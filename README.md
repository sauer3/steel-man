## Steel man: a recommender system for opposing viewpoints
*An Antidote to polarization*

### Overview
Social media platforms and their recommender systems have been largely blamed for increasing polarization and pushing people to ideological extremes by algorithmically curating content based on readers interests and leaving out alternative perspectives. This phenomenon has been referred to as echo chambers, filter bubbles, selective exposure, etc.

We need to understand opposing viewpoints, not just to mitigate unhealthy polarization in society but in order to solve problems we must weave together ideas from a range of perspectives. In philosophy a common idea is that to be an effective debator and thinker one must utilize the "steel man" argument. The steel man requires a debater to find the best form of the opposing argument and then argue with this rather than the “straw man” which is a caricature utilized to undermine the opposition. In the words of John Stuart Mill, “He who knows only his own side of the case knows little of that.”

### Goal
My goal for this project is to create an antidote to echo chambers by creating a recommender system that gives the reader an alternative opinion to the content they are currently reading on the same topic. 

### Methods
1. 01-scraping-articles.ipynb
	* This notebook scrapes article content from The New York Times editorial and OpEd sections into a data frame.
2.  02-processing-topic-modeling-clustering.ipynb
	* This notebook includes pre-processing text for each article, topic modeling, k-means clustering, and creating a recommendation system. 
  