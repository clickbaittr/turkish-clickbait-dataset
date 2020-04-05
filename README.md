# Turkish Clickbait Dataset
This dataset presents one of the first efforts for clickbait detection in Turkish news headlines. We contribute to future works with the dataset consisting of 48,062 news headlines (24,031 clickbait, 24,031 non-clickbait).

# General Information
![](https://github.com/clickbaittr/turkish-clickbait-dataset/blob/master/image/data_acquisition.png?raw=true)

# Structure of Dataset
The dataset consists of clickbait and non-clickbait headlines as two different categories providing a structure suitable for analysis to be made for clickbait detection. News headlines taken from Twitter accounts of Limon Haber and Spoiler Haber were included in clickbait data while the headlines taken from Twitter accounts of Evrensel and Diken Newspapers were included in non-clickbait data. 

Limon Haber and Evrensel Newspaper shared their tweet data for this dataset and the tweets of Diken Newspaper and Spoiler Haber are gathered manually from Twitter since there was no response to request for data. After the dataset is created, their permissions are obtained for sharing their data. The data have an equal representation of clickbait and non-clickbait headlines. The amounts of data extracted from these 4 accounts are the following:

![](https://github.com/clickbaittr/turkish-clickbait-dataset/blob/master/image/image/numbers.png?raw=true)

The dataset consists of source information (source), information about on which date tweets were shared (created_at), news headline (full_text), how many times a tweet was liked by other users (favorite_count) and how many times a tweet was shared by other users (retweet_count). Since Limon Haber and Evrensel Newspaper shared their tweet data with us, the data of these accounts also includes tweet id number (tweet_id). There is no tweet id infromation in data of Spoiler Haber and Diken Newspaper since the data of these two accounts were gathered manually. For the same reason, some tweets of these two accounts do not contain information about number of retweets and number of likes. 

# Clickbait Headlines
Tweets of Limon Haber and Spoiler Haber were choosen for clickbait category since they are voluntary Twitter accounts that alert people against clickbait news headlines of various Turkish news sources by sharing/retweeting them. Twitter account of Limon Haber contains 33200 tweet (22 March 2020) while Spoiler Haber’s account includes 14900 tweets (22 March 2020).

# Non-clickbait Headlines
Tweets of Evrensel and Diken Newspapers were choosen for non-clickbait category since they were recommended by Limon Haber, and the headlines of these two news sources are rarely shared as clickbait by Limon Haber. Twitter account of Evrensel Newspaper consist of 358000 tweets (22 March 2020) and Twitter account of Diken Newspaper consists of 240800 tweets (22 March 2020).

# Acknowledgement
We would like to thank Limon Haber and Evrensel Newspaper for supporting the construction of this dataset by sharing their tweet data with us, and allowing us to make their tweet data public for further studies. We also would like to thank Spoiler Haber and Diken Newspaper for allowing us to make their tweet data public.

