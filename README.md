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

Word Clouds:
The first two plots are word clouds generated from the dataset.
Word clouds visually represent the most frequent words or terms in a dataset, with word size indicating frequency.
The first word cloud represents positive comments, while the second negative comments.
They are useful for identifying common themes or keywords in textual data.

Bar Chart (Emojis Frequency):
This bar chart shows the frequency of emojis used in the data.
Each bar represents an emoji, and the height of the bar indicates how often that emoji appears.
It provides insights into the prevalence of emojis in the dataset.

Box Plot (Likes vs. Video Categories):
The first box plot compares the distribution of 'likes' across different video categories.
It helps visualize the spread and central tendency of likes for each category.
Useful for understanding how the video category impacts the number of likes.

Box Plot (Like Rate vs. Video Categories):
The second box plot compares the distribution of 'like_rate' (likes per view) across video categories.
It provides insights into audience engagement with videos in different categories.
Helpful for analyzing the relative popularity of categories.

Regression Plot (Views vs. Likes):
This regression plot shows the relationship between the number of 'views' and the number of 'likes' for videos.
It helps identify if there's a linear correlation between these two variables.

Bar Chart (Top 20 Channel Titles):
The bar chart displays the top 20 channel titles based on a specific criterion (could be views, likes, etc.).
Each bar represents a channel title, and the height represents the corresponding metric.
It's useful for identifying the most influential or popular channels.
Box Plot (Views vs. Punctuation Count):

The first box plot examines how the count of punctuation in video titles affects the number of 'views.'
It provides insights into whether the use of punctuation has any impact on views.
Box Plot (Likes vs. Punctuation Count):

The second box plot investigates the relationship between the count of punctuation in video titles and the number of 'likes.'
It helps determine if there's a correlation between punctuation and likes.
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

