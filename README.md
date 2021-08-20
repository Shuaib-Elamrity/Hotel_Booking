# Hotel_Booking
Hotel booking demand datasets(Data in Brief:2019)
## Description
### Context 
> This dataset contains 119390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.
                    
               
### Content
> Since this is hotel real data, all data elements pertaining hotel or costumer identification were deleted.Four Columns, 'name', 'email', 'phone number' and 'credit_card' have been artificially created and added to the dataset.
           
           
### Acknowledgements
> The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.
  
  
##  Predicting cancelations¶
It would be nice for the hotels to have a model to predict if a guest will actually come.    
This can help a hotel to plan things like personel and food requirements.    
Maybe some hotels also use such a model to offer more rooms than they have to make more money... who knows..


## Outlines
 - [Import libraries & Data ](#import_libraries)
 - [Read and know the data ](#read_data)
 - [Assessing_Data ](#assessing)
 - [Cleaning_Data](#clean)
 - [Analyze and Visualzing Data](#analyze)
 - [Conclusions](#conclusions)
 - [Reference](#reference)


## Observation 
> This project is a general project to explore and analyze this data without having a major problem to solve, so you will find that I worked on most of the variables and the relationships between them to explore and analyze most of the data

# import the libraries that i will be using
-. Numpy      
-. Pandas   
-. matplotlip.pyplot   
-. Seaborn     
-. Ploty


<a id='conclusions'></a>
# The most important conclusions
1.  The CITY_HOTEL have double of the number of RESORT_HOTEL 
2. 2016 have highest number of reservations BUT we dont have the last quaerter of 2017 SO we can't say that 2016 have haighest reservation than 201
3. The third quarter of the year has the highest rate of bookings, especially the month of August
4. Most of the nights for a week stay are two or three days, and there are some reservations that have more than 10 days, but they are too few to be outliers
5. Most of reservation don'd stay in weekend nights , or stays one or two days
6. LEAD_TIME has a long tail distributions and most of reservation has lead_time between [0:50] days
7. The most of reservations ask BB (Bed and Breakfast
8. Portugal is the most booked country

9. the rate of cancellation of reservation increasees every year but at simple rates
10. he average price per room, depending on its type and the standard deviation. Note that due to data anonymization rooms with the same type letter may not necessarily be the same across hotels
11. the price in the resort hotel increase in summer [ Augest , july] , but city hotel increase in [April , May ,June ]¶

<a id='reference'></a>
# References
1. [stack_over_flow](https://stackoverflow.com/)
2. [panda ](https://pandas.pydata.org/)
3. [Kaggle](https://www.kaggle.com/gregorut/videogamesales)

# Created by "Data_Analyst" : Shuaib Alamrity
 [Github](https://github.com/Shuaib-Elamrity)
 [Linkedin](www.linkedin.com/in/shuaib-elamrity-790430216)
