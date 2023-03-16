# Predicting-hotel-booking-cancellations

Probelem statement:

Hotel industry is one of the fastest growing businesses of tourism sector. Hotel bookings have risen dramatically since the arrival of giant online booking services, making it easier than ever to book a hotel. However, the growing trend of the hotel industry comes with problems too, one of the problems is the rising rate of cancellation in the hotel industry. Globally, on an average there is 40% cancellation in hotel bookings every year.

As a result of this cancellation trend, the hotel is unable to accurately forecast occupancy within their revenue management system, and it is also causing opportunity costs to be lost. This project includes building an ideal model to predict the cancellation of a hotel booking along with information on the factors that have a high impact on hotel booking cancellation. This prediction from the model will be beneficial to the hotel management team in managing their operational strategies and to be prepared when there is a cancellation so that there are no surprises.


STEPS:
1. Data Preparation
   - Loading data to dataframe
   - Data Cleaning: Checking null values, treating null values with imputation, dealing with outliers.
2. Data Visualization
   - With bar graphs, pie charts, boxplots
3. Exploratory Data Analysis
   - Correlation and Heat map
   - Feature engineering and feature selection
   - Data scaling
   - Feature encoding
   - Splitting data into test and train
4. Data Modeling
   - Logistic Regression Model
   - Random Forest Model
   - Decision Tree Model
   - KNN Model
5. Model Evaluation


Insights and Recommendations:

- Lead time, deposit type, country are the top three features with highest impact on the model.

- Loyalty programs could be offered to customers having greater lead time so that it can help in the avoiding the cancellations.

- The payment type ‘No Deposit’ tends to experience a greater number of cancellations compared to other deposit types. The hotel management should keep a     nominal amount as minimum deposit in order to get rid of the category of ‘No Deposit’ thus reducing the cancellations. 
  Predicting the number of guests for a hotel can be an important enhancement.

- Having additional feature such as hotel cancellation policy would help the hotel management team to more effectively manage its room inventory.


