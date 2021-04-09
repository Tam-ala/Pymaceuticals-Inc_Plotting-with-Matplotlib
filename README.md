# Pymaceuticals Inc.: Plotting with Matplotlib

## Background

While my data companions rushed off to jobs in finance and government, I remained adamant that science was the way for you. Staying true to my mission, I've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## How To Use
### One Way
To access the materials used, go to the [Pymaceuticals](https://github.com/Tam-ala/Pymaceuticals-Inc_Plotting-with-Matplotlib/tree/master/Pymaceuticals) folder.

The csv files used can be accessed in the [data](https://github.com/Tam-ala/Pymaceuticals-Inc_Plotting-with-Matplotlib/tree/master/Pymaceuticals/data) folder.

The notebook is called [Pymaceuticals](https://github.com/Tam-ala/Pymaceuticals-Inc_Plotting-with-Matplotlib/blob/master/Pymaceuticals/Pymaceuticals_update.ipynb).

### Second Way
This way will allow for data manipulation.
* First clone the folder
* In the terminal, type: git clone <folder>. The folder should appear on the Desktop
* Go to the folder to open the terminal from this folder by right-click and selecting the terminal
* Assuming that an environment is made in terminal, type: conda activate <environment-name>
* And assuming that jupyter notebook is installed, type: jupyter notebook
* Jupyter Notebook should open up in the browser automatically to the Pymaceuticals_update notebook file.

## Tasks

My tasks were to do the following:

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of data points for each treatment regimen.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Generate a line plot of time point versus tumor volume for **mouse number l509** treated with Capomulin.

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

## Observations of Results
Observation 1
Based off of the mice treatment with Capomulin, there seems to be a positive correlation of 0.84 between mouse weight and tumor volume.

Observation 2
The mouse distribution for each drug regimen was uneven. The maximum number of mice for Capomulin was 230 and the minimum was 161 for the Propriva regimen. The study might be more concrete if the number of mice was the same for all regimens.

Observation 3
Since the mouse count was higher and the median tumor volume for the mice were the lowest for Capomulin(41.6mm3) and Ramicane(40.7mm3) compared to the mice on the other regimens, did it hold more promise of these drugs' success?

Observation 4
Mouse-l509's seemed to react positively with Capomulin and the tumor volume decreased over time. However, there's a sharp increase after the 35th timepoint and the end of the study at 45th timepoint. What changed during that time? And was it the same for other mice that were on this treatment?

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
