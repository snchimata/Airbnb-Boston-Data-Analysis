# A Data-Driven Story of Boston Airbnb
## Data Scientist Nanodegree - Write a Data Science Blog Post

## Installation

This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [NLTK](https://www.nltk.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [plotly-express](https://plot.ly/python/plotly-express/)
- [WordCloud](https://pypi.org/project/wordcloud/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [lightgbm](https://lightgbm.readthedocs.io/en/latest/)

[Anaconda](https://www.continuum.io/downloads) is the recommended distribution, a pre-packaged Python distribution that contains all of the necessary libraries or [Google Colab](https://colab.research.google.com/) can be utilized for the project. 


## Project Motivation

To explore messy real-world data and come up with valued business questions that could be answered by data science skills.
Use visualizations to make findings more understandable and catchy.
Communicate with stakeholders from different backgrounds addressing the below mentioned questions.

## Business questions being answered

1. Predict the sentiment score for user comments

2. Assess relation between review score rating, number of reviews and price

3. Identify Most important attributes emphasized by hosts and required for tenants

4. Predict the monetary value of rental based on listing information

5. Identify Prominent features to affect the rental price


## File Descriptions 

There are three CSV files of Boston Airbnb data and a ipynb notebook with exploratory data analysis, sentiment analysis, to Modeling and feature importance etc.
1. calendar - Price and availability of each Airbnb house.  
2. listings - Title, description, Amenities, ratings, layouts and everything about each AirBNB house. 
3. reviews - Data related to comments by guests
4. Airbnb-Boston-Data-Analysis.ipynb - Notebook with data-driven analysis 

## Data Preperation Process

Process involves Steps to data cleaning by dropping features/imputing values/wrangling and exploration to answer above mentioned business questions. Data wrangling work is heavy on "listing.csv" to convert data and to extract useful information for the Model consumption. Missing values are interpolated or dropped based on data judgments. Histogram, Scatter plots and Wordclouds are adopted to visualize the results better.

## Results

In this project, we have delved into the Boston Airbnb datasets and found some interesting patterns:

1. We used Vader NLTK library to predict user’s sentiment score based on their comments.
2. We evaluated the relation between review scores rating, number of reviews and price
3. We Identified the most important attributes emphasized by hosts and required to tenants
4. We used Lightgbm ML library to predict the price of rental based on the listing information.
5. We found that the most important features in predicting the price of a rental.

The main findings of the code can be found at the post available [here](https://medium.com/@snnchimata/a-data-driven-story-of-boston-airbnb-5056e8f823e8).

## Licensing, Authors, Acknowledgements

Must give credit to Kaggle - Airbnb for the data.  Licensing data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/boston).  Otherwise, feel free to use the code here as you would like! 

Thanks to teams from Udacity's Data Scientist Nanodegree for a captivating journey.
