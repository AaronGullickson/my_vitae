# My Data Driven CV

This repository includes and R Markdown file for generating my Curriculum Vitae using a data driven approach ala Nick Strayer's [datadrivencv](http://nickstrayer.me/datadrivencv/). 
A [previous repository](https://github.com/AaronGullickson/cv) used that template, but I decided I did not like the specific look of it and wanted something a little more traditional.
Thus, I switched to the [vitae](https://pkg.mitchelloharawild.com/vitae/index.html) R package to build a PDF of my CV using the `hyndman` template. 

The data for the CV is kept in a google sheet document that the the R Markdown file reads and processes. Unfortunately, the `vitae` package currently does not handle markdown syntax within the fields
very well. However, I use this same google sheet to produce an HTML CV in my [website repo](https://github.com/AaronGullickson/minimo_blog) so I could not remove it. At the moment, I have some (hackish)
functions that clean out the markdown syntax and perform some other formatting. 
