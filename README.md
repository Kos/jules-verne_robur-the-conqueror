# whitespace-rendering-test

This branch has multiple builds of a simple page to demonstrate how whitespace is rendered on different punctuation on a Kobo device.

## Observations

Two separate issues have been observed:
- Extra space after a word contain non-breaking hyphen only happens on the kepub (se) build
- Extra space after degree and minute symbols kappens on all builds
- Neither issue happens when opening the ebook in calibre

## Device screenshots

Taken on Kobo Clara Colour

### Epub

<img alt="Epub" src="dist/test%20case.epub.jpg" width=50% height=50%>

### Epub (advanced)

<img  alt="Epub (advanced)" src="dist/test%20case_advanced.epub.jpg" width=50% height=50%>

### kepub (se)

<img alt="kepub (se)" src="dist/test%20case.kepub.epub.jpg" width=50% height=50%>

### kepub (kepubify)

<img alt="kepub (kepubify)" src="dist/test%20case_kepubify.kepub.epub.jpg" width=50% height=50%>
