---
title: 'Slide Demo'
center: true
transition: slide
background: #1c1c1c
preloadIframes: false
highlightTheme: 'monokai'
maxScale: 0.8
controls: false
width: 960
height: 540
---


<!-- .slide template="[[template]]" bg="#1c1c1c" -->

<grid
	  align="center"
	  drop="center"
	  drag="65 25"
	  style="background-color:#282828; border-radius:8px;">

# Slides Demo

<a href="https://github.com/saforem2/Notes-Demo/blob/master/slides/demo/slides.md">
<i class="fab fa-github fa-1x" ></i>
<code><span style="color: #BDBDBD !important; background-color:#282828 !important;">saforem2/Notes-Demo/slides</span></code>
</a>

</grid>

<grid drag="100 10" drop="0 70" align="bottomleft" >

Sam Foreman <!-- .element style="color:#505050;" -->

<span style="font-size:0.9em; color:#505050; padding:0px; margin:0px; text-align:center!important;">2023-02-19</span>

</grid>


---

<!-- .slide template="[[template]]" bg="#1C1C1C" -->

# Interesting Title

- Blah

---

<!-- .slide template="[[template]]" bg="#1c1c1c"  style="text-align: left;" width="100%" -->

# Thank you!

- Feel free to reach out!
-  [<i class="fab fa-twitter"></i>](https://www.twitter.com/saforem2) [<i class="far fa-paper-plane"></i>](mailto:///foremans@anl.gov) [<i class="fas fa-home"></i>](https://samforeman.me)

> [!INFO] Acknowledgements
> This research used resources of the Argonne Leadership Computing Facility, which is a DOE Office of Science User Facility supported under Contract DE-AC02-06CH11357.
<!-- .element style="max-width:90%; text-align:left;" -->

---

<!-- .slide template="[[template]]" bg="#1c1c1c" -->


> [!INFO] Acknowledgements
> This research used resources of the Argonne Leadership Computing Facility, which is a DOE Office of Science User Facility supported under Contract DE-AC02-06CH11357.
<!-- .element style="max-width:90%;" -->



---

<!-- .slide template="[[template]]" bg="#1c1c1c" -->

# Thank you!

- Organizers
- ALCF Data Science & Operations

- Feel free to reach out!

<br>

<grid drop="13 37" drag="60 20">

[<i class="fas fa-home"></i>](https://samforeman.me) <!-- .element style="padding-right:17px; font-size:1.2em;" -->
[<i class="far fa-paper-plane"></i>](mailto:///foremans@anl.gov) <!-- .element style="padding-left:17px; padding-right:17px; font-size:1.2em;" -->
[<i class="fab fa-twitter"></i>](https://www.twitter.com/saforem2) <!-- .element style="padding-left:17px; padding-right:17px; font-size:1.2em;" -->
</grid>


> [!info] Acknowledgements
> This research used resources of the Argonne Leadership Computing Facility, which is a DOE Office of Science User Facility supported under Contract DE-AC02-06CH11357.
<!-- .element style="max-width:90%;" -->

---


<style>

:root {
	--callout-radius: 5px;
	--cm-inline-background: #242424;
	--cm-inline-foreground: #00CCFF;
    --r-heading-text-transform: none;
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
    --r-code-font: 'JuliaMono', 'Hack', 'VictorMono', "agave Nerd Font", monospace;
    --r-link-color: #03A9F4;
    --r-link-color-dark: #f92672;
    --r-link-color-hover: #63ff51;
	--r-accent-color: #77CA29;
    --r-controls-color: #228BE6;
    --r-progress-color: #404040;
	--r-header-accent: #1E8BC9;
    --r-selection-background-color: rgba(255, 255, 0, 0.15);
    --r-selection-color: rgb(255, 255, 0);
    --r-main-color: #c8c8c8;
    --text-muted: #757575;
    --text-faint: #404040;
    --r-heading-color: #FFF;
    --r-background-color: #ffffff;
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
	--cm-error-bg: #ff5370;
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
	--cm-background-color: #202020;
	--cm-active-line-background-color: #353a50;
	--cm-foreground-color: #bdbdbd;
      -webkit-font-smoothing:subpixel-antialiased;
	--chart-color-1: #ff00ff;
	--chart-color-x: rgb(255,255,255);
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
  min-width:max-content;
  max-width:min-content;
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

.row {
  display: flex;
}

.column {
  flex: 50%;
}

.horizontal_dotted_line{
  border-bottom: 2px dotted gray;
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
  border-color:#66666640;
  padding: auto;
  margin:auto;
}

.callout {
  border-style: none;
  border-color: RGBA(var(--callout-color), var(--callout-border-opacity));
  border-width: var(--callout-border-width);
  border-radius: var(--callout-radius);
  margin: 1em 0;
  mix-blend-mode: var(--callout-blend-mode);
  background-color: rgba(var(--callout-color), 0.1);
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
  /*border:1px solid red;*/
  background:var(--cm-background-color);
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
  /* border:1px solid green; */
  font-size:0.9em!important;
  line-height:inherit;
  background:var(--cm-inline-background);
  color: var(--cm-inline-foreground);
  border-radius:3px;
  letter-spacing: -0.45px!important;
  word-spacing: -0.5px!important;
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

.hljs-comment, .hljs-quote, .hljs-deletion, .hljs-meta {
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

.strong {
	color: #F92672!important;
	font-weight: 800;
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

</style>