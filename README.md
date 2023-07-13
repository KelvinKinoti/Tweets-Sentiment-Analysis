# Tweets-Sentiment-Analysis
The purpose of the project is to perform sentiment analysis and explore the frequency and relationships of words in a text dataset. The project involves loading libraries such as tidytext, ggplot2, dplyr, tidyr, ggraph, and igraph.

The data is loaded from two text files: "tweet.txt" and "part-m-00000.txt". The "tidytext" library is used to tokenize the text data into individual words, removing stop words and conducting sentiment analysis. The sentiment analysis is performed using lexicons such as AFINN, BING, and NRC, which categorize words into positive, negative, and other emotional categories.

The word frequency of the text data is analyzed, and word clouds are created to visualize the most frequently occurring words. Bi-grams (sequences of two words) are also generated, and their frequency is analyzed. Common words and stop words are removed to focus on meaningful word associations.

Finally, a word network is constructed using the remaining bi-grams, showing the relationships between words based on their co-occurrence in the text data. The resulting network graph provides insights into word associations and connections within the dataset.

Overall, the project aims to analyze the sentiment and explore the frequency and relationships of words in the given text dataset, allowing for a deeper understanding of the text's content and characteristics.
