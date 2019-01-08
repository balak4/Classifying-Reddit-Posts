# Classifying Reddit Posts

## Overview <br>
Given a Reddit post from one of two subreddits, can we build a model to _accurately_ classify which subreddit the post belongs to? The short answer is yes (with NLP of course)! Check out the jupyter notebook "Classifying_Subreddit_Posts_BK.ipynb" for the gory details on how I've tackled this problem, and the presentation titled "Reddit Post Classification 2018-12-21.pptx" for a quick summary of the methodology and results. 

## Tl;DR <br>
I tested several classifiers (Logistic Regression, RandomForest, Naive-Bayes, and Support Vector Classifier) with NLP on two sets of subreddits: 
- r/science vs r/technology <br>
- r/sports vs r/fitness <br> <br>

Overall, the Naive-Bayes classifier performed the best. It achieved a high accuracy (greater than 90%) on test data and ran faster than the other classifiers tested. As one would expect, classification accuracy improves as the subreddits become more "distinct" (i.e. use of common language between subreddits decreases).
