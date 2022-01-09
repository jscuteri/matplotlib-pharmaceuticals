# Matplotlib – Pharmaceutical Analysis

**Background**

“ABC Pharmaceuticals” specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of ABC Pharmaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 
I have generated all the tables and figures needed for the technical report of the study as well as a top-level summary of the study results.

**Analysis Overview**

**Steps of Analysis**

•	Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

•	Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

•	Generate a bar plot that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

•	Generate a pie plot that shows the distribution of female or male mice in the study.

•	Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

•	Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

•	Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

•	Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

•	Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

•	Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
