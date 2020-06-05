
<!--  use the --webtex argument in the YAML to render equations -->

<!-- badges: start -->

<!-- badges: end -->

To recreate the article: *A nutrient-driven tipping point catalysed
marine anoxia during the end-Permian mass extinction*, published in
*Nature Geoscience*, run the R Markdown file (.Rmd) with *knitr* (Xie
2020, 2015, 2014; Allaire et al. 2020; Xie, Allaire, and Grolemund 2018)
on the programming platform R (R Core Team 2020). Instructions on the
installation and the usage of Rmarkdown for Rstudio can be found on the
website: <https://rmarkdown.rstudio.com/>. Several additional packages
are required to recreate data processing, statistics and visualization
of the geochemical datasets and geographic maps, including:*bibtex*
(Francois 2017), *Cairo* (Urbanek and Horner 2019), *gtable* (Wickham
and Pedersen 2019), *gridExtra* (Auguie 2017), *png* (Urbanek 2013),
*lattice* (Sarkar 2008), RColorBrewer (Neuwirth 2014), *readxl* (Wickham
and Bryan 2019), *rgdal* (R. Bivand, Keitt, and Rowlingson 2019),
*rgeos* (R. Bivand and Rundel 2019), *sp* (Pebesma and Bivand 2005;
Bivand, Pebesma, and Gomez-Rubio 2013), and *tidyverse* (Wickham 2017).
The library *marelac* (Soetaert and Petzoldt 2018) was used for chemical
data transformations. Complete the pathway to approriate directory on
lines 6, 7 and 78 of *Schobbenetal\_main.Rmd* and lines 6, 7 and 82 of
*Schobbenetal\_SI.Rmd* before rendering the files\[1\].

# References

<div id="refs" class="references">

<div id="ref-rmarkdown1">

Allaire, JJ, Yihui Xie, Jonathan McPherson, Javier Luraschi, Kevin
Ushey, Aron Atkins, Hadley Wickham, Joe Cheng, Winston Chang, and
Richard Iannone. 2020. *Rmarkdown: Dynamic Documents for R*.
<https://github.com/rstudio/rmarkdown>.

</div>

<div id="ref-gridExtra">

Auguie, Baptiste. 2017. *GridExtra: Miscellaneous Functions for "Grid"
Graphics*. <https://CRAN.R-project.org/package=gridExtra>.

</div>

<div id="ref-rgdal">

Bivand, Roger, Tim Keitt, and Barry Rowlingson. 2019. *Rgdal: Bindings
for the ’Geospatial’ Data Abstraction Library*.
<https://CRAN.R-project.org/package=rgdal>.

</div>

<div id="ref-rgeos">

Bivand, Roger, and Colin Rundel. 2019. *Rgeos: Interface to Geometry
Engine - Open Source (’Geos’)*.
<https://CRAN.R-project.org/package=rgeos>.

</div>

<div id="ref-sp2">

Bivand, Roger S., Edzer Pebesma, and Virgilio Gomez-Rubio. 2013.
*Applied Spatial Data Analysis with R, Second Edition*. Springer, NY.
<http://www.asdar-book.org/>.

</div>

<div id="ref-bibtex">

Francois, Romain. 2017. *Bibtex: Bibtex Parser*.
<https://CRAN.R-project.org/package=bibtex>.

</div>

<div id="ref-RColorBrewer">

Neuwirth, Erich. 2014. *RColorBrewer: ColorBrewer Palettes*.
<https://CRAN.R-project.org/package=RColorBrewer>.

</div>

<div id="ref-sp1">

Pebesma, Edzer J., and Roger S. Bivand. 2005. “Classes and Methods for
Spatial Data in R.” *R News* 5 (2): 9–13.
<https://CRAN.R-project.org/doc/Rnews/>.

</div>

<div id="ref-rversion">

R Core Team. 2020. *R: A Language and Environment for Statistical
Computing*. Vienna, Austria: R Foundation for Statistical Computing.
<https://www.R-project.org/>.

</div>

<div id="ref-lattice">

Sarkar, Deepayan. 2008. *Lattice: Multivariate Data Visualization with
R*. New York: Springer. <http://lmdvr.r-forge.r-project.org>.

</div>

<div id="ref-marelac">

Soetaert, Karline, and Thomas Petzoldt. 2018. *Marelac: Tools for
Aquatic Sciences*. <https://CRAN.R-project.org/package=marelac>.

</div>

<div id="ref-png">

Urbanek, Simon. 2013. *Png: Read and Write Png Images*.
<https://CRAN.R-project.org/package=png>.

</div>

<div id="ref-Cairo">

Urbanek, Simon, and Jeffrey Horner. 2019. *Cairo: R Graphics Device
Using Cairo Graphics Library for Creating High-Quality Bitmap (Png,
Jpeg, Tiff), Vector (Pdf, Svg, Postscript) and Display (X11 and Win32)
Output*. <https://CRAN.R-project.org/package=Cairo>.

</div>

<div id="ref-tidyverse">

Wickham, Hadley. 2017. *Tidyverse: Easily Install and Load the
’Tidyverse’*. <https://CRAN.R-project.org/package=tidyverse>.

</div>

<div id="ref-readxl">

Wickham, Hadley, and Jennifer Bryan. 2019. *Readxl: Read Excel Files*.
<https://CRAN.R-project.org/package=readxl>.

</div>

<div id="ref-gtable">

Wickham, Hadley, and Thomas Lin Pedersen. 2019. *Gtable: Arrange ’Grobs’
in Tables*. <https://CRAN.R-project.org/package=gtable>.

</div>

<div id="ref-knitr3">

Xie, Yihui. 2014. “Knitr: A Comprehensive Tool for Reproducible Research
in R.” In *Implementing Reproducible Computational Research*, edited by
Victoria Stodden, Friedrich Leisch, and Roger D. Peng. Chapman;
Hall/CRC. <http://www.crcpress.com/product/isbn/9781466561595>.

</div>

<div id="ref-knitr2">

———. 2015. *Dynamic Documents with R and Knitr*. 2nd ed. Boca Raton,
Florida: Chapman; Hall/CRC. <https://yihui.org/knitr/>.

</div>

<div id="ref-knitr1">

———. 2020. *Knitr: A General-Purpose Package for Dynamic Report
Generation in R*. <https://yihui.org/knitr/>.

</div>

<div id="ref-rmarkdown2">

Xie, Yihui, J.J. Allaire, and Garrett Grolemund. 2018. *R Markdown: The
Definitive Guide*. Boca Raton, Florida: Chapman; Hall/CRC.
<https://bookdown.org/yihui/rmarkdown>.

</div>

</div>

1.  R version 3.6.3 (2020-02-29), with: bibtex 0.4.2, Cairo 1.5-10, grid
    3.6.3, gridExtra 2.3, gtable 0.3.0, knitr 1.28, lattice 0.20-38,
    marelac 2.1.9, png 0.1-7, RColorBrewer 1.1-2, readxl 1.3.1, rgdal
    1.4-6, rgeos 0.5-2, rmarkdown 2.1, sp 1.3-1, tidyverse 1.2.1.
