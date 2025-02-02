# A Large-Scale Dataset of AI-Related Tweets: Structure and Descriptive Statistics

A large-scale dataset of AI-related tweets, comprising over 7.5 million entries spanning from January 1, 2017, to July 19, 2021. The dataset captures various metadata attributes, including user interactions, engagement metrics, and linguistic properties. It serves as a valuable resource for researchers studying the evolution of AI discourse, social media engagement, and sentiment analysis. 

**Specifications Table:**

| Specification | Details |
|--------------|---------|
| Subject Area | Social Media Analytics, Natural Language Processing, Data Science |
| Type of Data | Structured text data |
| How data was acquired | Extracted from Twitter API |
| Data format | CSV (original), converted to QS format |
| Experimental factors | Not applicable |
| Experimental features | Descriptive metadata, user interactions, and engagement metrics |
| Data accessibility | Available upon request or in repositories |

**Data Description:**
The dataset consists of 7,511,304 tweets, capturing various metadata features relevant to AI-related discussions. The variables include tweet-specific attributes (e.g., tweet ID, creation timestamp, text content), user-specific details (e.g., user ID, username, name), engagement metrics (e.g., number of replies, retweets, likes), and contextual information such as mentions, hashtags, and embedded URLs. The dataset spans from January 2017 to July 2021, covering multiple time zones and language settings.

### **Key Variables:**
- **Temporal Variables:** The dataset includes timestamps in both date and time format, allowing for time-series analysis of AI discussions.
- **User Information:** Each tweet is associated with a unique user ID, username, and display name.
- **Engagement Metrics:** The dataset captures the number of replies, retweets, and likes per tweet, with values ranging from zero to over 230,000 likes.
- **Content Attributes:** The presence of hashtags, cashtags, URLs, photos, videos, and quote URLs enables a multimodal analysis of tweets.
- **Retweet and Reply Structure:** Retweet status is recorded as a logical variable, and reply threads are mapped using a conversation ID.
- **Linguistic Features:** The dataset includes the original language of the tweet, with potential for further translation and sentiment analysis.

### **Descriptive Statistics:**
The dataset spans a period from January 1, 2017, to July 19, 2021, with a median date of April 20, 2019. The tweets originate from multiple time zones, with an average offset of -423.1 minutes. The engagement statistics show that the mean number of replies per tweet is 0.1395, while the mean retweets count is 2.0256 and the mean likes count is 2.7038. The maximum values observed in these categories are substantial, with the most-liked tweet accumulating 231,879 likes, the most-retweeted post reaching 78,672 retweets, and the most-replied-to tweet garnering 11,736 replies. The dataset contains binary indicators for retweets (FALSE for all), as well as fields related to media content, such as photos, videos, and quote URLs. The presence of multimedia elements suggests potential applications for visual content analysis.

Additionally, the dataset comprises 36 variables. The **date** column is formatted as an `IDate` object, ensuring efficient handling of temporal data. The **timezone** variable, stored as an integer, records offsets from UTC, with values primarily clustered around -400 minutes. The **source** and **geo** fields predominantly contain `NA` values, reflecting missing geolocation metadata. The **hashtags** and **mentions** fields are stored as character vectors containing JSON-like lists of tagged terms and user references, enabling advanced textual analysis. The dataset contains 1,032,267 unique users, further illustrating the diversity of engagement and participation in AI-related discussions on Twitter.

**Potential Applications:**
This dataset provides a robust foundation for various research applications, including but not limited to:
1. **Trend Analysis:** Examining the temporal evolution of AI-related discourse on Twitter.
2. **Sentiment and Emotion Analysis:** Leveraging natural language processing techniques to assess public perceptions of AI.
3. **User Engagement Studies:** Analyzing the dynamics of retweets, likes, and replies in AI-related discussions.
4. **Network Analysis:** Mapping interactions between users through mentions, replies, and retweets.
5. **Multimodal Analysis:** Investigating the role of images, videos, and external links in AI-related communication.

**Conclusion:**
This dataset represents a significant contribution to social media analytics, particularly in understanding AI-related discourse. Its structured metadata and extensive coverage allow for diverse analytical approaches, from time-series forecasting to deep learning applications in text classification. Future studies can expand its scope by integrating additional contextual data from external sources or applying advanced machine learning techniques to uncover hidden patterns.

**Acknowledgments:**
The authors acknowledge the role of Twitter API in data collection and emphasize compliance with ethical guidelines in handling social media data.

**Data Availability:**
The dataset is available here with an MIT License.

