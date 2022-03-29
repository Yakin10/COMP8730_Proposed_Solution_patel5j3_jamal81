# COMP8730_Proposed_Solution_patel5j3_jamal81
# Sentiment Analysis of comments on Indian Cooking Channel
## Business Problem 
Over the years Youtube has emergered as an enthrailing social media platform, with users and channels increasing day by day. Not that you get accessed via goggle if you have a Youtube channel but also a huge target audience to showcase whatever you wanna make a video on. The comment section on every Youtube video or the community section of a channel are the places where user engagement is recorded and provide the youtuber with the know -how of what their community wants? So it gets often enthrailing about finding out what the community need and what's the performance or sucess of each videos and going through a commnet section is overwhelming as their are various types of comments ranging from positive to negatives to neutral and within them the list goes on and on.
Credits: https://medium.com/@stanko.b.prvanovic/7-benefits-of-youtube-for-your-business-3f0344c67c1
## Problem Statement
Our goal is to categorize the comment on YouTube channel so it will be easier for the author to understand what his audience is thinking of his/her content. Our goal here is to classify the comments made on the YouTube Cooking channel. Given a comment c, classify c in any one of Labels in L. L = \{1: Gratitude, 2: About recipe, 3: About Video, 4: Praising, 5: Hybrid, 6: unrelated, 7: Question/Suggestion\}. Let C be collection of comments on a video C = \{c1, c2, c3,.....c$_n$\}. Let there be L for category L = \{1, 2, 3, 4, 5, 6, 7\}.\newline
Classify  $c \in C$ into $l \in L$
## Sources 
* Youtube blog: https://medium.com/@milonimittal/whats-that-youtube-channel-about-973f04c72b4d 
* Library: https://scikit-learn.org/stable/index.html (we use models from this library)
* Research Data: https://zenodo.org/record/2841848 
## Real world/Business Objectives and constraints 
### Objectives:
1. Predict the sentiment of a comment and categorize it.
2. Minimize the difference between predicted and actual sentiment 
### Constraints:
1. Some form of interpretability.
2. 

## Type of Data:
* There are 4900 unique user IDs.
* There are 9800 comments user IDs.
* There are Labels ranging from 1-7
* Label 1- Gratitude
* Label 2- About the recipe
* Label 3- About the video
* Label 4- Praising
* Label 5- Hybrid
* Label 6- Undefined
* Label 7- Suggestions and queries
Start by downloading the project and run "project.ipynb" file in ipython-notebook.

## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.

## Installing
1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/
3. Jupyter
4. Scikit Learn: pip install -U scikit-learn
5. NLTK: pip install --user -U nltk


## Built With
*	ipython-notebook - Python Text Editor
*	sklearn - Machine learning library
*	seaborn, matplotlib.pyplot, - Visualization libraries
*	numpy, scipy- number python library
*	pandas - data handling library
* XGBoost - Used for making regression models

## Authors
*	Yakin Patel & Asim Jamal

 
