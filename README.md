# matplotlib-challenge

In this challenge, we look at a dataset consisting of observations of mice being treated for tumors with one of 9 experimental drug regimens (or a placebo). We begin by eliminating some ambiguous data for one mouse, then producing a summary statistics table for each of the drug regimens.

Next we take a look at the sample size of each drug regimen, represented by bar charts showing the total number of measurements taken on mice in each treatment group. A bar chart is generated using python's method as well as matplotlib.

Next the population of mice by gender is shown using a pie chart. With 123 female mice and 125 male mice in the study, the population is a representative sample.
To look more closely at the spread of the data for 4 promising regimens, quartile bounds and outliers are calculated and a box plot is generated. The quartile/outlier calculation is fairly involved, whereas using pandas' boxplot function on a grouped dataframe made the chart generation very simple.

Next we confirm that tumor volume does decrease over time for a single mouse, chosen at random, on Capomulin by generating a simple line plot of tumor volume vs time.

Finally, we generate a scatter plot of tumor volume vs mouse weight for mice on Capomulin, and observe there is a strong direct correlation between those two factors, as shown by the Pearson coefficient close to 1. The linear regression model is also calculated using the linregress() function and plotted.

Conclusions drawn from this data is given at the top of the Jupyter notebook.
