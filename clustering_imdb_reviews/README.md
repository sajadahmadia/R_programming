
# Text clustering in R
In this project, we will build clustering models on text data, specifically on reviews from the Internet Movie Database (IMDB).

* IMDB reviews is a text dataset available in the text2vec package.
* This dataset consists of 5000 movie reviews specifically selected for sentiment analysis.
* No single movie has more than 30 reviews.
* The sentiment of the reviews is also given as a binary variable, i.e. an IMDB rating < 5 results in a sentiment score of 0, and a rating >=7 results in a sentiment score of 1.

## Procces
1. At first, we apply a text pre-processing technique to raw test data.
2. We tokenize each review into words.
3. Use the Word2vec embeddings of words as the vectorized representation of each review.
4. Apply the K-Means and Gaussian mixture models to cluster reviews.
5. Measure the performance of each clustering method using Silhouette score (as our internal metric) and chi-squred(as our external metric).
6. Choose the best clustering method.

## Installation

Many times in R, you need to install some packages before you can run a code. Make sure you have installed the following packages before running the code:

* text2vec
* wordcloud
* magrittr
* tidyverse
* tidytext
* purrr
* mclust
* fpc
* lsa

You can install a new package using:
`````
install.packages(package_name_with_double_quotation)
`````
    
## Author

- [@sajadahmadia](https://github.com/sajadahmadia)

## Notice
To see the code and visualizations, it's better to download the HTML report of this project(file named [text_clustering.html](https://github.com/sajadahmadia/R_programming/blob/main/clustering_imdb_reviews/text_clustering.html), and then run it through your browser. 
