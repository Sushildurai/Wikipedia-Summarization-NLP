# Wikipedia-Summarization-NLP
Using NLP to summarize the content of a given wikipedia article.

1. Having created a tokenization of the words in the article, using sent_tokenize() from the NLTK package.
2. The frequency of words in the article is stored in a dictionary. To avoid storing, fullstops and comma. stopwords from the nltk.corpus package is used for this.
3.Now sentence score has to be calculated. Wherein each sentence should be weighed with a frequency and stored in a dictionary. A sentence contains maximum of 30 words.
4. heapq package is used to get the largest sentence weight frequency(where sentence weight is key) and prints its corresponding sentence(value) associated with that key.
