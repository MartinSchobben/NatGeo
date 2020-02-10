To recreate the article: A nutrient-driven tipping point catalysed marine anoxia during the end-Permian mass extinction, published in Nature Geoscience, run the R Markdown file (.Rmd) with knitr (1.27) (Xie 2014, 2015, 2018) on the programming platform R (R Core Team 2019).  Instructions on the installation and the usage of Rmarkdown for Rstudio can be found on the website: https://rmarkdown.rstudio.com/. After unzipping the file, the Rmd file can be found under the directory: report. Several additional packages are required to recreate data processing, statistics and visualization of the geochemical datasets, including: tidyverse 1.2.1 (Wickham 2017), gtable 0.3.0 (Wickham & Pedersen 2019), png 0.1-7 (Urbanek 2013), gridExtra 2.3 (Auguie 2017), readxl 1.3.1 (Wickham & Bryan 2019), bibtex 0.4.2 (Francois 2017), sp 1.3-1 (Bivand et al. 2013; Pebesma & Bivand 2005), rgdal 1.4-6 (Bivand et al. 2019), rgeos 0.5-2 (Bivand & Rundel 2019), lattice 0.20-38 (Sarkar 2008), and grid 3.6.1. The library marelac 2.1.9 (Soetaert & Petzold 2018) was used for chemical data transformations. Complete the pathway to approriate directory on lines 6, 7 and 78 of Schobbenetal_main.Rmd and lines 6, 7 and 82 of Schobbenetal_SI.Rmd before rendering the files.

Auguie, B. GridExtra: Miscellaneous functions for "grid" graphics. (2017).
Bivand, R., Keitt, T. & Rowlingson, B. Rgdal: Bindings for the ’geospatial’ data abstraction library. (2019).
Bivand, R. S., Pebesma, E. & Gomez-Rubio, V. Applied spatial data analysis with R, second edition. (Springer, NY, 2013).
Bivand, R. & Rundel, C. Rgeos: Interface to geometry engine - open source (’geos’). (2019).
Francois, R. bibtex: Bibtex Parser. (2017).
Pebesma, E. J. & Bivand, R. S. Classes and methods for spatial data in R. R News 5, 9–13 (2005).
R Core Team. R: A language and environment for statistical computing. (R Foundation for Statistical Computing, 2019).
Sarkar, D. Lattice: Multivariate data visualization with r. (Springer, 2008).
Soetaert, K. & Petzoldt, T. Marelac: Tools for aquatic sciences. (2018).
Urbanek, S. Png: Read and write png images. (2013).
Wickham, H. & Bryan, J. Readxl: Read excel files. (2019).
Wickham, H. & Pedersen, T. L. Gtable: Arrange ’grobs’ in tables. (2019).

