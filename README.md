Hi Everyone this is the readme file for my project.Below are some of the steps that I followed:

PART-1 : LIBRARIES USED:

1. To load the dataset, perform operations and plotting the results, we have used the libraries:
-- Numpy, pandas and matplotlib

2. To perform the machine learning we need to import some of the below libraries:
-- XGBoost, Ridge, RandomForestRegressor, DecisionTree (machine learning libraries)
-- train_test_split(to split the datasets)

3. To evaluate the results:
-- We have used r2_score, as this is a regression problem

PART-2: MOTIVATION OF THE PROJECT:

This dataset is way useful because we can analyze some of the questions like :

-- What are the busiest times of the year to visit Seattle? By how much do prices spike?

-- Can you describe the vibe of each Seattle neighborhood using listing descriptions?

-- Which are the top features/predictors that could be useful in knowing what actually attarcts the customers?

-- Futher more we will also see which is the best machine learning algorithm.

PART-3 : STRUCTURE OF THE PROJECT:

For this project we have -- 1 code file: project.ipynb

                         -- 3 datasets : listings.csv
                         
                                       : calendar.csv
                                       
                                       : reviews.csv (This is not much useful for us, we will only work with above 2 files)
                                       
                         -- 1 readme file, where we have documented the important steps useful
                         
PART-4: SUMMARY:

Now we will answer the questions as stated in part-2:

-- Which is the busiest year ? What are price spikes ?

Ans:  Upon doing the analysis,we can see that the busiest time of the year in Seattle is March means summer and we can see some increasing trend in december means winter, so it tells us that summer and winter are the busiest time in seattle and prices are more in months of June-July-aug-sep, it may be due to the fact that there are less listings available.

-- Can you describe the vibe of each Seattle neighborhood using listing descriptions?

Ans: Here we will see Prices v/s months for different locations based on the plot that we concluded in notebook

-- Which is the best machine learning model?

Ans: After running 4 different models, we can see that Random Forest(with r2_score = 98.6%) is the best.

-- Which are the top predictors or imp features?

Ans: We findout that: : Bathrooms, how many person they can accomodate, beds, property type, whether the calendar is updated or not? are the best features.

You can also find the detailed analysis of this project on my blogpost: https://karangupta485.medium.com/airbnb-seattle-reservation-price-analysis-9a0db0fc502d

PART-5: Acknowledgments

This dataset has been taken from Kaggle, link is: https://www.kaggle.com/airbnb/seattle

I would further like to thank Udacity for the motivation and further providing me the appropriate material and guidance.
