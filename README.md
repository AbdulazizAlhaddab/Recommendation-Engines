# Recommendations Engines with IBM
This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.

##  Infrastructure
This project requires Python 3.x and the following Python libraries installed:
- [Nltk](https://www.nltk.org/)
- [Pandas](http://pandas.pydata.org)
- [Progressbar](https://pypi.org/project/progressbar/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## Overview:
The following tasks are included in the project:
- Exploratory Data Analysis: This section is for exploring data.
- Rank Based Recommendations: To begin constructing recommendations, I look for the most popular articles with the most interactions. These are the articles we might suggest to new users (or anyone depending on what we know about them).
- User-User Based Collaborative Filtering: In order to develop better suggestions for IBM's platform users, I look at users who have engaged with comparable products. These goods could then be suggested to other users.
- Content-Based Recommendations: I created a content-based recommendation system using NLP capabilities.
- Matrix Factorization: Eventually, I finished a machine learning technique to recommendation construction. Making use of user-item interactions, I created a matrix decomposition. Using the decomposition, I was able to estimate how effectively I can predict new articles that a person could interact with.
## Data
- user-item-interactions.csv: file contains user interaction.
- articles_community.csv: file contains articles description.  

## Acknowledgments
I'd like to thank [Udacity](https://eu.udacity.com/) for this fantastic project and [IBM](https://dataplatform.cloud.ibm.com/) for the data.
