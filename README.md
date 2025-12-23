# Multimodal Biomarkers for Sudden Cardiac Death

This repository reproduces **Figure 3** from:

> *A review of multimodal biomarkers for the diagnosis of sudden cardiac death*  
> Manuscript under submission

The analysis is implemented in **R Markdown** and uses **`renv`** to ensure full computational reproducibility.

---


## Requirements

- R ≥ 4.2 (recommended)
- RStudio (recommended but not required)
- Internet access (for initial package installation only)

---

## Quick start (TL;DR)

```r
install.packages("renv")
renv::restore()
rmarkdown::render("src/Figure3_code.Rmd")
```

---

## Reproducible setup using `renv`

### 1. Clone the repository

```bash
git clone https://github.com/CompBio-Lab/scd_multimodal_litreview.git
cd scd_multimodal_litreview
```

### 2. Open the project

Open `scd.Rproj` in RStudio or set the working directory manually.

### 3. Restore the R environment

```r
install.packages("renv")
renv::restore()
```

---

## Running the analysis

```r
rmarkdown::render("src/Figure3_code.Rmd")
```

---

## Outputs

- Figure3a_roc.png
- Figure3b_boxplots.png
- Figure3c_network.png
- scd_network.pdf

---

## Contact

**Amrit Singh**  
amrit.singh@ubc.ca
University of British Columbia
