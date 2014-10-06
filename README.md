# Rmd2html
This repo contains a set of scripts that turn a set of Rmd files into a beautiful, fluid html page that using twitter bootstrap.
The worflow is the following:

1. Run [Knitr](http://yihui.name/knitr/) to convert the Rmd files to produce md files and figures.
2. Run [pandoc](http://johnmacfarlane.net/pandoc/) to oncatenate the md files and convert them to html.

Pandoc uses a custom template the nicely renders the md files in a fluid html page using twitter [Bootstrap](http://getbootstrap.com/)

A sample output file is available [here](https://rawgit.com/tleonardi/rmd2html/master/report/report.html)
