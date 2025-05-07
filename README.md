# MrBeast YouTube Data Analysis

## Problem Statement
As digital content creation becomes increasingly important, understanding the key drivers behind video success on platforms like YouTube is essential. By analyzing data from MrBeast's YouTube channel, this project seeks to identify patterns in video performance. Specifically, it focuses on understanding which content generates the most engagement — measured by views, likes, and comments — and how these metrics correlate over time.

## Approach
In this project, we analyze YouTube data from MrBeast's channel, with the goal of uncovering actionable insights that could potentially enhance content strategy and audience growth. The approach involves several key steps:

1. **Data Collection**: The dataset was sourced from Kaggle, which provides publicly available data related to YouTube channels. The dataset includes video details such as the number of views, likes, comments, and publish dates.
   
2. **Data Cleaning**: The raw dataset was cleaned to handle missing values and to ensure that the data is structured correctly for analysis.

3. **Exploratory Data Analysis (EDA)**: We explored the dataset by performing several types of analysis:
   - Views over time: Identifying trends in viewership.
   - Most viewed, liked, and commented videos: Analyzing the top-performing content.
   - Likes vs views: Understanding the relationship between these two metrics.
   - Comments vs views: Analyzing audience interaction in relation to views.

4. **Visualization**: For each analysis, the data was visualized using **matplotlib** and **seaborn** to create clear, informative graphs that illustrate the findings.

5. **Real-World Impact**: The insights gained from this analysis provide valuable recommendations for improving video performance and driving audience growth. By understanding the patterns behind the most popular content, content creators can refine their strategies to increase engagement and attract more viewers.

## Dataset
The dataset used in this project was obtained from Kaggle, and it contains the following columns:
- `video_id`: Unique identifier for each video.
- `title`: Title of the video.
- `published_at`: The date the video was published.
- `views`: The number of views on the video.
- `likes`: The number of likes on the video.
- `comments`: The number of comments on the video.

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `seaborn`: For advanced statistical visualizations.
- `numpy`: For numerical computations.

## Conclusion
By analyzing the views, likes, and comments on MrBeast's YouTube videos, this project provides insights into the factors that drive video success. Understanding which content performs best and why can help content creators improve their strategies, attract a larger audience, and increase engagement. The analysis demonstrates the real-world impact of data-driven decision-making in digital content creation.
