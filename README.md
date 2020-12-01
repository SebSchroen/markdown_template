# Leibniz University Hannover RMarkdown Template

This is a simplified thesis template in compliance with the formal guidelines of the School of Economics and Management at Leibniz University Hannover. 
The template was inspired by the [thesisdown package](https://github.com/ismayc/thesisdown), but is simplified in many dimensions. 
The template explains how to handle those adjustments.

## Prerequisites

### RStudio/ RMarkdown

Make sure to have the latest version of RStudio installed on your computer. 
The template will work with RStudio 1.3 upwards.
To make sure that all rmarkdown depencies are installed, install the package `rmarkdown` as follows:

```
install.packages(rmarkdown)

```


### LaTeX
Before using the template, make sure to have a working LaTeX installation on your computer. 
By far the easiest way is the R package `tinytex`:

```
install.packages(tinytex)

tinytex::install_tinytex()

```
This might take a while. 
Make sure to restart RStudio after installation. 

**Note: The first compiling of the document might take a couple of minutes because tinytex installs package depencies in the background.**



## Citation style

The folder CSL contains the citation style, the default is APA (American Psychological Association) as provided by [Zotero](https://www.zotero.org/styles/). 
Other specific styles are available in the [official repository](https://github.com/citation-style-language/styles#readme) for Citation Style Language citation styles.
To change the style, store the file in the designated folder and change the yaml header accordingly.

## Acknowledgement

The contribution of Brian von Knoblauch and Leon Kowalke to this template is gratefully acknowledged. 

## License

This template is based on the [pandoc default template](https://github.com/jgm/pandoc-templates) by John MacFarlane. The template is licensed as follows:

All of the templates in this repository are dual licensed, under both the GPL (v2 or higher, same as pandoc) and the BSD 3-clause license (included below).

Copyright (c) 2014--2019, John MacFarlane

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

  + Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

  + Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

  + Neither the name of John MacFarlane nor the names of other contributors may be used to endorse or promote products derived from this software without specific prior written permission.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
