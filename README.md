# To Real Estate or not to Real Estate...?
A closer look at the 2008 Housing Crisis compared to the housing market today.

# Introduction
As a group our team decided an in depth analysis of the housing market is a very relavant topic for all team memebers.  There has not been a more important historical time period in the US housing market than the 2008 Housing Crisis.  Using predictive machine learning models and sentiment analysis tools our goal is to confirm the following hypothesis:  If the current housing market is at unsustaiable price levels, then a market correction is inevitable.  

# Machine Learning
Our exploring initially began in the Freddie Mac housing price database.  The goal was to get enough data on many different regions across the US in order to correctly train our models.  Freddie Mac had more than enough information than needed.  The data was so intricate they even had columns associated to the mortgage details on homes.  However we ran into issues loading the dataset into jupyterlab and GitHub.  The data set was too large therefore we had to find something else.  This is what ultimatley led us to the Quandl Zillow API.  Zillow had everything we needed, historical housing prices, regions, different size houses.  This simple API tool let us create a dataset for the specific regions we wanted to take a look at.  Our best bet for training models was selecting a dataframe that includes data from the top 30 regions in the US.  

# Sentiment Analysis
...


# Housing Survey Analysis
## Fannie Mae API Housing Pulse Data 
National Housing Survey Data was extracted from Fannie Mae API exchange as a JSON file #imported Pandas, Requests, and JSON curl command was translated into a python command using https://curl.trillworks.com/. Data was cleaned into a dataframe to include the 5 most relevant questions in the survey, in addition, to shortening the timeframe from January-2021 to June-2021, instead of January-2011 to June-2021 through parsing the data. A dictionary was created for "dates", "question_list", and "track_value",i.e., right or wrong track(sentiment) 

## Q1Do you think the economy is on the right track or wrong track? 
In January of 2020, 58% of homeowners surveyed believed the economy was on the right track compared to 34% believed the economy was on the wrong track. In June of 2021, 55% of homeowners surveyed believed the economy was on the wrong track in comparison to 36% that believed we were on the right track. In January of 2021, only 29% surveyed that we were on the right track compared to 58% that believed we were on the wrong track. There are multiple explanations for the negative sentiment in January of 2021, including rising Covid cases and a new administration taking over the white house during a global crisis. The June 2021 sentiment may be due to rising inflation, an overvalued housing market, and impending foreclosures. Additional surveys would need to be implemented to evaluate major contributing factors in driving overall sentiment of the housing market. 

## Q2 In general, do you think it is a goodtime to buy a house? 
In January of 2020, 59% of homeowners believed it was a very good time to buy a home, in comparison to 30% that believed it was not a good time to buy a home. In January of 2021, 52% still believed it was a good time to buy home, but 37% surveyed it wasn’t a good time to buy a home. In June of 2021, only 32% still believed it was a good time to buy a home, in comparison to a staggering 64% that had a negative sentiment for buying a home. This may be due to looming fears regarding a housing market “crash” or correction due to inflation and potential foreclosure moratoriums ending causing an influx of houses to hit the market. 

## Q3 In general, do you think it is a good time to sell a home? 
In January of 2020, 66% surveyed they believed it was a good time to sell a home in comparison to 21% that believed it was not a good time. In January of 2021, 57% surveyed they believed it was a good time to sell, while 33% believed it was not a good time to sell. In June of 2021, 77% surveyed believed that it was a good time to sell a home in comparison to only 15% that believed it was a bad time to sell. 

## Q4 During the next 12 months, do you think home prices will go down or up? 
In January of 2020, 48% surveyed believed home prices would increase, while only 7% surveyed they believed it would decrease. In January of 2021, 41% surveyed believed home prices would increase, while 17% surveyed believed they would decline. In June of 2021, 48% surveyed believed that home prices would still increase, while only 21% surveyed believed housing prices would decline. This may explain why that the sentiment analysis in the news showed a neutral rating. 

## Q5 During the next 12 months, do you believe mortage rates will increase or decrease? 
In January of 2020, 33% surveyed believed mortgage rates were on the “right-track”, while only 7% believed rates were on the “wrong track.” In January of 2021, 45% surveyed believed mortgage rates were on the “right-track”, while 9% believed they were on the “wrong track.” In June of 2021, 57% surveyed believed rates were still on the “right-track”, while only 6% believed they were on the “wrong track.” The survey fails to indicate if rates increasing would correlate to the “right-track”, or “wrong-track”. The assumption is made that most homeowners would see a rate increase as the “wrong track.” 

## Conclusion 
The National Housing Survey seems to indicate that the overall sentiment for the economy is negative. More homeowners have the current sentiment that it is a bad time to buy a home, and a good time to sell. However, homeowners seem to have a neutral sentiment in regards to home prices and mortage rates, in the sense that they believe it will more or less stay the same.




# Conclusion
Thourough analysis and use of different machine learning tools a conclusion was acheived in regards to our current Housing Market.  Public sentiment is a finicky subject but our tools showed us that sentiment is at the nuetral status with a heavy lean towards negative.  According to our survey analysis an extreme shift in public feelings has been trending toward negativity, the public thinks it is a good time to sell and that the economy is headed toward a crash.  Finally our machine learning models have been trained & tested with historical data.  The prediction models show that housing prices are increasing across the board.  The Zillow API tool only had data leading up to 5-31-21. We feel that an ongoing analysis of these models will help the user show downward trends in the market.  More time and data are needed to correctly show a housing market correction.  Our findings display a clear message, all signs point towards a negative public feeling but until housing prices start going down there will be no market correction.  


# Presentation Link
https://docs.google.com/presentation/d/1YOWB786NRycdBRBhVS_qqTyWvLWxTxwOFL4Pavz9BUg/edit?usp=sharing

