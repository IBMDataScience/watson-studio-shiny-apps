# Shiny apps in Watson Studio

Shiny Apps for ibm.com/cloud/watson-studio

## Predictions of car accident in NYC based on weather data:

This shiny app shows how the IBM Watson Studio was leveraged to show the results of a car accident predictive model in New York City. The model was trained using historical data of car accidents and IBM's weather data. The weather conditions per zip code were used as features to train a logistic regression model, using Spark, that predicts the probability of a car accident at the zip code level, at an specific date and time of the day. 

###### Running the Shiny App
- Download the predict-accidents [zip file](https://github.com/IBMDataScience/watson-studio-shiny-apps/blob/master/predict-accidents.zip) to your laptop (no need to unzip!)
- Open RStudio in [Watson Studio](https://www.ibm.com/cloud/watson-studio) from the left navigation bar 
- On the bottom right panel of RStudio, under "Files", click the "Upload" option
- Click "Choose File" and browse for the "predict-accidents.zip" on your laptop (downloaded on the first step)
- Click the "predict-accidents" directory
- Click the global.R file to open it (will show up on the top left part of the screen)
- Click the "Run App" button to run the shiny app

You should get a really cool map that shows the probabilities of car accidents per zip code. On the right panel of the app you can interact with the app by choosing the desired date and time of interest. Click the circles to get information on the zip code and the probability of accident.

For questions, please contact 
- Jorge Castanon, jorgecasta@us.ibm.com

## Analyzing flight delays:

This shiny app shows how the IBM Watson Studio was leveraged to show an interactive map to analyze flight delays. The app can be used to explore the average flight delays (in minutes) for each airport. The user can interact with the app by choosing the month and year to be explored. In addition, the user can click on airport to get the airport name, code, state and city. The size of the circles depends on the volume of flights for each airport. 


###### Running the Shiny App
- Download the flights [zip file](https://github.com/IBMDataScience/watson-studio-shiny-apps/blob/master/flights.zip) to your laptop (no need to unzip!)
- Open RStudio in [Watson Studio](https://www.ibm.com/cloud/watson-studio) from the left navigation bar 
- On the bottom right panel of RStudio, under "Files", click on the "Upload" option
- Click "Choose File" and browse for the "flights.zip" on your laptop (dowloaded on the first step)
- Click the "flights" directory
- Open the server.R file by clicking it in RStudio
- On the top left panel, open the shiny app by clicking the "Run App" button

You should get a really cool map that shows the average flight delay (in minutes) for each airport. On the right panel of the app you can interact with the app by choosing the desired year and month of interest. Click on the circles to get the airport name and code, as well as the average delay of arriving flights.

For questions, please contact 
- Jorge Castanon, jorgecasta@us.ibm.com

