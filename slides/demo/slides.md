---
title: 'Slides'
highlightTheme: monokai
defaultTemplate: "template"
center: true
maxScale: 0.8
width: 960
height: 540
css:
  - ./app.css
---

<!-- .slide template="[[template]]" bg="#1c1c1c" -->

<grid
	  align="center"
	  drop="center"
	  drag="50 25"
	  style="background-color:#282828; border-radius:8px;">

## Slides Demo <!-- .element style="font-weight:900; font-size:1.5em" -->

<a href="https://github.com/saforem2/Notes-Demo/blob/master/slides/demo/slides.md">
<i class="fab fa-github fa-1x" ></i>
<code><span style="color:#bdbdbd!important;background-color:#282828!important;">saforem2/Notes-Demo/slides</span></code>
</a>

</grid>

<grid drag="100 10" drop="0 70" align="bottomleft" >

<a href="https://samforeman.me">

<i class="fas fa-home" style=""></i>
<span style="color: #BDBDBD;">Sam Foreman</span>
</a>

<span style="font-size:0.8em; color:#505050; padding:0px; margin:0px; text-align:center!important;">2023-02-19</span>

</grid>

---

<!-- .slide template="[[template]]" bg="#1c1c1c" -->
# Callouts

- Icons are broken for some reason???

> [!example]
> Here is an Example for an Callout in a Slide. Callouts support dark and white backgrounds and could be sized by annotations
</grid>

---

<!-- .slide template="[[template]]" bg="#1c1c1c" style="text-align:left!important; align:left!important" -->

# Thank you!

- Feel free to reach out! <br>
<split gap="2">

   [<i class="fab fa-twitter"></i>](https://www.twitter.com/saforem2)
   [<i class="far fa-paper-plane"></i>](mailto:///foremans@anl.gov)
   [<i class="fas fa-home"></i>](https://samforeman.me)
</split>

> [!INFO] Acknowledgements
> This research used resources of the Argonne Leadership Computing Facility, which is a DOE Office of Science User Facility supported under Contract DE-AC02-06CH11357.
<!-- .element style="max-width:90%; text-align:left;" -->

---

<style>

:root {
    --callout-radius:5px;
    --r-math-color:#FAFAFA;
    --cm-inline-background: #242424;
    --cm-inline-foreground: #00CCFF;
    --r-heading-text-transform: none;
    --primaryBorderColor: #666666;
    --r-main-background-color: #1c1c1c!important;
    --r-heading-letter-spacing: -0.45px;
    --r-heading-word-spacing: 0.5px;
    --r-heading-text-transform: none;
    --r-heading-text-shadow: none;
    --r-heading-font-weight: 700;
    --r-heading1-text-shadow: none;
    --r-main-font-size: 22px;
    --r-main-line-height: 1.5em;
    --r-monospace-font-size: 18px;
    --r-heading1-size: 1.33em;
    --r-heading2-size: 1.25em;
    --r-heading3-size: 1.2em;
    --r-heading4-size: 1.15em;
    --r-heading5-size: 1.05em;
    --r-heading6-size: 1.025em;
    --r-heading-line-height:1.5em;
    --r-main-font-family: 'Inter';
    --r-code-font: "JuliaMono", "agave Nerd Font", "Monaco", "Hack", "VictorMono", monospace;
    --r-link-color: #03A9F4;
    --r-link-color-dark: #f92672;
    --r-link-color-hover: #63ff51;
    --r-accent-color: #77CA29;
    --r-controls-color: #228BE6;
    --r-progress-color: #404040;
    --r-header-accent: #1E8BC9;
    --r-selection-background-color: RGBA(255, 255, 0, 0.15);
    --r-selection-color: RGB(255, 255, 0);
    --r-main-color: #c8c8c8;
    --text-muted: #757575;
    --text-faint: #404040;
    --r-heading-color: #FFF;
    --r-background-color: #1c1c1c;
    --cm-keyword: #c792ea;
    --cm-atom: #f78c6c;
    --cm-number: #ff5370;
    --cm-type: #decb6b;
    --cm-def: #82aaff;
    --cm-property: #c792ea;
    --cm-variable: #f07178;
    --cm-variable-2: #EEFFFF;
    --cm-variable-3: #f07178;
    --cm-definition: #82aaff;
    --cm-callee: #89ddff;
    --cm-qualifier: #decb6b;
    --cm-operator: #89ddff;
    --cm-hr: #98e342;
    --cm-link: #696d70;
    --cm-header: #da7dae;
    --cm-builtin: #ffcb6b;
    --cm-meta: #ffcb6b;
    --cm-matching-bracket: #FFFFFF;
    --cm-tag: #ff5370;
    --cm-tag-in-comment: #ff5370;
    --cm-string-2: #f07178;
    --cm-bracket: #ff5370;
    --cm-comment: #676e95;
    --cm-string: #c3e88d;
    --cm-attribute: #c792ea;
    --cm-attribute-in-comment: #c792ea;
    --cm-background-color: #1c1c1c;
    --cm-active-line-background-color: #353a50;
    --cm-foreground-color: #AE81FF;
    --code-normal: #AE81FF;
    -webkit-font-smoothing:subpixel-antialiased;
    --font-smoothing:subpixel-antialiased;
    --chart-color-1: #ff00ff;
    --chart-color-x: RGB(255.0,255.0,255.0);
	  --admonition-details-icon: url("data:image/svg+xml;charset=utf-8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'><path d='M8.59 16.58L13.17 12 8.59 7.41 10 6l6 6-6 6-1.41-1.42z'/></svg>");
	  --admonition-margin-top: 1.5625em;
	  --admonition-margin-bottom: var(--admonition-margin-top);
	  --admonition-margin-top-lp: 0px;
	  --admonition-margin-bottom-lp: 12px;
}

.standout{
    background: var(--cm-background-color);
    padding:5px;
    font-weight:700;
    border-radius:6px;
}

.reveal pre {
  display:block;
  margin:auto;
  width:auto;
  font-family: var(--r-code-font);
  font-size: var(--r-monospace-font-size);
  padding: auto;
  white-space: pre-wrap;
}

.reveal p {
  margin:auto!important;
  padding:auto!important;
}

.reveal pre code {
    display: inline-block;
    top: 2px;
    white-space: pre;
    bottom: 2px;
    margin:auto;
    padding:auto;
    font-size: 0.8em;
    background:var(--cm-background-color);
    color: var(--cm-foreground-color)!important;
    text-align: justify;
    letter-spacing: -0.45px!important;
    word-spacing: -0.5px!important;
}

.reveal {
    font-family: var(--r-main-font), sans-serif;
    font-size: var(--r-main-font-size);
    font-weight: normal;
    color: var(--r-main-color);
    background-color: var(--r-main-background-color);
}

.reveal blockquote p {
    color: var(--text-muted);
    font-style: normal !important;
    font-align: left;
    display: inline;
    text-align: left;
}

.reveal blockquote em{
  color: var(--text-muted);
  text-align: left;
}

.reveal blockquote {
  border-radius: 8px !important;
  margin: 0.5rem 0rem 0.5rem 0rem;
  text-align: left;
  padding-top: 1rem;
  padding-left: 2rem;
  padding-bottom: 1rem;
  padding-right: 2rem;
  width: auto;
  font-style: normal !important;
}

.reveal blockquote {
	font-size: unset;
	margin: auto;
	padding:auto;
}


.reveal ul, ol {
	text-align:left;
}

.reveal ul ul,
.reveal ul ol,
.reveal ol ol,
.reveal ol ul {
  text-align:left;
}

.reveal ul ul {
    list-style: circle;
}
.container {
  position: relative;
}

.make-it-pop {
  filter: drop-shadow(0 0 10px purple);
}

@media (max-width: 95%) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}

.footer {
  font-size: 60%;
  vertical-align:bottom;
  color:#bdbdbd;
  font-weight:400;
  margin-left:-5px;
}
.note {
  color:#f8f8f8;
  border-radius:8px;
  background-color:#35353540;
  width: max-content;
  border-color:#66666640;
  padding: auto;
  margin:auto;
}

#blue {
  color: #00CCFF;
}

#red {
  color: #FF5252;
}

.callout {
  border-style: none;
  border-color: RGBA(var(--callout-color), var(--callout-border-opacity));
  border-width: var(--callout-border-width);
  border-radius: var(--callout-radius);
  margin: 1em 0;
  mix-blend-mode: var(--callout-blend-mode);
  background-color: RGBA(var(--callout-color), 0.1);
  padding: var(--callout-padding);
}
.callout-title {
  font-size: var(--callout-title-size);
  color: RGB(var(--callout-color));
  background-color: RGB(var(--callout-color), 0.0);
  line-height: var(--line-height-tight);
  font-weight: 700;
}
.callout-content {
  overflow-x: auto;
  padding: auto;
  background-color: var(--callout-content-background);
}
.callout-icon {
  flex: 0 0 auto;
  padding: auto;
  display: flex;
  align-self: center;
}
.callout-icon .svg-icon {
  color: RGB(var(--callout-color));
}
.callout-title-inner {
  font-weight: var(--bold-weight);
  color: var(--callout-title-color);
}
.callout-fold {
  display: flex;
  align-items: center;
  padding-right: var(--size-4-2);
}

.reveal .code-wrapper code {
	width: 98%;
}
.reveal code {
  font-family: var(--r-code-font);
  text-transform: none;
  tab-size: 4;
  background-color:var(--cm-background-color);
  color: var(--cm-foreground-color);
  border-radius:2px;
  letter-spacing: -0.45px!important;
  word-spacing: -0.5px!important;
}

.reveal pre code {
	padding: auto;
	border:none;
	border-radius:2px;
	font-size:0.9em;
	margin:auto;
	background: var(--cm-background-color);
}
.reveal p code {
  font-family: var(--r-code-font);
  text-transform: none;
  tab-size: 4;
  padding:auto;
  font-size:0.9em!important;
  line-height:inherit;
  background:var(--cm-inline-background);
  color: var(--cm-inline-foreground);
  border-radius:3px;
  letter-spacing: -0.45px!important;
  word-spacing: -0.5px!important;
}

mjx-container[jax="CHTML"][display="true"] mjx-math {
  color: var(--r-math-color);
}

mjx-math {
  color: var(--r-math-color);
  background: none!important;
  padding:unset;
  vertical-align:inherit;
}
#customcontrols > ul {
  display: none!important;
}

#customcontrols button {
  display: none!important;
}

.reveal .slides > section.present, .reveal .slides > section > section.present {
  min-height: 100% !important;
  display: flex !important;
  flex-direction: column !important;
  justify-content: center !important;
  position: absolute !important;
  top: 0 !important;
}

section > h1 {
  position: absolute !important;
  top: 0 !important;
  margin-left: auto !important;
  margin-right: auto !important;
  left: 0 !important;
  right: 0 !important;
}

h1 {
	border-bottom: 3px solid var(--r-header-accent);
	text-align: left!important;
	min-width: max-content;
	max-width: min-content;
}

.print-pdf .reveal .slides > section.present, .print-pdf .reveal .slides > section > section.present {
  min-height: 770px !important;
  position: relative !important;
}

.hljs {
    background: var(--cm-background-color) !important;
	font-size:inherit;
}

.hljs-main {
	color: #ff5252
}

.hljs-built_in {
  color: #63ff5b;
}

.hljs-comment, .hljs-quote, .hljs-deletion {
	color: #454545;
}

.hljs-params{
	color: #03A9F4;
}

.hljs-meta {
	color: #AE81FF;
}

.hljs-string {
	color: #FFFF00;
}

strong {
	color: #FF5252!important;
	font-weight: 700;
}

ul {
	margin-left: 0;
	padding-left:1em;
}

ol {
	margin-left: 0;
	padding-left:1em;
}

.reveal .code-wrapper code {
 st white-space: unset;
}

.reveal pre {
white-space: pre-wrap;
}


.reveal sup {
	font-size:0.6em;
}

.markdown-rendered code {
  color: var(--code-normal)!important;
  font-family: var(--font-monospace);
}

body.fallback-highlighting[class*="theme-"] .markdown-preview-view pre.cm-s-obsidian[class*="language-"], body.fallback-highlighting[class*="theme-"] .markdown-preview-view code[class*="language-"], body.fallback-highlighting[class*="theme-"] .markdown-preview-view .HyperMD-codeblock, body.fallback-highlighting[class*="theme-"] .markdown-preview-view .cm-hmd-codeblock {
  --font-monospace: var(--cm-font-monospace);
  color: var(--cm-foreground-color);
  font-family: var(--cm-font-monospace);
  font-weight: var(--cm-font-weight);
  line-height: var(--cm-line-height);
  font-size: var(--cm-font-size);
  white-space: var(--cm-wrap-lines);
}

.reveal .code-wrapper code {
  color: #B0BEC5;
  font-family: var(--r-code-font);
  font-size: 18px;
  line-height:1.1em;
}
/* Content */

/* Blockquotes */

.markdown-preview-view blockquote {
	padding: 0 0 0 var(--nested-padding);
	font-size: var(--blockquote-size);
}
.markdown-source-view.mod-cm6.is-live-preview .HyperMD-quote,
.markdown-source-view.mod-cm6 .HyperMD-quote {
	font-size: var(--blockquote-size);
}
.is-live-preview .cm-hmd-indent-in-quote {
	color: var(--text-faint);
}

/* Callouts */

.is-live-preview.is-readable-line-width > .cm-callout .callout {
	max-width: var(--max-width);
	margin: 0 auto;
}

.callouts-outlined .callout .callout-title {
	background-color: var(--background-primary);
	margin-top: -24px;
	z-index: 200;
	width: fit-content;
	padding: 0 0.5em;
	margin-left: -0.75em;
	letter-spacing: 0.05em;
	font-variant-caps: all-small-caps;
}
.callouts-outlined .callout {
	overflow: visible;
	--callout-border-width: 1px;
	--callout-border-opacity: 0.5;
	--callout-title-size: 0.8em;
	--callout-blend-mode: normal;
	background-color: transparent;
}

.callouts-outlined .cm-embed-block.cm-callout {
	padding-top: 12px;
}

.callouts-outlined .callout-content .callout {
	margin-top: 18px;
}

.callout[data-callout="custom-question-type"] {
	--callout-color:  '#FF5252';
	 --callout-icon: lucide-alert-circle;
 }

</style>

<script>
var config = { theme: 'default', logLevel: 'fatal', securityLevel: 'strict', startOnLoad: true, arrowMarkerAbsolute: false, er: { diagramPadding: 20, layoutDirection: 'TB', minEntityWidth: 100, minEntityHeight: 75, entityPadding: 15, stroke: 'gray', fill: 'honeydew', fontSize: 12, useMaxWidth: true, }, flowchart: { diagramPadding: 8, htmlLabels: true, curve: 'basis', }, sequence: { diagramMarginX: 50, diagramMarginY: 10, actorMargin: 50, width: 150, height: 65, boxMargin: 10, boxTextMargin: 5, noteMargin: 10, messageMargin: 35, messageAlign: 'center', mirrorActors: true, bottomMarginAdj: 1, useMaxWidth: true, rightAngles: false, showSequenceNumbers: false, }, gantt: { titleTopMargin: 25, barHeight: 20, barGap: 4, topPadding: 50, leftPadding: 75, gridLineStartPadding: 35, fontSize: 11, fontFamily: '"Open Sans", sans-serif', numberSectionStyles: 4, axisFormat: '%Y-%m-%d', topAxis: false, }, }; mermaid.initialize(config);
</script>