<div align="center">
  <img src="https://github.com/RainelDias88/packagePYPI/blob/6a9709f6baaa6ce0051cd0e37ac8a35737fb923d/file/logoraineldataia.png"><br>
</div>

-----------------

## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What is it?](#what-is-it?)
- [Where to get it](#where-to-get-it)
- [Creator](#creator)

# Recommendations with IBM:
Analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like.

## Quick start

Several quick start options are available:

- Clone the repo: `git clone https://github.com/RainelDias88/recommendation-engine-IBM`
- [Install Python](https://www.python.org/downloads/)
- [Install Anaconda](https://www.anaconda.com/products/distribution)

## Status

![Languages](https://img.shields.io/github/languages/count/RainelDias88/recommendation-engine-IBM)
![Top Language](https://img.shields.io/github/languages/top/RainelDias88/recommendation-engine-IBM)

## What is it?

I. Exploratory Data Analysis

Before making recommendations of any kind, I explored the data I am working. I Dived in to see what I could find. 

II. Rank Based Recommendations

To get started in building recommendations, I first found the most popular articles simply based on the most 
interactions. Since there were no ratings for any of the articles, it was easy to assume the articles with the most 
interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on 
what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, I can look at users that are similar in terms
of the items they have interacted with. These items could then be recommended to the similar users. This would be a 
step in the right direction towards more personal recommendations for the users.

IV. 

V. Matrix Factorization

Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I 
builded out a matrix decomposition. Using my decomposition, I got an idea of how well I can predict new articles an 
individual might interact with. I  finally discussed which methods I might use moving forward, and how I might test how
well my recommendations are working for engaging users.

## Where to get it
The source code is currently hosted on GitHub at:
https://github.com/RainelDias88/recommendation-engine-IBM



## Creator

**Felipe Rainel**

- <https://medium.com/@raineldias88>

- <https://www.linkedin.com/in/felipe-rainel/>

- E-mail: raineldias88@gmail.com