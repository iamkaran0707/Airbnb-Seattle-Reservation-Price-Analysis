Below are some of the steps that I followed:
1. Load all the datsets: listings, calendar and review. We will mainly be working with listings and calendar datasets, as they contain the data.
2. Now, take the listings dataset and check the %age of null values present in them by making a bar plot. Features that have more than 40% of values as missing will be deleted from the datasets
3. Next is to drop all the features from the dataset-- listing. We will remove around 40 features, these are mostly the features like url, or the featues that have mostly 1 unique values or the featues that have similar features present
4. Now we will create the cleaning function for listings datasets. Here we will clean some of the features that contain %,$ sign or extract the months, dates and year from the date. We will also split the features that contains list,dictionaries in them and will conver them to separate features
5. After we complete the cleaning function of listing, we will similarly create the cleaning function for calendar dataset.
6. Here also we will clean the date and extract months, date and year and also remove the $ from the price feature.
7. Once we will clean both the datasets, then we will merge both the datasets and fill the missing values
8. For the categorical features we will replace the missing values with their mode
9. For the numerical featues we will replace the missing values with there mean values {Note: For the features that are skewed,there we will replace the missing values with the median values, else we generally replace the missing values with mean values }
10. Now,we will answer some of the questions related to this dataset:
11. ---> Which is the busiest year ? What are price spikes ?
12. Ans:  We can see that the busiest time of the year in Seattle is March means summer and we can see some increasing trend in december means winter, so it tells us that summer and winter are the busiest time in seattle and prices are more in months of June-July-aug-sep, it may be due to the fact that there are less listings available.
13. ---> Can you describe the vibe of each Seattle neighborhood using listing descriptions?
14. Ans: Here we will see Prices v/s months for different locations

## Now will Machine learning to find out whuch all the important features of the dataset
1. One is convert all the categorical features to the dummy variables
2. I use 4 ML models: Decision Trees, Random Forest, Ridge Regression and XGBoost
3. After running them models, we can see that Random Forest is the best.
4. Now, we will find out the important features using Feature importance functionality
5. We findout that: : Bathrooms, how many person they can accomodate, beds, property type, whether the calendar is updated or not? are the best features

######## THANK YOU###########
