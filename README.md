# youtube_api_data_extraction

Data extraction using my favorite Youtube channel (Ivan Djuric). Extracted data using API request library in Python and transformed data into a Pandas dataframe for sentiment analysis. Statistics extracted from videos include view count, like count, and comment count. Other paramters extracted from the videos include the video title, video ID, and upload date. This code also uses'pageToken' to extract data from videos on multiple pages past just the first page, allowing the dataframe to collect data from over 500 videos.
