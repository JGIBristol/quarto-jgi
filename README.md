# Quarto templates for the Jean Golding Institute

Provides:

- Document templates for both `.html` and `.docx` files.
- Presentations for both `.html` (via RevealJS) and `.pptx` files.

in the style of the [Jean Golding Institute](https://www.bristol.ac.uk/golding/).

## Examples

| `.html` document | `.docx` document |
|------------------|------------------|
| ![Screenshot of HTML document generated with the template](.examples/document.html.png) | ![Screenshot of DOCX document generated with the template](.examples/document.docx.png) |

| `.html` presentation | `.pptx` presentation |
|----------------------|----------------------|
| ![Screenshot of HTML presentation generated with the template](.examples/presentation.html.png) | ![Screenshot of PPTX presentation generated with the template](.examples/presentation.pptx.png) |

## Install

For new projects:

```bash
quarto use template jgibristol/quarto-jgi
```

This will install the extension and create example `.qmd` files that you can use as a starting place for your report.

For existing projects:

```bash
quarto add jgibristol/quarto-jgi
```

This will install the extension but not create any example files.

## Usage

In the preamble of your `.qmd` you can set:

```md
---
title: Untitled
author: Your name
date: last-modified
abstract: This is the abstract
format: jgi-html
---
```

where format can be one of the following:

```md
format: jgi-html
format: jgi-docx
format: jgi-revealjs
format: jgi-pptx
```

Alternatively, you can override the document format at the command line:

```bash
quarto render document.qmd --to jgi-html
quarto render document.qmd --to jgi-docx
quarto render document.qmd --to jgi-revealjs
quarto render document.qmd --to jgi-pptx
```

## Contributors

- [James Thomas](https://github.com/jatonline), Jean Golding Institute, University of Bristol

## License

The source code in this repository is licensed under the MIT License.

The University of Bristol logo is copyright the University of Bristol, all rights reserved. You may only use this if you are allowed to do so as a member of the university.
