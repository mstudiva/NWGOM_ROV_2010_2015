NWGOM ROV transect analyses
==========================================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXX)

### Ryan Eckert -- <ryan.j.eckert@gmail.com>

### version: March 27, 2020

------------------------------------------------------------------------
This repository contains scripts and data associated with the
publication: 

**XXX**

------------------------------------------------------------------------

#### Protocols and walkthroughs accompanying this manuscript:

1.  [Statistical analyses of ROV transect photos](https://ryaneckert.github.io/NWGOM_ROV_2010_2015/)

------------------------------------------------------------------------

#### Repsitory contents:

- code
    - *code.Rproj* -- R project file
    - *nwgomAnalyses.Rmd* -- NWGOM ROV transect analyses Rmarkdown document

- data
  - raw
    - *2010-2015_transectMetaData.xlsx* -- Metadata associated with ROV transects
    - *rawBenthicCounts.xlsx* -- Raw CPCe count data from ROV transects
    - *rawDensity.xlsx* -- Raw density of Cnidarians by transect
    - *scleractinianCounts.csv* -- Raw counts of Scleractinian corals by transect to species
  - *coralFamilyCounts.csv* -- Counts of coral Family by transect
  - *coralFamilyDensityBank.csv* -- Density of coral Family by bank
  - *coralFamilyPercentCoverBank.csv* -- Percent cover of coral Family by bank
  - *nwgomMajorPerc.csv* -- Percent cover of major taxa by transect
  - *nwgomMinorDensity.csv* -- Density of corals by transect
  - *nwgomMinorPerc.csv* -- Percent cover of minor taxa by transect
  - *nwgomMjrPercBank.csv* --  Percent cover of major taxa by bank
  - *scleractinianSppCounts.csv* -- Counts of Scleractinian species by bank

- figures
  - *Figure1.eps* -- Figure of transect locations (.eps)
  - *Figure1.png* -- Figure of transect locations (.png)
  - *allNMDS.eps* -- Figure of non-metric multidimensional scaling biplots transects for major/minor taxa percent cover and coral density
  - *barPlots.eps* -- Figure of stacked barplots for major taxa percent cover, coral family percent cover, and coral family density by bank
  - *percentDends.eps* -- Figure of denrograms of transects for major/minor taxa percent cover and coral density
  - *sclerSppPlots.tiff* -- Figure of coral and Scleractinian alpha diversity metrics

- primerFiles
  - *nwgomMajorPercPrimer.xlsx* -- Major taxa percent cover data fomatted for PRIMER7
  - *nwgomMinorDensPrimer.xlsx* -- Coral density data fomatted for PRIMER7
  - *nwgomMinorPercPrimer.xlsx* -- Minor taxa percent cover data fomatted for PRIMER7
  - *nwgom_2010-2015.pwk* -- PRIMER7 workbook

- tables
  - *alphaDiversityResults.xlsx* -- Results for Kruskal-Wallis and Conover-Iman tests on alpha diversity metrics
  - *coralPercentCover.xlsx* -- Breakdown of coral percent cover by taxa by bank
  - *permanovaResults.xlsx* -- Results of PERMANOVA and pairwise PERMANOVA on percent cover and coral density by bank
  - *rovSummary.xlsx* -- Summary of ROV transects by bank
  - *simperResults.xlsx* -- Results of SIMPER analysis for percent cover and coral density by bank
  
- *README.md* -- Repository readme document
- *index.html* -- Webpage version of code and analysis walkthrough
