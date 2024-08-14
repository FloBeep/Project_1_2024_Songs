
Welcome on the Read Me file for Team 2. 

The team is composed of Ada, Florian and Selina.

The team choose to produce an analysis on a free of rights Music Streaming database for 2024 

The questions we are answering in this analysis are:

1. How does the timing of a song release affect popularity on Spotify?
2. Are there specific artists that perform better across multiple platforms?
3. Does a track’s performance changes when it is classified as explicit?
4. What is the relationship between social media interactions and track performances?

Link of the datasets: https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024/data

Analysis

1. On the Spotify platform, songs released in January had the highest number of streams. We found that there was not a lot of difference between the of streams based on the seasons. While songs released in the spring had the highest streams, there were only relatively small increments in number of streams between fall, winter and summer.

2. Our analysis on the top 10 artists across our platforms of interest, Spotify, YouTube, TikTok, Pandora revealed the following:
 - The number of streams on TikTok was far greater that the number of streams on any other platforms. For example the artist with the highest number of streams on TikTok had a total of 280 billion views. By comparison the artist with the greatest number of streams on YouTube has only about 8 billion views by comparison. TikTok was by far the largest platform in terms of number of views/streams
 - The types of artist that were popular differed across platforms. Spotify and Pandora's must popular artist are more mainstream and recognizable artists. By comparison the most popular artist on TikTok was Kevin Macleod whose is known for his popular, royalty free music. The music that was popular on this platform clearly catered to social media content creation. YouTube had the most diverse representation of artists in the top 10 including non-English speaking artists and Pinkfog, the artist being the popular children's song, "Baby Shark"

3. Using the metrics for Spotify Streams, YouTube Views, TikTok Likes, TikTok Views, and Pandora Streams, we were able to observe that:

Spotify Streams: Both explicit and non-explicit tracks have similar average counts.
YouTube Views: Non-explicit tracks have a significantly higher average count compared to explicit tracks.
TikTok Likes: Explicit tracks slightly outperform non-explicit tracks in average count.
TikTok Views: Non-explicit tracks have a much higher average count compared to explicit tracks.
Pandora Streams: Both explicit and non-explicit tracks show similar average counts with a slight edge for explicit tracks.

By calculating the T-Stat and the P-values, we were able to confirm that there is no significant difference between explicit and non-explicit tracks for all platforms, except YouTube Views the very small P-value indicates a significant difference, with non-explicit tracks performing better.

We can see in our total number of Streams bar chart that the popularity of Non-Explicit songs is higher than the one of explicit songs for all platform, nearing 6 trillions streams. Explicit tracks have around 3 trillion total streams, which is about half the streams of non-explicit tracks.

If we look at the most listened artists bar graph, we can see that 2 artists are by far the most listened too. Kevin MacLeod and The King Khan & BBQ Show. Kevin MacLeod composed more than 2,000 royalty free musics that are used on social media. Which explained is ranking as number 1 of the most streamed artist.
The King Khan & BBQ Show as a very very popular song on Tiktok with more than 18 billions uses!

Therefore a lot of the Non-Explicits streams are due to those 2 artists which add 3 trillions of streams to the non-explicit chart.

4. We can see here that we ran a linear regression comparing social media engagement (Likes) with content performance (Views) on platforms like Youtube and TikTok. This helps us understand the relationship between how much a video is liked and how often it is viewed.

Youtube Views vs Youtube Likes 

We plotted likes on the x-axis and views on the y-axis. The slope is positive, y= 127.27x + 28924790.03 The scatter of data primarily clusters towards the lower end of likes and views, but we can see that there are a few outliers with extremely high values. This regression suggests a positive correlation which means as likes increase, views also tend to increase.

TikTok Views vs TikTok Likes

Just like Youtube, we plotted likes on the x-axis and views on the y-axis. The equation displayed y=10.62x + 34944787.26 This means that each like corresponds to an increase of around 10.62 views. We can see that the data points are clustered near the origin. This shows us that TikTok videos in this dataset have relatively low likes and views with a few outliers reaching extremely high values. However, we can identify a positive correlation specially that the slope and high intercept show that even videos with a moderate number of likes can have a large number of views.

Both these graphs show us a positive correlation between social media likes and views on both platforms. We conclude that likes are a strong predictor of views, which shows how important user engagement is for popularity. The success of the content on both YouTube and TikTok can depend on how well it engages users which is shows by the likes and this can lead to more exposure because algorithm of platforms like content that gets more likes.



Resources:

Define a function to create Linear Regression plots: https://stackoverflow.com/questions/61263177/defining-a-function-to-make-automated-plots-using-matplotlib