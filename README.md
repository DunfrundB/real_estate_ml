### real_estate_ml
##Fannie Mae API Housing Pulse Data
#National Housing Survey
#Data was extracted from Fannie Mae API exchange as a JSON file
#imported Pandas, Requests, and JSON
#curl command was translated into a python command using https://curl.trillworks.com/
#Data was cleaned into a dataframe to include the 5 most relevant questions in the survey, in addition, to shortening the timeframe from January-2021 to June-2021, instead of January-2011 to June-2021 through parsing the data. 
#A dictionary was created for "dates", "question_list", and "track_value",i.e., right or wrong track(sentiment)
