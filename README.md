![FIFA Logo](/images/fifa.png)

# Dataiku's Conundrum Challenge on FIFA Dataset.

# Introduction
If there's one thing similar about an interesting dataset and a good football's match, is that they're all keeping everyone's safe at home during this time of the pandemic. And in all honesty, I'm no data scientist nor a dev guy. I just recently got myself exposed to an ML/AI in general, while Dataiku in particular, somewhere a little over then 3 months ago, so here's my take to this conundrum's challenge.

# Installation
On this repository, you may find my personal projects related to Machine Learning, EDA, Python Jupyter Notebook and couple of Visualization based on the Dataiku Platform exported standard files. Most of the datasets I've been working with, downloaded from Conundrum site. Installation pretty straight forward. Simply download the whole set as a single project and as a ZIP file, everything have been flattened out with plain text files, and no SQL dump was involved, so there wouldn't be any missing system dependencies issue. Simply imported the downloaded Zip file to your working project.

# Data Flow
And since the challenge is not to 'predict' anything, rather to group/cluster the player's skillsets in reflect to their wages rate. Here's what my current flow would look like, and don't bother much on the 2 additional datasets, as they're merely exported from the existing model, so that I may explore them further.
![main-flow.png](/images/main-flow.png)


# Prepare Recipes
And here's how I go about on the prepare recipes, nothing out of the ordinary. Just converting *categorical* to *numerical* values with one-hot encoding and filling up the *'NaN'* with median values, while grouping them to have better clarity, if ever I need to go back and revise anything.

# Modeling & Training 
While on modeling/training steps, I choose the '_Interactive Clustering_' which in return, delivered me a sufficient scoring value.

# Clustering Classification
On to the clustering variables name, I simply identify them in the grading manner, starting from '_Grading A_', as the most top-knot performer, all the way down to the least performing one marked with '_Grading E_'.

# Cluster Plot
And here's how my _cluster plot_ would look like, obviously the better the grade, the least volume of players getting included in them.

**Acceleration x Wage**


**Sliding Tackle x Wage**

# Variables Significant Level
And for sure those who sits at the 'Grading A' level would stand above the average threshold (though, that's not always the case with other variables).

# Value Proposition
- And coming back again to the initial question,  _"creating a flow that outputs a value proposition in term of their wages"_. I think I didn't include the players name and their nationalities in my modeling for a couple of reasons. In my opinions, those two variables are just too subjective to get included. In a sense that you could be a top-knot player, regardless of what your 'Names' would sound like, and of course your 'Nationalities'.

So I've done the DSS flow diagram, while the followings are my list of 'value proposition' that contributed of being one '_Grading-A_' player in the field.

**Top 5 Values Proposition**



**Top 5 Values Proposition By Distribution.**


**Top 5 Values Proposition By Grade.**



Been enjoying exploring this dataset for sure, and certainly it was fun doing it, stays safe everyone! 😊

# Disclaimer
And please remember, as this is only a weekend pet project, which I'm doing them for my personal interest only.