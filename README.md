# Kaggle's  StumbleUpon Challenge on Dataiku!
![stumbleUpon Logo](/images/stumbleupon.jpg)

# Brief Descriptions
`StumbleUpon` is a user-curated web content discovery engine that recommends relevant, high quality pages and media to its users, based on their interests. While some pages we recommend, such as news articles or seasonal recipes, are only relevant for a short period of time, others maintain a timeless quality and can be recommended to users long after they are discovered. In other words, pages can either be classified as `"ephemeral"` or `"evergreen"`. The ratings we get from our community give us strong signals that a page may no longer be relevant - but what if we could make this distinction ahead of time? A high quality prediction of `"ephemeral"` or `"evergreen"` would greatly improve a recommendation system like ours.

Many people know `evergreen` content when they see it, but can an algorithm make the same determination without human intuition? Your mission is to build a classifier which will evaluate a large set of URLs and label them as either evergreen or ephemeral. Can you out-class(ify) StumbleUpon? As an added incentive to the prize, a strong performance in this competition may lead to a career-launching internship at one of the best places to work in San Francisco.

# Installation
On this repository, you may find my personal projects related to Machine Learning, EDA, Python Jupyter Notebook and couple of Visualization based on the Dataiku Platform exported standard files. Most of the datasets I've been working with, downloaded from Kaggle. Installation pretty straight forward. Simply download the whole set as a single project and as a ZIP files, everything have been flattened out with plain text files, and no SQL dump was involved, so there wouldn't be any missing system dependencies issue. Simply imported the downloaded Zip file to your working project.


# Data Dictionary

**There are two components to the data provided for this challenge:**

The first component is two files:  `train.tsv`  and  `test.tsv`. Each is a tab-delimited text file containing the fields outlined below for 10,566 urls total. Fields for which no data is available are indicated with a question mark.

-   `train.tsv` is the training set and contains 7,395 urls. Binary evergreen labels (either evergreen (1) or non-evergreen (0)) are provided for this set.
-   `test.tsv` is the test/evaluation set and contains 3,171 urls.

The second component is  `raw_content.zip`, a zip file containing the raw content for each url, as seen by StumbleUpon's crawler. Each url's raw content is stored in a tab-delimited text file, named with the `urlid` as indicated in `train.tsv` and `test.tsv`.

The following table includes field descriptions for `train.tsv` and `test.tsv`: By default, the initial dataset coming from [Kaggle's]([https://www.kaggle.com/c/stumbleupon/data](https://www.kaggle.com/c/stumbleupon/data)) challenge page would give you the above dataset features at hand. But we'll try to optimize them to something much more Machine Learning friendly looking dataset. 

# Jupyter Notebooks

- [Correlations analysis on test_prepared_scored (admin).ipynb](https://github.com/leonism/Dataiku-StumbleUpon/blob/master/ipython_notebooks/Correlations%20analysis%20on%20test_prepared_scored%20(admin).ipynb) 
- [PCA on test_prepared_scored (admin).ipynb](https://github.com/leonism/Dataiku-StumbleUpon/blob/master/ipython_notebooks/PCA%20on%20test_prepared_scored%20(admin).ipynb) 
- [[Predict label in train_prepared.ipynb](https://github.com/leonism/Dataiku-StumbleUpon/blob/master/ipython_notebooks/Predict%20label%20in%20train_prepared.ipynb "Predict label in train_prepared.ipynb")](https://github.com/leonism/Dataiku-StumbleUpon/blob/master/ipython_notebooks/Predict%20label%20in%20train_prepared.ipynb) 
- [Statistics and tests on a single population on test_prepared_scored (admin).ipynb](https://github.com/leonism/Dataiku-StumbleUpon/blob/master/ipython_notebooks/Statistics%20and%20tests%20on%20a%20single%20population%20on%20test_prepared_scored%20(admin).ipynb)

# Disclaimer
And please remember, as this is only a weekend pet project, which I'm doing them for my personal interest only.