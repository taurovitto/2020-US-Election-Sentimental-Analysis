# 2020-US-Election-Sentimental-Analysis

This group projet was done during the Big Data and Databases course at Bocconi University using Knime, a visual programming platform (with some nodes that allowed to program in python).

Team: Vittorio Costa (New York University - Bocconi University), Pietro Campanella (Bocconi University), Roberto Ceraolo (École polytechnique fédérale de Lausanne - Bocconi University), and Alessandro Fedel (Massachusetts Institute of Technology - Bocconi University).

We found twitter data that mentioned either Donald Trump or Joe Biden, the two leading candidates running for US presidency, and performed sentimental analysis on the data. After having cleaned and filtered Twitter API data, we assigned to each word in a tweet a sentiment (positive, negative, neutral) using the lexicon method and calculated the average sentiment of each tweet. Then, the data was regressed with a Random Forest Classifier achieving 80% accuracy for the sentiment label created (i.e. sentiment score for each tweet). By trying to predict elections with Twitter data, we came to two conclusions:

1. People use Twitter more frequently to externalize negative rather than positive sentiment
2. The prediction gives Biden a win in almost every state (biased), so that we tend to conclude that active Twitter users are more prone to support the Democratic Party

For more details abpout the study, check out the report pdf file.
