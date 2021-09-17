# Tweets-Analysis, March 2020 - Europe

In this project, we explore a large dataset of tweets collected from the twitter API during the period March 1st to March 31st 2020 These tweets were collected using a geographical filter specifying a rectangular box over Europe. The bounding box used is specified by (longitude,latitude) coordinates. The lower-left corner is at (-24.5, 34.8) and the upper-right is at (69.1, 81.9). No keyword or other thematic filters were applied, so the dataset should contain all tweets that Twitter can identify as originating from the specified region, irrespective of their topic/content.The data is downloaded as a number of compressed files each covering 1 day of data. The whole dataset is large (typically around 450Mb per day when compressed) and contains millions of tweets. It makes up a total of 13.3 GB of compressed data which reaches to 100 GB on being uncompressed. Each file contains a tweet on every line. Tweets are stored as JSON objects, as described in the Twitter developer documentation. <br> </br>
The project is covered in different parts. <br> </br>
1. **Basic Stats and Data lookup**
  * Sampling Data
  * Dealing with anomalies and duplicates.
  * Analysing number of tweets over the month.
  * Analysing tweets languages.
  * Analysing tweets over weekdays and weekends.
  * Analysing tweets over each hour of the day.
  
3. **Mapping** - The interactive folium maps are not renedered in github notebook. GIFs and html map files in repo can be used to chekout interactive maps. 
  * Using clustered maps to mark geo tagged tweets.
  * Functionality to read tweets by clikiing on map markers.

<img src="./Gifs/all_720gif.gif" width="800" height="400" />

<img src="./Gifs/ireland_720gif.gif" width="800" height="400" />

3. **Users**
  * Analysing tweets per user.
  * Analysing top users and automated accounts.
  * Analysing top mentioned users.
  
5. **Events**
  * Identifying unusal days in Ireland and UK. 
  * Identifying the events on these days.
  * Plotting wordclouds
  * Validating with real world news.
