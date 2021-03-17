# hw5-plotting-pymaceuticals

## Project Summary | Grade: A

The objective of this project was to use the given data about mice in clinical trials of various cancer drugs to practice plotting and draw some inferences and observations from the final product. 

After cleaning the data for potential duplicates, I created a topline statistical summary for the volume of tumors, including mean, median, standard deviation and error. I then created a bar graph to count how many times a measurment was taken for each drug regimen. I also created a pie chart that breaksdown the mice trial subjects by sex. 

For the regimens of Capomulin, Ramicane, Infubinol, and Ceftamin, I performed a statistical analysis on the final tumor volume. After narrowing to the data I needed, I used the 1.5 * IQR method to determine any statistical outliers for each drug. I then plotted each drug as a box and whisker plot, which shows the mean, quartiles and potential outliers of the data set. 

The next task was selecting one mouse on the Capomulin regimen (I chose Mouse x401) and graphed the tumor volume at each measurement.

Lastly, I created a scatterplot to show the relationship between weight and average tumor volume for the Capomulin regimen. Additionally, I performed an analysis of the correlation between the two variables and found the equation of the regression line. 

Some observations about the data are listed below. You can also find all this information at the top of the workbook.

##### Observation 1

Based on the topline summary (see Summary Statistics below), the drug regimens Capomulin and Ramicane have significantly lower average tumor volumes compared the placebo and other regimens. Not only do these two regimens have the lowest mean and median average tumor volume-- 40.68 and 40.22 mm^3 average respecitively-- they also have the lowest standard deviation. This indicates that the drugs work more consistently across the population, as opposed to working on some mice and not on others. We can infer that these two drugs are the most promising for future trials

##### Observation 2
Also based on the topline summary, it is clear that some drugs are not effective at reducing tumor volume given that the mean and median are close to the plecebo volume of 54.03 mm^3. Naftisol, Stelasyn, and Ketapril seem to have no effect (average tumor volume is actually higher for the Ketapril regimen at 55.24 mm^3). From this, we can infer that these regimens require alteration and/or more study before continuing future trials. 

##### Observation 3
For the mice on the Capomulin regimen, average tumor volume is highly correlated to the individual mouse's weight. Given a correlation coefficient of greater than 0.8, that indicates a strong relationship between these two factors. In the future, I would like to examine this relationship across all regimens to see if the trend holds. If it does, that could be an area of future study to determine if weight might play a role in the progression of tumors. 
