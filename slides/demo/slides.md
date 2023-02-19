---
title: 'Slides'
highlightTheme: monokai
defaultTemplate: "template"
center: true
width: 960
height: 540
---

<!-- .slide template="[[template]]" bg="#1c1c1c" -->

<grid align="center" drop="center" drag="65 25" style="background-color:#282828; border-radius:8px;">

# Slides Demo

<a href="https://github.com/saforem2/Notes-Demo/blob/master/slides/demo/slides.md">

<i class="fab fa-github fa-1x" ></i>
<code><span style="color:#bdbdbd!important;background-color:#282828!important;">saforem2/Notes-Demo/slides/demo/slides</span></code>
</p>

</a>

</grid>

<grid drag="100 10" drop="0 70" align="bottomleft" >

Sam Foreman <!-- .elemenstyle=""le="color:#505050;" -->

<span style="font-size:0.9em; color:#505050; padding:0px; margin:0px; text-align:center!important;">2023-02-19</span>

</grid>

---

<!-- .slide template="[[template]]" bg="#1c1c1c" -->
# Slides Demo

<i class="callout">
Testing

</i>

---

# Slide 2

---

# Slide 3

---



<style>

:root {
	--cm-inline-background: #242424;
	--cm-inline-foreground: #00CCFF;
    --r-heading-text-transform: none;
    --r-heading-font: 'Inter', 'Arial', "OpenSans-Bold", "Open Sans", Helvetica, Impact, sans-serif;
    --r-main-background-color: #1c1c1c!important;
    --r-main-font: 'Inter', "Arial", "Open Sans", "Coming Soon", "SourceSansPro", Helvetica Neue, sans-serif;
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

.reveal pre code {
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

.bottomright {
  position: absolute;
  bottom: 8px;
  right: 16px;
  font-size: 18px;
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
  border-left: 6px solid rgb(var(--callout-color));
  background-color: #;
  opacity:95%;
  text-align:left;
  margin-left: 4%;
  border-radius:2px;
  page-break-inside: avoid;
}

.callout > ul,ol {
	line-height:1.5em!important;
}

.callout-title {
  display: flex;
  text-align:left;
  color: var(--callout-color);
  padding-left:10px;
  gap: 10px;
  font-size:1em;
  top: 0;
  position:relative;
  margin-top:0px!important;
  margin-bottom:0em!important;
  padding-top:0px!important;
  padding-bottom:0px!important;
  border-radius:2px;
  background-color: rgba(var(--callout-color), 0.3);
}

.callout-content {
	padding: 1px!important;
	top: 0;
	margin-left: 1%;
    padding-bottom:0.75em;
	padding:auto;
    line-height:1em!important;
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
  white-space: pre;
}

.reveal pre {
white-space: pre;
}

.reveal sup {
	font-size:0.6em;
}

div.code {
  white-space: pre;
}

.reveal .code-wrapper code {
  white-space: pre;
}

</style>