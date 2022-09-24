# Data-analysis-visualization---Environmental-Protection-Agency
Analyzed with visualization aids to explain various aspects of vehicle induced pollution using R programing. This also includes written description and explanation of my findings. 

Merging and Cleaning

The first objective was to combine the files and stack them as three large files, one for each time period. Run basic EDA and descriptive statistics on some columns and clean any obvious outliers from each time period. Make sure that no more than 1% of the data are removed from within each time period in this process. Write the details of outlier detection and descriptive analysis. 

Analysis

This section is further broken down into two parts:
Part A
There are several numeric columns listed in the datasets. Many of those columns are correlated and contain repetitive information. I used the tools of dimension reduction and condense the number of columns to smaller dimension for each time period separately.  
Use the reduced dimensions to perform “grouping” of similar vehicles. Keep the number of groups between 5 and 8 for each time period. Clearly define groups based on their characteristics by running descriptive analytics on each group, then compare the groups for the three time periods and point out any vehicles that jumped from one group to the other over time. Also explained what that jump meant 


Part B: 
This part is about predictive modeling where I tried several modeling techniques separately for each time period. I then compared the results from the best models for each time period. 
The response variable for this problem is mileage per gallon (columns name: RND_ADJ_FE). I created the best predictive model predicting the mileage per gallon for each time period. I then compared those models for the predictors and accuracy (R2, MSE etc.) and described the results. 

Visualization 

Created several visual depictions of the analysis in both descriptive statistics and modeling parts of the report.
