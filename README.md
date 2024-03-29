# EDF-6436

## Fall 2022 - EDF 6436: Theory of Measurement 

Welcome everyone! This is a repository for the lab materials provided in EDF 6938 - SPRING 2023 (Previously EDF 6436)


You can copy and past this following code in R to run the lab tutorial (You only need to run this part once!) 
```r
install.packages(c('remotes', 'shiny'))
```
Next 
```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
remotes::install_github("rstudio/learnr", force=TRUE)
```

### Syllabus (Tentative)
For week 1: Basic Statistics review for EDF 6436 

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week1", package = "LabR6436")
```

For week 2: Test Construction and Test Scores 

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week2", package = "LabR6436")
```

For week 4: CTT Item Analysis 

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week4", package = "LabR6436")
```
For week 5: Reliability 

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week5", package = "LabR6436")
```
For week 7: Validity

```r
#install.packages(c('stringr','Hmisc', 'reshape2', 'surveydata', 'dplyr'))
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week7", package = "LabR6436")
```

For week 8: EFA

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week8", package = "LabR6436")
```

For week 11: CFA

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week11", package = "LabR6436")
```

For week 13-14: IRT

```r
remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week14", package = "LabR6436")
```


For week 15: G-Theory 

```r
install.packages("devtools")
devtools::install_github("cddesja/hemp") # if you have trouble downloading 'hemp'

remotes::install_github("jinnieshinufl/EDF-6436/lab/LabR6436", build_vignettess = TRUE)
learnr::run_tutorial("week15", package = "LabR6436")
```

