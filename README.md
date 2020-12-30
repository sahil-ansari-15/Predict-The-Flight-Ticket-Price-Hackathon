# Predict The Flight Ticket Price (Hackathon)

Hackathon by 'www.machinehack.com'. 

My Hackathon Rank : 228 

Participants in Hackathon  : 2600+ (till date 28/12/2020)

ML Algorithm used: Random Forest Regressor with hyperparameter tuning.

## Overview
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travellers saying that flight ticket prices are so unpredictable. Huh! Here we take on the challenge! As data scientists, we are gonna prove that given the right data anything can be predicted. Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities. Size of training set: 10683 records Size of test set: 2671 records FEATURES: Airline: The name of the airline. Date_of_Journey: The date of the journey Source: The source from which the service begins. Destination: The destination where the service ends. Route: The route taken by the flight to reach the destination. Dep_Time: The time when the journey starts from the source. Arrival_Time: Time of arrival at the destination. Duration: Total duration of the flight. Total_Stops: Total stops between the source and destination. Additional_Info: Additional information about the flight Price: The price of the ticket

## Data

Data_Train.xlsx

Test_set.xlsx

Raw Data Source : https://www.machinehack.com/hackathons/predict_the_flight_ticket_price_hackathon/data

## Conclusion

We successfully completed data cleaning/wrangling, EDA, feature selection, ML Model selection & finally Flight fare prediction. We compared r2_score of various Models(LinearRegression ,Lasso ,Ridge ,SVR ,RandomForestRegressor ,DecisionTreeRegressor ,XGBRegressor) using Sklearn's 'Cross Validation Score'. RandomForestRegressor with Hyperparameter Tuning was selected as it was giving the best r2_score. Predicted price(output ) was transformed into pandas dataframe & then in excel file format which later uploaded on Hackathon portal (https://www.machinehack.com/hackathons/predict_the_flight_ticket_price_hackathon/overview).

We successfully secured 228 Rank (28/12/2020) in Hackathon with 2600+ participants!!
