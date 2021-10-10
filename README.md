# restaurant-data-analysis
RMDS Lab Data science cometition submission - The Himalayas

# Review_analysis.ipynb
This program loads the two datasets (Q3_competition_detail_dataset.xlsx, Q3_competition_review_dataset.xlsx), cleans them up for the Tableau Word Cloud and exports the 
result in a csv file.

## How to use
* Navigate into the directory containing Review_analysis.ipynb as well as the two datasets, positive.txt and negative.txt.
open Review_analysis.ipynb in an ipython notebook reader and run every cell. This should generate a file named ‘Restaurants_review2.csv’,
which is also present in this repository.

## Dependencies:

* **pandas**
* **seaborn**
* **matplotlib.pyplot**
* **requests, re**
* **nltk**
* **string, itertools**
* **collections.Counter, collections.defaultdict**
* **gensim.corpora.dictionary**
* **gensim.models.tfidfmodel**
* **sklearn**
* **wordcloud**
* **csv**

