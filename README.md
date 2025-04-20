# Airline Time-Series Analysis for Charlotte AI Reasearch's AI Hackathon 2025
Team members: Stephen Butters, Mark Schwarzmann, Lillian Chen, Jerell Bell

## Overview
This project is about using time-series analysis to forecast the number of U.S flights in the future and Covid-19's affect on the airline industry. This was accomplished by using this U.S. Airline dataset (2003-2023) from Kaggle (https://www.kaggle.com/datasets/yyxian/u-s-airline-traffic-data/data) and using Facebook's Prophet model to build a model that can forecast the future amount of flights in the U.S. We chose Prophet because of it's ability to account for variance in the data, such as our data being affected by the seasons and Covid-19. We added regessors and weights to the model to help better guide the model on what areas of the data to focus on for better results.

## Forecasting Domestic and International Flights
We trained a Prophet model using U.S. Airline data from 2003-2023 to make a forecast for 2024 and we compared that forecast to another dataset containing U.S. Airline data from 2024. The results for domestic flights showed that our model only had a 7% error on average, meaning our forecast was very close to what actually happended. The results for international flights were still a close 18% error.

## Forecasting Covid-19's Lasting Impact on the Airline Industry
We took our model that was trained for our Domestic and International Flights and removed years 2020-2023 from the training so we could create a forecast of how it would look in 2024 if Covid never existed. We found for Domestic flights, Covid-19 had an impact during summer and fall months, as the forecast shows there would be around 100000-150000 more domestic flights during those times if Covid never existed. However, we found that Covid-19 only had a slight or no impact on international flight as there is only a small 4% error comparing our forecast to the actual amount of flights. The results could show that after the result of Covid-19, people were more motivated to fly international than ever before.
