## Analysis of The Pymaceuticals 
---------------------------------

### Three conclusions that can be drawn from the analysis are:
1. From the bar charts of "Total timepoint for each drug" it can be concluded that the drugs Capomulin has 
the most number of total timepoints. It can be said that it take the most time to effect the tumors or 
in other words these are comparatively slower drugs, while there might be other factors contributing to this by just 
the bar charts this can be an obvious conclusion. The another drug with similar reaction time is Ramicane.

2. From the box plot for the four drugs Capomulin, Ramicane, Infubinol, and Ceftamin, we can see that none of the drugs
has any outliers except Infubinol. The factors effecting that can be only found out by further analysis but the concluiosn
we can draw from that is that Infubinol has a very positive effect on treatment of tumor hence there is an outlier in lower region.
Also none of the drugs has shown an outlier in the upper region indicating that drugs seems to have a negative effect on the tumors.

3. From liner regression model for average tumor volume vs mouse weight we can conclude that there is linear correlation between the 
mouse weight and Average tumor volume. The average tumor volume is seems to increase with mouse weight.So higher the weight higher the tumor volume.


## Pymaceuticals
-------------------

![Laboratory](https://user-images.githubusercontent.com/85182090/126898039-08144b2a-7c45-4cd5-b90a-c98b7d897ad3.jpg)

 Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company,I havee been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

Tasks to do :

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Use the cleaned data for the remaining steps.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

    **NOTE:** These plots should look identical.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

    **NOTE:** These plots should look identical.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

  **Hint**: All four box plots should be within the same figure. Use this [Matplotlib documentation page](https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py) for help with changing the style of the outliers.

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.


  

