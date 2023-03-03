Lead scoring case study
Below are steps we will follow to carry put this activity:
- Importing the necessary libraries:
The first step is to import the necessary libraries required to carry
out various operations, it includes libraries like pandas, numpy,
sklearn, seaborn and matplotlib. However it is not just limited to
these libraries and one can use their own set of libraries to build
and evaluate the model.
- Second step is to perform basic Exploratory data analysis:
Once libs are imported we will now try to understand the data.
We will understand the span of the data, analyze the outliers and
treat missing values. This will give us a wholistic view of the data
we are dealing with.

- Data cleaning and Transformation:
We will now remove the insignificant columns i.e. the columns
that are not adding much value to our model or seems to have
very little impact on the overall output. Now in some columns
some invalid values were also there, like select. We will now
handle such values and clean the data. We will also remove those
columns where missing values were more than 3000, we can
choose any number which seems reasonable. For example, we
could also delete columns where missing values were more than
2500 or so. For remaining columns, we will handle the missing
values and either replace that with mean or median values
depending upon the type of column.
Another important step was to convert the categorical values into
numerical values for the operations of our model. Creating bins
for our outliers and removing the redundant columns.

- Data preparation for the model:
Now, we have already treated the data, hence the next step will
be to prepare the data for our training model. We will split the
data set in to train and test and we used 70% and 30% split for
that as this is the industry standard. But having said that, it is not
mandatory to rely on this percent only and we can also go for
other bifurcations such as 75-25 or even 80-20, that is also fine.
We drew the heatmap and found out about correlations and
based on this newly available information dropped couple of more
columns.

- Model building and evaluation:
Now it’s time to build the model. We built the model and
calculated the evaluation score. We also find out the specificity
and sensitivity. We also calculated the accuracy score for our
model.

- Conclusion: recall sensitivity in acceptable range. Few most important
columns are last notable activity, current occupation and lead origin.
