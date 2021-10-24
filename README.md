![beer](https://images.unsplash.com/photo-1586993451228-09818021e309?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=687&q=80)

# Beer-Data-Analysis

 ## Business Problem  
 Our Company is trying to gain insight on how the property of beer can actually affect demand for it from the Consumers. Survey questionaires were given to beer drinkers and they were encouraged to rate various beer types on a scale of 0-5, and also write product reviews about the beers that they rated. The feedback was collated and given to my team for analysis.
 ## The dataset

The dataset contains the beer properties as well as the product reviews collected from the end consumer. beer_ABV
The features in the dataset are described below.

•	beer_beerId == 0, implies that the patient did not survive after 1 year of treatment

•	beer_brewerId, implies that the patient survived after 1 year of treatment

•	beer_name: Care situation of a patient during treatment

•	beer_style: The diagnosed condition of the patient

•	review_appearance: Patient identifier number

•	review_palette: Class of drugs used during treatment

•	review_overall: If the patient survived after one year (0 means did not survive; 1 means survived)

•	review_taste: Age of the patient

•	review_profileName: A calculated value based on the patient’s weight, height, etc.

•	review_aroma: If the patient was a smoker or not

•	review_text: If the patient stayed in Rural or Urban part of the country

• review_time: Condition of the patient before the start of the treatment ( This variable is splitted into 8 columns - A, B, C, D, E, F, Z and Number_of_prev_cond. A, B, C, D, E, F and Z are the previous conditions of the patient.

 
 ## Objective
 
To analyze the dataset and answer the following question:
1.	Rank top 3 Breweries which produce the strongest beers?
2.	Which year did beers enjoy the highest ratings? 
3.	Based on the user’s ratings which factors are important among taste, aroma, appearance, and palette?
4.	If you were to recommend 3 beers to your friends based on this data which ones will you recommend?
5.	Which Beer style seems to be the favorite based on reviews written by users? 
6.	How does written review compare to overall review score for the beer styles?
7.	How do find similar beer drinkers by using written reviews only?   
 
## Requirements 
Libraries used - To succesfully run this Jupyter notebook the following libraries need to be installed.

    - Python 3     - Pandas     - Scikit-Learn     - Seaborn     - Matplotlib     - Numpy  
    
## Data Preprocessing
Preprocessing work done on the data included:

1. Outlier removal

2. Label and one hot encoding for categorical data

3. Handling of missing data by median imputation

4. Replacing missing values  with a hard coded values like zero (eg 1 for yes, 0 for none)



## Models 
1.Gradient Boosting Classifier

2.Ada Boost Classifier

3.Random Forest Classifier

4.Naive Bayes

5.K Nearest Neighbors

6.Decision Tree Classifier

7.Logistic Regression

## Results
Performance Evaluation Metric used:

1.F1 score

2.AUC score

3.Training and test accuracy

4.Confusion matrix

