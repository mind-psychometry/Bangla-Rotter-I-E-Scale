# Bangla-Rotter's I-E Scale

This is the repository for the reproducible manuscript of **"Psychometric evaluation of the Bangla-Translated Rotter’s Internal-External Scale through classical test theory and item response theory"**

## In this repository you will find:

### File


- **README.md**: This file contains necessary information of the project
- **LICENSE**
- **Rotterpaper.Rmd**: A reproducible manuscript with all analysis code.
- **Wrotter.rds**: De-identified raw data used in this study.
- **Bangla-Rotter-I-E-Scale-Manuscript.Rproj**: This is the R project file.
- **Rotter-References.bib**: A bibTeX file with all references used in the manuscript.
- **vancouver.csl**: A csl styler to  format the references.
-  **renv.lock**: Lockfile for renv package initiation.

### Folder

- **Figures/300**: A folder with all figures used in the Manuscript.
- **renv** : This folder contains all necessary information of the relevant R-packages used in the manuscript. This folder will help you get all required R-packages in your environment. Just use `renv:restore` in your consol to install all required packages automatically.

# Workflow:

- Open **Bangla-Rotter-I-E-Scale-Manuscript.Rproj** using RStudio.

- In the Rstudio console open **Rotterpaper.Rmd**.

- The second chunk in the `Rotterpaper.Rmd*` is deactivated. Run this manually for the very first time you are knitting to install all packages.
- Alternatively, you can run `renv::restore()` in your consol to automatically install all required packages.
- Once all the packages are installed try knitting in PDF.

<a href="https://zenodo.org/badge/latestdoi/464843878"><img src="https://zenodo.org/badge/464843878.svg" alt="DOI"></a>

