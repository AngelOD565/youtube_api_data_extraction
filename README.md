# youtube_api_data_extraction

This is an ETL Data Pipeline project which features data extraction using the Youtube API, transformation into a Pandas dataframe in Python, and loading into an AWS RDS Database. The first part covers the data extraction and transformation using the API and Pandas, while the second part focuses on the loading into the RDS database.  

Statistics extracted from videos include view count, like count, and comment count. Other parameters extracted from the videos include the video title, video ID, and upload date. This code also uses page tokens to extract data from videos on multiple pages past the first page, allowing the dataframe to collect data from over 500 videos. 

While this data extraction and transformation uses a particular youtube channel (Ivan Djuric), this can, of course, be applied to any youtube channel by refactoring the chosen youtube channel ID. It can also be updated for new videos and updated statistics on the channel.

This can be used as a data piepline to be used for a sentiment analysis or other machine learning model.
