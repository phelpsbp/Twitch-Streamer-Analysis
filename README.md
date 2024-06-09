# Twitch Streamer Analysis

## Introduction

This project analyzes Twitch streaming data to understand streamer performance metrics and viewer engagement. It compares the performance of partnered and non-partnered streamers.

## Quick Links

- [Streamer Project Webpage](https://phelpsbp.github.io/Twitch-Streamer-Analysis/)
## Project Overview

This project uses a dataset of the top 1000 Twitch streamers to analyze various metrics like watch time, followers gained, and streaming hours. The goal is to identify patterns and trends that can inform streamers and marketers.

### Business Questions

1. **How does partnership status affect streamer performance?**
2. **What are the key metrics that correlate with high follower counts?**
3. **What insights can we gain about viewer engagement from streaming data?**

## Methodology

1. **Data Loading and Preparation**: 
   - Load the dataset and clean it to handle missing or inconsistent values.
2. **Exploratory Data Analysis (EDA)**:
   - Use summary statistics and visualizations to explore the data.
   - Identify correlations between different metrics.
3. **Categorical Data Analysis**:
   - Analyze categorical features like `Partnered`, `Mature`, and `Language`.
   - Understand the distribution and impact of these categories on performance.
4. **Top Channels Analysis**:
   - Identify the top 50 channels based on followers and views.
   - Analyze the common characteristics of these top channels.

### Tools Used: 
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Jupyter Notebook

## Results
1. **Partnership Status**: Being partnered with Twitch leads to more visibility and additional features. The length of time a stream is watched has the strongest link with follower count and growth, suggesting that longer watch times are a major factor in channel popularity.
2. **Content Accessibility**: Channels that avoid 'Mature' ratings and produce more accessible content tend to reach a wider audience.
3. **Language Use**: English is the dominant language among top channels. 
4. **Engagement Metrics**: Metrics like peak viewership and average viewers are vital for assessing a channel's ability to attract and keep a large audience, which is important for long-term popularity and success.
5. **Streaming Duration**: Longer streaming sessions do not necessarily lead to higher engagement rates. There is a slight negative trend between stream duration and followers gained.

## Recommendations
Based on the analysis, these are the following recommendations I'd give to aspiring streamers:

1. Secure partnership status to leverage Twitch's platform features.
2. Prioritize quality in terms of content creation rather than the length of content to ensure longer watch times.
3. Produce content that is accessible to a wider audience, avoiding restrictive ratings where possible.
4. Utilize English to maximize reach but also consider multilingual content to tap into non-English speaking demographics.

## Acknowledgments & References

- Data: [Twitch Streamers Dataset on Kaggle](https://www.kaggle.com/datasets/aayushmishra1512/twitchdata)
- License: [MIT License](LICENSE.md).

## Contact Information

- **Email**: [phelpsbp@gmail.com](mailto:phelpsbp@gmail.com)
- **LinkedIn**: [Brittany Phelps](https://www.linkedin.com/in/brittany-everette/)
- **GitHub**: [phelpsbp](https://github.com/phelpsbp)
