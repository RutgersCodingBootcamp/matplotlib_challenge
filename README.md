# matplotlib_challenge

#The Power of Plots- Pymaceutical

##How does it work?

this code will take two sets of data, Mouse meta data and Study results, merge them and clean up the duplicated data. then it will do the following analysis:

* Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generates a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculates the final tumor volume of each mouse across four regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculates the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generates a box and whisker plot of the final tumor volume for all four treatment regimens.

* For a selected mouse that was treated with Capomulin it generates a line plot of tumor volume vs. time point for that mouse.

* Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.