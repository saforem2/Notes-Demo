<%*
/*
```javascript
*/
const installStyleHook = () => {
    if(!window.ExcalidrawAutomate) return false;
	ExcalidrawAutomate.onCanvasColorChangeHook = (ea, view, color) => {
		const doc = view.ownerDocument;
		
		const dark = "#404040";
		const darker = "#202020";
		const light = "#f4f4f4";
		const lighter = "#fbfbfb";
		const step = 5;
		const mixRatio = 0.8;
		
		const cmBG = () => ea.getCM(color);
		
		const isDark = cmBG().isDark();
		
		const accent = () => {
		  const s = doc.querySelector("body").style;
		  return ea.getCM(`hsl(${s.getPropertyValue("--accent-h")},${
		    s.getPropertyValue("--accent-s")},${s.getPropertyValue("--accent-l")})`).mix({color:isDark?dark:light, ratio:0.6});
		}
		    
		const updateCSSClassVariable = (className, payload) => {
		  for(stylesheet of doc.styleSheets) {
		    for(rule of stylesheet.rules) {        
		      if (rule.selectorText !== className) continue;
			  let cssText = rule.cssText;
			  let changed = false;
			  payload.forEach(pl => {
			    const reg = new RegExp(`${pl.var}:\\s[^;]*`);
			    if(cssText.match(reg)) {
				  cssText = cssText.replace(reg,`${pl.var}: ${pl.val}`);
				  changed = true;
			    }
			  });
			  if(changed) {
			    stylesheet.deleteRule(rule);
			    stylesheet.insertRule(cssText);
			  }
		    }
		  }
		}
		
		const str = (cm) => cm.stringHEX({alpha:false});
		
		const gray1 = cmBG().mix({color:isDark?darker:lighter, ratio:mixRatio});
		const gray2 = cmBG().mix({color:isDark?dark:light, ratio:mixRatio});
		const text = cmBG().mix({color:isDark?lighter:darker, ratio:mixRatio})
		
		updateCSSClassVariable (
		  ".excalidraw",[
			  {
			    var: "--color-primary",
			    val: str(accent())
			  },
			  {
			    var: "--color-primary-darker",
			    val: str(accent().darkerBy(step))
			  },
			  {
			    var: "--color-primary-darkest",
			    val: str(accent().darkerBy(step))
			  },
			  {
			    var: "--button-gray-1",
			    val: str(gray1)
			  },
			  {
			    var: "--button-gray-2",
			    val: str(gray2)
			  },
			  {
			    var: "--input-border-color",
			    val: str(gray1)
			  },
			  {
			    var: "--input-bg-color",
			    val: str(gray2)
			  },
			  {
			    var: "--input-label-color",
			    val: str(text)
			  },
			  {
			    var: "--island-bg-color",
			    val: gray2.alphaTo(0.93).stringHEX()
			  },
			  {
			    var: "--icon-fill-color",
			    val: str(text)
			  },
			  {
			    var: "--text-primary-color",
			    val: str(text)
			  },
			  {
			    var: "--overlay-bg-color",
			    val: gray2.alphaTo(0.6).stringHEX()
			  },
			  {
			    var: "--popup-bg-color",
			    val: str(gray1)
			  },
	          {
	            var: "--color-gray-100",
	            val: str(text)
	          },
	          {
	            var: "--sidebar-border-color",
	            val: str(gray1)
	          },
	          {
	            var: "--color-primary-light",
	            val: str(gray1)
	          },
		  {
	            var: "--button-hover-bg",
	            val: str(gray1)
	          },
		  {
	            var: "--sidebar-bg-color",
	            val: gray2.alphaTo(0.93).stringHEX()
	          },
	          {
	            var: "--sidebar-shadow",
	            val: str(gray1)
	          },
		  ]
		);   
	};
	const view = app.workspace.activeLeaf?.view;
	if(view && view.getViewType() === "excalidraw") {
	  if(!view.isLoaded || !view.excalidrawAPI) return true;
	  ExcalidrawAutomate.onCanvasColorChangeHook(
	    ExcalidrawAutomate,
	    app.workspace.activeLeaf.view,
	    view.excalidrawAPI.getAppState().viewBackgroundColor
	  )
	}
    return true;
}

setTimeout(()=>{
  console.log("Installing Excalidraw style hook...");
  if(installStyleHook()) return;
  console.log("Failed to install style hook...");
  setTimeout(()=>{
    if(installStyleHook()) {
      console.log("Excalidraw style hook installed successfully");
    }
    console.log("Excalidraw style hook NOT installed");
  },10000);
},5000);
%>