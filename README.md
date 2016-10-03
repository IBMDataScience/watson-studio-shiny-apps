# Shiny apps in the IBM data science experience

Shiny Apps for datascience.ibm.com

## Predictions of car accident in NYC based on weather data:

This shiny app shows how the IBM Data Science Experience was leveraged to show the results of a car accident predictive model in New York City. The model was trained using historical data of car accidents and IBM weather's data. The weather conditions per zip code were used as features to train a logistic regression model that predicts the probability of a car accident at the zip code level. 

###### Running the Shiny App
- Download [the predict-accidents zip file](https://github.com/IBMDataScience/dsx-shiny-apps/blob/master/predict-accidents.zip) to your laptop
- Open RStudio in [Data Science Experience](http://datascience.ibm.com/) from the left navigation bar 
- On the bottom right part of RStudio, under "Files", click on the "Upload" option
- Click on "Choose File" and browse for the "predict-accidents.zip" on your laptop (dowloaded on the first step)
- Click on the "predict-accidents" directory
- Open the server.R file by clicking on it
- On the top left, open the shiny app by clicking on the "Run App" button
- You should get a really cool map that shows the probabilities of car accidents per zip code 
- On the right panel of the app you can interact with the app by choosing the desired date and time of interest
- Click on the circles to get the zip code and the probability

## Blocpower:

This shiny app shows how the IBM Data Science Experience offering was leveraged to model and understand energy usage within under-served communities in NYC. Come see how these models led to previously undiscovered insight that helped energy analysts better target their clean energy project offers among  the communities involved.

###### Running the Shiny App - Flex Dashboard
- Open RStudio in Data Science Experience from the left navigation bar 
- Create a new R Markdown Document - note you may be required to download some R packages at this time
- Copy the raw [R Markdown from here](https://raw.githubusercontent.com/IBMDataScience/SparkSummitDemo/master/shinyDemo.Rmd)
- Replace the default content in the new R Markdown file by pasting the code in the file
- Select lines 21 - 65 and execute (This is a one time set up to install all necessary packages)
- Click the Knit button with the ball of yarn next to it
- Ignore the error on the pop-up and click the button "Open in Browser" to see the app in a web browser
- Open the app in a browser to interact with it, share the link with anyone
