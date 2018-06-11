---
title: Revealjs Introduction
theme : "moon"
transition: "zoom"
highlightTheme: "darkula"
slidenumber: true
separator: ^---
verticalSeparator: ^--
---

# Revealjs <br> Introduction <br> <small>by [Knecht](https://knowledge.rootknecht.net/about)</small>

---

# Why <br> Reveal?

---

## Do you know this?

![](bad-pp.jpg) <!-- .element height="65%" width="65%" -->

<small><small>[source](http://www.kothuria.com/bad-powerpoint-presentations/bad-powerpoint-presentations-examples-of-bad-powerpoint-presentations-slaved-template/)</small><small>

--

## How to diff?

![](ppt.png) <!-- .element height="40%" width="40%" -->

<small><small>Icon made by <a href="http://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></small></small>

--

## Do you know this?

![](markdown.png) <!-- .element height="100%" width="100%" -->

--

## How about that?

![](web.png) <!-- .element height="80%" width="80%" -->

<small><small>[source](https://www.planet-source-code.com/vb/2010Redesign/images/LangugeHomePages/HTML5_CSS_JavaScript.png)</small></small>

--

## Webtechnologies + Markup Language <br>= ???

---

# Revealjs

--

## What is that?

* Framework for HTML presentations <!-- .element: class="fragment" -->
* Support for Markdown, orgmode, rST, and more <!-- .element: class="fragment" -->
* Speaker notes, pdf export, API, and more <!-- .element: class="fragment" -->

--

## Syntax

![](code.png)  <!-- .element height="65%" width="65%" -->

<small>[source of this presentation](https://repo.rootknecht.net/open/revealjs-intro/) and a slightly more [extensive example](https://raw.githubusercontent.com/evilz/vscode-reveal/master/sample.md)</small>

--

## Tooling

<!-- .slide: data-background="./background.png" -->
<!-- .slide: style="color:red" -->

* Emacs, VS Code, Vim <!-- .element: class="fragment" -->
* R Studio, Jupyter <!-- .element: class="fragment" -->
* reveal-md, Pandoc <!-- .element: class="fragment" -->
* HTML <!-- .element: class="fragment" -->
* Many more  <!-- .element: class="fragment" -->

--

### Pandoc example

```bash
pandoc -t revealjs -s -o myslides.html myslides.md \
    -V revealjs-url=http://lab.hakim.se/reveal-js
```

--

### Reveal-md example

```bash
npm i -g reveal-md
reveal-md presentation.md --static public
```

--

### Revealjs & Gitlab Workflow

1. VS Code editing
1. Export with reveal-md
1. Push changes to Gitlab
1. Triggering [Gitlab CI](https://repo.rootknecht.net/open/revealjs-intro/pipelines)

---

# Benefits

* VCS, portable, small size
* Easy to write
* Powerful features
* Less is more

---

# To be considered

* No diagrams ootb
* Image sizing/alignment tricky
* Additional export
* Basic HTML knowledge required
* Browser compatibility

---

# Alternatives

* [Impressjs](https://impress.js.org/#/bored)
* [Remark](https://remarkjs.com/)
* [Shower](https://github.com/shower/shower)
* [Latex Beamer](https://de.wikipedia.org/wiki/Beamer_(LaTeX%29)
* [Prezi](https://prezi.com/de/)

---

### Links

* [Revealjs](https://github.com/hakimel/reveal.js)
* [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal)
* [Emacs](https://github.com/yjwen/org-reveal)
* [Pandoc](https://pandoc.org/)
* [reveal-md](https://github.com/webpro/reveal-md)