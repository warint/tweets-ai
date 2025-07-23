# A Large-Scale Dataset of AI-Related Tweets: Structure and Descriptive Statistics

[![DOI](https://zenodo.org/badge/926193933.svg)](https://zenodo.org/records/15230836)

### Supplement to the following article

> Kouloukoui, D., de Marcellis-Warin, N. & Warin, T. Balancing risks and benefits: public perceptions of AI through traditional surveys and social media analysis. AI & Soc (2025). https://doi.org/10.1007/s00146-025-02232-x

Also in CSV format here:

Kouloukoui, Daniel, Nathalie DE MARCELLIS-WARIN, and Thierry Warin. 2025. “Replication Data for: Balancing Risks and Benefits: Public Perceptions of AI through Traditional Surveys and Social Media Analysis.” Harvard Dataverse. https://doi.org/doi:10.7910/DVN/NHLEJL.

### Data Description

The dataset covers the period from 1 January 2017 to 19 July 2021, with a median tweet date of 20 April 2019. Binary indicators identify the presence of media elements such as photographs, videos, and quoted URLs. A total of thirty-six raw variables were initially collected; in compliance with Twitter’s data redistribution policy and relevant data-protection regulations, nineteen non-sensitive variables were retained for public release. Information on hashtags and user mentions is encoded as JSON-formatted vectors.


## Table 1. Variables and their descriptions

| Variable          | Description                                  |
| -------------------------- | -------------------------------------------- |
| `id`              | Unique tweet identifier                      |
| `conversation_id` | Identifier for the conversation thread       |
| `created_at`      | Date‑time stamp with timezone                |
| `date`            | Calendar date (YYYY‑MM‑DD)                   |
| `time`            | Time of day (HH\:MM\:SS)                     |
| `timezone`        | Offset from UTC (minutes)                    |
| `tweet`           | Text content of the tweet                    |
| `language`        | ISO 639‑1 language code                      |
| `urls`            | External links                               |
| `photos`          | Image URLs                                   |
| `replies_count`   | Number of replies                            |
| `retweets_count`  | Number of retweets                           |
| `likes_count`     | Number of likes                              |
| `hashtags`        | Hashtags (JSON vector)                       |
| `cashtags`        | Stock tickers                                |
| `retweet`         | Flag identifying retweets                    |
| `quote_url`       | URL of quoted tweet                          |
| `video`           | Flag identifying embedded video              |
| `thumbnail`       | Thumbnail URL for video                      |

The dataset consists of 893 076 tweets, capturing various metadata features relevant to AI-related discussions. The variables include tweet-specific attributes (e.g., tweet ID, creation timestamp, text content), user-specific details (e.g., user ID, username, name), engagement metrics (e.g., number of replies, retweets, likes), and contextual information such as mentions, hashtags, and embedded URLs. The dataset spans from January 2017 to July 2021, covering multiple time zones and language settings.

### **Key Variables:**
- **Temporal Variables:** The dataset includes timestamps in both date and time format, allowing for time-series analysis of AI discussions.
- **Engagement Metrics:** The dataset captures the number of replies, retweets, and likes per tweet, with values ranging from zero to over 230,000 likes.
- **Content Attributes:** The presence of hashtags, cashtags, URLs, photos, videos, and quote URLs enables a multimodal analysis of tweets.
- **Retweet and Reply Structure:** Retweet status is recorded as a logical variable, and reply threads are mapped using a conversation ID.

### **Descriptive Statistics:**
The dataset spans a period from January 1, 2017, to July 19, 2021, with a median date of April 20, 2019. The tweets originate from multiple time zones, with an average offset of -423.1 minutes.
The dataset contains binary indicators for retweets (FALSE for all), as well as fields related to media content, such as photos, videos, and quote URLs.
The presence of multimedia elements suggests potential applications for visual content analysis.

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
The dataset is available here with a CC-BY-NC license.

