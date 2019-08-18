# FAST AI 

## Stop Words

- Stop words are common words which were thought to be of little help in NLP and used to be removed from documents as part of the preprocessing step.
- Lately the trend has been to exclude fewer and fewer stop words, with many algorithms skipping their removal entirely
- Stop word lists from different libraries
    - `from sklearn.feature_extraction import stop_words`
    - `from nltk.corpus import stopwords`
    - `from spacy.lang.en.stop_words import STOP_WORDS`
    - `from gensim.parsing.preprocessing import STOPWORDS`
