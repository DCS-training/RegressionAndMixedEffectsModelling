# Regression And Mixed Effects Modelling

This course will introduce you to regression and linear mixed-effects models (LMMs). It will help to develop your theoretical understanding and practical skills for running such models in R.

A regression is a statistical technique that relates a dependent variable to one or more independent variables. A regression model can show whether changes observed in the dependent variable are associated with changes in one or more of the explanatory variables.

Linear mixed-effects models are powerful and flexible statistical tools that help us understand the world. This is particularly useful in language sciences when our aim is to investigate the influence of one or more predictor factors (e.g., time spent on the Internet per week) on a particular linguistic phenomenon that we are interested in (AKA. an outcome variable; e.g., people’s tendency to use internet slang in face-to-face communication). In these cases, we often need to account for the individual differences among people who take part in the study. Linear mixed models allow us to do this and more!

This course includes three 2-hour sessions. Session 1 is mainly conceptual. We will first recall linear regressions and discuss how linear mixed-effects regressions differ from it and why we want to use mixed-effects models. Sessions 2 and 3 are more practical in that we will go through a real dataset from a sociolinguistic study to demonstrate how to run LMMs in R using the lme4 package (Bates, Mächler, Bolker, and Walker, 2015). You will also have the opportunity to try it out yourself by analysing a made-up psycholinguistic dataset using LMMs in R.

By the end of the course, you will understand the following concepts of LMMs and know how to construct LMMs in R.  

- Model structure (fixed and random effects)
- Coefficients (intercepts and slopes)
- Model fit
- Model Selection
- Model Assumptions

This course is an advanced training course. It requires a basic understanding of R and statistical analyses. Some general knowledge of regression is not mandatory but will help you follow the content of this course. The lme4 package should be downloaded and installed prior to participating in this workshop

# Getting Set-up
We are fine-tuning the course materials now, thus want to run a quick pre-course survey in order to best accommodate your needs. 
Can you please complete this (survey)[https://edinburgh.eu.qualtrics.com/jfe/form/SV_2gi3h3QXTBFHEAm]

# Installing R and Packages needed 
## Installing R and R Studio
### For R On Noteable

1. Go to https://noteable.edina.ac.uk/login
2. Login with your EASE credentials
3. Select RStudio as a personal notebook server and press start
4. Go to File > New Project> Version Control > Git
5. Copy and Paste this repository URL [https://github.com/DCS-training/RegressionAndMixedEffectsModelling](https://github.com/DCS-training/RegressionAndMixedEffectsModelling) as the Repository URL (The Project directory name will filled in automatically but you can change it if you want your folder in Notable to have a different name).
6. Decide where to locate the folder. By default, it will locate it in your home directory
7. Press Create Project
Congratulations you have now pulled the content of the repository on your Notable server space.

### Install it locally
1. Go to (https://www.r-project.org/)[https://www.r-project.org/]
2. Go to the download link
3. Choose your CRAN mirror nearer to your location (either Bristol or Imperial College London)
4. Download the correspondent version depending if you are using Windows Mac or Linux
  4a. For Windows click on install R for the first time. Then download R for Windows and follow the installation widget. If you get stuck follow this (video tutorial)[https://www.youtube.com/watch?v=GAGUDL-4aVw]
  4b. Form Mac Download the most recent pkg file and follow the installation widget. If you get stuck follow this (video tutorial)[https://www.youtube.com/watch?v=EmZqlcKkJMM]
5. Once R is installed you can install R studio (R interface)
6. Go to (www.rstudio.com)[www.rstudio.com]
7. Go in download
8. Download the correspondent version depending on your Operating system and install it. If you get stuck check the videos linked above. 

## Install the libraries 
```
library("tidyverse") #for cleaning and sorting out data
library("lme4") #for fitting linear mixed-effects models (LMMs)
library("effects") #for creating tables and graphics that illustrate effects in linear models
library("sjPlot") #for plotting models
library("interactions") #for plotting interaction effects``` 

# What you are going to find in this repo
Once ready, you are going to find 

-  .ppt presentations used during the course
-  example code 


# Author
 Fang Jackson-Yang

