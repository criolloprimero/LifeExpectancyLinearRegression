# LifeExpectancyLinearRegression

Data was collected by the Global Health Observatory under the world health organization(WHO) and economic data from the United Nations (UN) of 183 countries. Data should be accurate and applicable.

##### data source

A few notes were left by the creators​ https://www.kaggle.com/kumarajarshi/life-expectancy-who
dataset Creators: Kumar Rajarshi, Deeksha Russell and Duan Wang

##### data notes
1. The data was collected from 2000-2015, within that time frame global health has been increasing overall for most countries except for a minúte few. ​

2. If data was missing for a majority of fields it was removed.  ​

3. Small countries like Cape Verde was removed.​

4. The total before data processing was 22 columns and 2938 rows​

5. Main categories for the group was Immunization related factors, mortality factors, economical factors and social factors.​

## significant features of life LifeExpectancyLinearRegression

-Adult Mortality
-infant deaths
-percentage expenditure
-Measles
-BMI
-under five deaths
-Polio
-HIVAIDS
-thinness119years
-thinness59years
-Income composition of resources
-Schooling
-whether a nation is developed or not
-Intersection of BMIandPolio
-Intersection of thinness119yearsandthinness59years
-Intersection of Totalexpenditureandunderfivedeaths
-Intersection of percentageexpenditureandthinness59years
-Intersection of Polioandunderfivedeaths
-Intersection of MeaslesandPolio
-Intersection of BMIandTotalexpenditure
-Intersection of Totalexpenditureandpercentageexpenditure


## conclusion

so we can see here that these values are significant determinants of life expectancy. This analysis was a bit difficult since we were battling for very small increases in R square values.  

Most can be explained by the large variance of the data and some of the subgrouping amongst the data.  a little disappointing but there are few more methods we could use in future analysis to see if we can see out RMSE decrease and R square increase.

## interpreting Coefficients that are useful and impact the model.

###### We should note that the logarithmic variables should be described as

For every 1 percent increase in under 5 deaths we should see a .07 unit change in Life expectancy.  ​

###### and for the dummy and interaction features

For every unit change in schooling we should see 1.9 unit change in the value of life expectancy

###### Future.

we can improve this model by taking a look at:
1. Polynomial regression​

2. Better pruning of outliers, looking at internal structure of Independent  variables​

3. Better recursive functions​

4. Taking a better look at multicollinear variables​

5. The groupings within low-income countries that stood out. Clear divide
