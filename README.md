## Survival Analysis - Lung cancer : Deploy a statistical analysis of a dataset related to the lung cancer

### Table of Contents

1. [Project Purpose](#projet)
2. [Installation](#install)
3. [Files Descriptions](#files)
4. [Authors and motivations](#authors)



### What is the project ? <a name="projet"></a>

The purpose of this project is to perform a statistical analysis of a dataset 
related to the lung cancer. 

The dataset provided is the NCCTG lung cancer data set. 
The North Central Cancer Treatment Group (NCCTG) data set records the survival of patients with advanced lung cancer. 
More information on the website : https://dataset.lixoft.com/data-set-examples/ncctg-lung-cancer-data-set/

### Installation <a name="install"></a>

To explore this project download the R file 'Survival Analysis Lung Cancer.Rmd' and open it in your favourite IDE or R studio.
The dataset is included in the R package called 'survival'.

The R packages to install are :
       survival
       survminer


### Files Descriptions <a name="files"></a>

Dataset 'lung' : 
-   inst: Institution code
-   time: Survival time in days
-   status: censoring status 1=censored, 2=dead
-   age: Age in years
-   sex: Male=1 Female=2
-   ph.ecog: ECOG performance score (from 0=active to 5=dead)
-   ph.karno: Karnofsky performance score (from 0=dead to 100=normal)
-   pat.karno: Karnofsky performance score as rated by patient
-   meal.cal: Calories consumed at meals
-   wt.loss: Weight loss in last six months


### Authors & Motivations <a name="authors"></a>

This project was carried out as part of the preparation for an MSC in Data Science & AI at the Data ScienceTech Institute.

The members of the project group are :
 - Saïd HAMDI - Data science
 - Guillaume NONY - Data science

