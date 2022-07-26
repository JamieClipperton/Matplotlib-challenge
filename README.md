# Matplotlib-challenge - The Power of Plots 

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Instructions

Your tasks are to do the following:

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Cleaned Data Frame: 

![image](https://user-images.githubusercontent.com/101610081/181093358-f4cede63-c243-444c-95f1-1131d6d64c03.png)


* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![image](https://user-images.githubusercontent.com/101610081/181093504-82dded1c-f7fd-405f-8bd7-cb8271256193.png)


* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

![image](https://user-images.githubusercontent.com/101610081/181093603-1d9d5de5-27a7-4999-920d-6fabf62028cc.png)

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

![image](https://user-images.githubusercontent.com/101610081/181093746-73d4e8eb-7b05-4dcd-86ff-5270c7c31c2a.png)

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

![image](https://user-images.githubusercontent.com/101610081/181093899-6b63cf5b-cf61-4096-a37b-983d4bb9e901.png)

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![image](https://user-images.githubusercontent.com/101610081/181093955-5ab2142c-79e1-44a2-b0c4-a28b6db4492a.png)

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

![image](https://user-images.githubusercontent.com/101610081/181094083-42edf04d-1007-4393-84c4-98becb249aab.png)

* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

![image](https://user-images.githubusercontent.com/101610081/181094187-99a4608e-068b-4f5b-815b-760fbec83947.png)

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

![image](https://user-images.githubusercontent.com/101610081/181094294-45a62ddd-cb42-4350-89a8-5417e75faaff.png)

## Observations

* Drugs Capomulin and Ramicane have the best results for decreasing tumor volume. 
* Researchers used almost same amount of males as female mices for experiment. 
* The Placebo group was tested on about the same amount of mice as drug groups for Ceftamin and Stelasyn. 



