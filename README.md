
Welcome on the Read Me file for Team 2. 

The team is composed of Ada, Florian and Selina.

The team choose to produce an analysis on a free of rights Music Streaming database for 2024 

The questions we are answering in this analysis are:

1. How does the timing of a song release affect popularity on Spotify?
2. Are there specific artists that perform better across multiple platforms?
3. Does a track’s performance changes when it is classified as explicit?
4. What is the relationship between social media interactions and track performances?

# Link of the datasets: https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data

Analysis

1. 
2. 
3. We can see in our analysis that the popularity of Non-Explicit songs is higher than the one of explicit songs for all platform, except for Spotify. Globally, Non-Explicit songs are twice more popular than Explicit songs.

By calculating the T-Stat and the P-values, we were able to confirm that there is no significant difference in any platforms between explicit and non-explicit tracks.


4. We can see here that we ran a linear regression comparing social media engagement (Likes) with content performance (Views) on platforms like Youtube and TikTok. This would help us understand the relationship between how much a video is liked and how often it is viewed.
   
Youtube Views vs Youtube Likes
We plotted likes on the x-axis and views on the y-axis. The slope is positive, y= 127.27x + 28924790.03
The scatter of data primarily clusters towards the lower end of likes and views, but we can see that there are a few outliers with extremely high values. This regression suggests a positive correlation which means as likes increase, views also tend to increase. 
The r-value is 0.8339. This is the indicator of a strong positive linear correlation between both likes and views. But, other factors play significant roles.

TikTok Views vs TikTok Likes
Just like Youtube, we plotted likes on the x-axis and views on the y-axis. The equation displayed y=10.62x + 34944787.26
This means that each like corresponds to an increase of around 10.62 views. We can see that the data points are clustered near the origin. This shows us that TikTok videos in this dataset have relatively low likes and views with a few outliers reaching extremely high values. However, we can identify a positive correlation specially that the slope and high intercept show that even videos with a moderate number of likes can have a large number of views.
the r-value is 0.9925, close to 1, which suggests a very strong correlation. Because the correlation is near perfect, it is an indicator of how reliable user engagement is. 

Both these graphs show us a positive correlation between social media likes and views on both platforms. We conclude that likes are a strong predictor of views, which shows how important user engagement is for popularity. The success of the content on both YouTube and TikTok can depend on how well it engages users which is shows by the likes and this can lead to more exposure because algorithm of platforms like content that gets more likes. The r-value for TikTok can also be higher because Youtube might have a more nuanced algorithm. TikTok also allows people to quickly engage with content that generates likes instantly unlike Youtube where a more comprehensive approach should be taken.



adding code to remove errors
