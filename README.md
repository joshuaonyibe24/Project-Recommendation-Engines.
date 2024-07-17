# Project-Recommendation-Engines
Recommendations Engines with IBM
This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform and make recommendations to them about new articles.

# Installations
This project requires Python 3.x and the following Python libraries installed:

Pandas
numpy 
matplotlib
project_tests 
pickle

# Summary
The project contains the following tasks:

Exploratory Data Analysis: This part involves exploring the data to understand the structure and key characteristics.

Rank Based Recommendations: To get started with building recommendations, I first identified the most popular articles based on the number of interactions. These popular articles are then recommended to new users or any users based on what we know about them.

User-User Based Collaborative Filtering: To build better recommendations for the users of IBM's platform, I examined users with similar interaction patterns. Items interacted with by similar users are then recommended.

Content Based Recommendations: I developed a content-based recommendation system that suggests articles based on the content similarity.


# Data
user-item-interactions.csv: This file contains user interaction data.
articles_community.csv: This file contains descriptions of articles.

# Acknowledgments
I would like to thank Udacity for this amazing project, and IBM for providing the data.
