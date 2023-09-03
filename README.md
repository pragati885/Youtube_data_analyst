# YouTube Data Analysis Project(Textcase Analysis)

## Overview

This project aims to analyze YouTube data to gain insights into trending videos, audience engagement, sentiment analysis, and more. The primary goals of this analysis are to understand YouTube video trends and factors that impact audience engagement.

## Data Collection

- The dataset was obtained from Udemy course Data analyst project using python and contains information about YouTube videos, including video titles, descriptions, view counts, likes, dislikes, and comments.
- Data was collected using Python and the pandas library.

## Data Analysis

### Sentiment Analysis

- Sentiment analysis was performed on video titles and descriptions using natural language processing (NLP) techniques.
- Visualizations of sentiment trends were created using Matplotlib.

### Wordcloud Analysis

- Word clouds were generated to visualize the most common words in video titles and descriptions.
- Word clouds provide a quick overview of popular keywords in the dataset.

### Emoji Analysis

- Analysis of emoji usage in video titles and descriptions was conducted to understand audience reactions.
- Emoji frequency and sentiment were visualized using custom Python scripts and emoji libraries.

## Results and Insights

- The most liked video categories were identified, providing insights into audience preferences.
- Analysis of likes, dislikes, and comments helped gauge audience engagement levels.
- Trends in video views and likes were explored over time.
- The heatmap illustrates the correlation matrix among the variables 'views,' 'likes,' and 'dislikes' from the dataset. Each cell in the heatmap represents   the degree of correlation between two variables, with values closer to 1 indicating a strong positive correlation, values closer to -1 indicating a     
  strong negative correlation, with values near 0 indicating little to no correlation. In this context:

    The correlation between 'views' and 'likes' signifies how the number of views relates to the number of likes a video receives.
    The correlation between 'views' and 'dislikes' measures the relationship between the number of views and the number of dislikes.
    The correlation between 'likes' and 'dislikes' gauges the connection between the number of likes and the number of dislikes.

## Technologies Used

- Python
- pandas
- Matplotlib
- Natural Language Processing (NLP) libraries
- Emoji libraries

## How to Run the Notebook

To run the analysis notebook, follow these steps:

1. Clone this GitHub repository.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Open and run the Jupyter Notebook `youtube_analysis.ipynb`.

