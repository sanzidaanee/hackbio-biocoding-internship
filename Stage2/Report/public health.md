
# Public Health: Analyzing the NHANES Dataset

This repository contains a Python notebook (`Stage_2.ipynb`) that analyzes the relationship between the data of participants in the dataset
# Link

## Code link: https://github.com/sanzidaanee/hackbio-biocoding-internship/blob/main/Stage2/Code/public%20health.ipynb

## Video link:  https://www.linkedin.com/posts/bezaleel-akinbami-33a812168_as-part-of-the-hackbio-internship-stage-activity-7299905354031632384-NRBQ?utm_source=share&utm_medium=member_android&rcm=ACoAACf8wF4BNyxqmoNClmfsIz-pzwUKKhCvBUs 


## Task Description

The task involved analyzing the dataset:

* **NHANES Dataset:** Contains data on health and nutritional status of adults and children in the US

The goal was to:

** Tasks**: 

** Process all NA (either by deleting or by converting to zero)

** Visualize the distribution of BMI, Weight, Weight in pounds (weight 2.2) and Age with an histogram.

** What's the mean 60-second pulse rate for all participants in the data?
** What's the range of values for diastolic blood pressure In all participants? 

** What's the variance and standard devlation for Income among all participants? 

** Visualize the relationship between weight and height? Color by:
   * Gender
   * Diabetes
   * smoking status 

** Conduct t-test between the following variables and make conclusions on the relationship between them based on P-Value 
   * Age and Gender
   * BMI and Dlabetes
   * Alcohol Year and Relationship Status


## Files

* `Stage_2.ipynb`: Jupyter Notebook containing the Python code for the analysis.
* `NHANES Dataset`:https://raw.githubusercontent.com/HackBio-Internship/public_datasets/main/R/nhanes.csv


## Dependencies

The following Python libraries are required to run the notebook:

* `pandas`
* `matplotlib`
* 'seaborn'
  

You can install these libraries using pip

## Results
The notebook provides:

* Dropped the NA values.
* Visualized the distribution of BMI, Weight, Weight in punds and age on a Histogram.
* Calculated the mean of the 60-second pulse rate.
* Displayed the min and max Diastolic blood pressure
* Calculated the varianve and standard deviation of the income of participants
* Visualized the relationship between weight and height, and color coded by gender, diabetes, and smoking status on scatterplots
* Conducted a t-test to find out the relationship between age and gender, BMI and diabetes, alcohol year and relationship status based on the P-value

## Author

* Bezaleel Akinbami(@Bez) 

## Acknowledgements
* CDC for the dataset.
* My team members
* HackBio for the task.
