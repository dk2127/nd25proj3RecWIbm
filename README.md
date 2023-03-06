## nd25 project3 Recommendations with AI/ML service provider

There is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets on the "AI/ML service provider" platform. Users of the system interact with all of this. For this project we will analyze the interactions that users have with articles on the platform, and make recommendations to them about new articles we think they will like.

## Steps:
The project is divided into the following steps:

### I. Exploratory Data Analysis

Before making recommendations of any kind, we will explore the data we are working with for the project. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. We will explore, before we dive into the details of our recommendation system in the later sections.

### II. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. We will implement this next.

### IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using our NLP skills, we might come up with some extremely creative ways to develop a content based recommendation system. We are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

### V. Matrix Factorization

Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.


## Instructions:
Just run the notebook in project#3 workspace.

## Resources:

### U d a c i t y
### I B M for data used in the project.
