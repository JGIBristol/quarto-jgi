# Quarto template for the Jean Golding Institute

Provides both `.html` and `.docx` export formats in the style of the [Jean Golding Institute](https://www.bristol.ac.uk/golding/).

## Installing

```bash
quarto use template jean-golding-institute/quarto-uob-jgi
```

This will install the extension and create an example qmd file that you can use as a starting place for your report.

## Usage

In the preamble of youe `.qmd` you can set:

```
---
title: Untitled
author: Your name
date: last-modified
abstract: |
  This is the abstract

  With multiple paragraphs
format: uob-jgi-html
---
```

or:

```
---
title: Untitled
author: Your name
date: last-modified
abstract: |
  This is the abstract

  With multiple paragraphs
format: uob-jgi-docx
---
```

Alternatively you can compile your document with:

```bash
quarto render document.qmd --to uob-jgi-docx
quarto render document.qmd --to uob-jgi-html
```

## Contributors

- James Thomas, Jean Golding Institute, University of Bristol

## License

The source code in this repository is licensed under the MIT License.

The Universtiy of Bristol logo is copyright the University of Bristol, all rights reserved. You may only use this if you are allowed to do so as a member of the university.
