au13uwgeoarchlab
================

Simple exploratory anayses and visualisation of geoarchaeological data for the UW ARCHY 482/486 Geoarchaeology class of Autumn 2013. The objective is to promote reproducible research in geoarchaeology by making the analyses explicit and supporting reporting of the results in a R Markdown file that includes text, figures, and the code that generated the results. 

How to install
----
First, make sure you've got Hadley Wickham's excellent devtools package installed. If you haven't got it, you can get it with these lines in your R console:

```
install.packages(pkgs = "devtools", dependencies = TRUE)
```
Then, use the `install_github()` function to fetch this package from github:

```
require(devtools)
install_github(repo = "au13uwgeoarchlab", username = "UW-Georchaeology-Lab")
```

How to get started
----
First, get the [lab report template R Markdown file](https://raw.github.com/UW-Georchaeology-Lab/au13uwgeoarchlab/master/my_lab_report.Rmd) by copying and pasting into a R markdown window in [RStudio][rstudio]. Then study the lab report template carefully because it shows how all of the functions in this package should be used.


Limitations and License
----
Currently this package is limited to the exploration of the data collected during Autumn 2013. 

Copyright (C) 2013  Ben Marwick

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA. 


  [rstudio]:http://www.rstudio.com/ide/download/
  
