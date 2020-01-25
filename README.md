# Rural Social Movements Debate

####################################

This repository contains the codes relate to a project where I analyzed 135 articles about rural social movement published in 
prestigious Brazilian journals. I used Python to get, clean, and analyze the data, as well as modules as pandas, spacy, nltk, 
itertools, gensim, and so on.

# Main research question:

What are the main problems and theories about rural social movements in Brazil?

# Work steps:

1. I scraped from Scielo platform the urls, titles, authors, sources, years, journals, abstracts, and references of the articles with words (and their plurals as 'movimento', 'conflito', and 'ativismo', that were published, between 2000 and 2019, in social science journals.

2. I selected all abstracts with the following words: 'rura', 'campo', 'agr', and 'terra'. Then I read all titles/abstracts and selected the articles about rural social movements. I decided select the articles manually, instead of automatically, because we noticed that the key words were not intuitive.

3. After select our corpus, I cleaned and prepared the data, removing the punctuation, the stop words, treating the synonyms, and so on.

4. I performed the EDA, checking the vocabulary and counting the frequency of words.

5. I performed topic modeling analysis, trying to check the main subjects treated in articles.

