---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

I build open-source packages in Python and R to advance researcher's understandings of single cell biology and multi-omic data integration.
# CORTADO

![github_flowchart](https://github.com/user-attachments/assets/8fec5bc5-fd99-47cb-a566-cbf1c69e1370)

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white) ![License](https://img.shields.io/badge/License-MIT-green) ![Docs](https://img.shields.io/badge/docs-passing-brightgreen) 

CORTADO is a PyPi package for robust marker gene inference. For a full description of the method as well as the user guide, please see the GitHub repository. 


### Install CORTADO
 
```python
pip install cortado-marker
import cortado_marker as cortado
```

# RWmisc

[![R build status](https://github.com/jayrobwilliams/RWmisc/workflows/R-CMD-check/badge.svg)](https://github.com/jayrobwilliams/RWmisc/actions)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/RWmisc)](https://CRAN.R-project.org/package=RWmisc)
[![codecov](https://codecov.io/gh/jayrobwilliams/RWmisc/branch/master/graph/badge.svg)](https://codecov.io/gh/jayrobwilliams/RWmisc)

I've collected convenience functions that I've written to address issues I frequently confront in my work into a personal R package called [RWmisc](https://CRAN.R-project.org/package=RWmisc). It includes functions for:

- Managing multiple different projections for cross-national spatial data
- Converting latitude-longitude data in archaic forms (degrees, minutes, seconds)
- Correcting for overlapping polygons when aggregating raster data to polygons
- My custom minimal ggplot2 theme

![](/images/software/spatial_weighting.png)

To install the latest release on CRAN:

```r
install.packages("RWmisc")
```

The latest [development version](https://github.com/jayrobwilliams/RWmisc) on GitHub can be installed with:

```r
library(remotes)
install_github("jayrobwilliams/RWmisc")
```

# Other resources

I also have a number of other software resources focused on making computation and academic life easier:

- [The template](https://github.com/jayrobwilliams/JobMarket) I use for my academic job market materials
    - Fill in school/position information in one file and it populates to all statements
    - Generate summary statistics from teaching evaluations and integrate into statements
    - Combine multiple teaching evaluations into a single portfolio document
    - Do all of this programmatically with GNU Make!
- [The template](https://github.com/jayrobwilliams/UNC-Dissertation-Template) I used for my dissertation
    - This satisfied the formatting requirements at UNC in 2019
    - Some tweaking likely required to use at another institution or in the future
- [Scripts](https://github.com/jayrobwilliams/Teaching) that I use to save time on various teaching-related tasks like grading
- [Functions](https://github.com/jayrobwilliams/ComputerVision) for extracting still frames from videos and information from images in Python using OpenCV
- [Compiling OpenCV](/files/html/OpenCV_Install.html) from source for Anaconda virtual environments instead of Homebrew ones or system Python installations
