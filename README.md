
This was a challenging but enjoyable assignment. It was empowering to take all this data and to transform it into simple and clear tables and figures for end users to analyze. 
 
I started with importing dependencies as well as the two csv files provided and converting them and merging them into one DataFrame. I then cleaned up the data by dropping a duplicate mouse by its ID number and creating a clean DataFrame without the duplicate.

Next up, statistics! I generated a summary statistics table for all drugs which showed the mean, median, variance, standard deviation, and the standard error of the mean by using groupby, summary statistical methods, and the aggregation method. I created a DataFrame to hold this data. 

Then came the charts and figures. First, I created two bar charts (one with Pandas and the other with PyPlot) that showed the number of observed mousepoints for each drug regimen. I then generated two pie charts (one with Pandas and the other with PyPlot) that showed the distribution of male vs female mice in the study.

I then calculated the final tumor volume at the greatest timepoint for mice taking Capomulin, Ramicane, Infubinol, and Ceftamin. This dataFrame was merged with the original clean DataFrame, and I calculated the IQR for each of these drugs and determined whether or not there were any potential outliers (only 1 in Infubinol). This was displayed in a box and whisker plot. 

I then created a line graph of tumor volume vs. time point for a single mouse treated with Capomulin, and then a scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen. Finally, I calculated the correlation coefficient and generated a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen.
