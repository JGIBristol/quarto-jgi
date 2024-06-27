# Quarto template for the Jean Golding Institute

Provides:

- Document templates for both `.html` and `.docx` files.
- Presentations for both `.html` (via RevealJS) and `.pptx` files.

in the style of the [Jean Golding Institute](https://www.bristol.ac.uk/golding/).

## Installing

```bash
quarto use template jgibristol/quarto-jgi
```

This will install the extension and create example `.qmd` files that you can use as a starting place for your report.

## Usage

In the preamble of you `.qmd` you can set:

```
---
title: Untitled
author: Your name
date: last-modified
abstract: |
  This is the abstract

  With multiple paragraphs
format: jgi-html
---
```

where format can be one of the following:

```
format: jgi-html
format: jgi-docx
format: jgi-revealjs
format: jgi-pptx
```

Alternatively you can compile your document with:

```bash
quarto render document.qmd --to jgi-html
quarto render document.qmd --to jgi-docx
quarto render document.qmd --to jgi-revealjs
quarto render document.qmd --to jgi-pptx
```

## Contributors

- James Thomas, Jean Golding Institute, University of Bristol

## License

The source code in this repository is licensed under the MIT License.

The University of Bristol logo is copyright the University of Bristol, all rights reserved. You may only use this if you are allowed to do so as a member of the university.
