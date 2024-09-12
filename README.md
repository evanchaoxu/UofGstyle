# University of Glasgow Quarto Theme

This repository contains a (personal) template for University of Glasgow Quarto documents. It includes an extension that can style revealjs slides, PDFs, and HTML documents.

## Installation and use

To install the Quarto extension to the current directory:

``` bash
quarto install extension evanchaoxu/UofGstyle
```

To install the Quarto extension and copy the template file to the current directory:

``` bash
quarto use template evanchaoxu/UofGstyle
```

This will copy a template file for revealjs slides.

If you want to use the PDF template instead, set:

``` yaml
format: UofGstyle-pdf
```

or for HTML documents:

``` yaml
format: UofGstyle-html
```
