# wm_nlp_Module7
Final Project for WM-NLP
This project with extract the text from the article about AI and ChatGPT from CNN. It will apply NLP tehcniques to analyze the article for sentiment and produce a summary of the article from either tokens or lemmas based on a sentence score applied to each sentence and then filtered based on that score. 

The project uses BeautifulSoup to parse the HTML for the text, saves that to a .pkl file. Spacy is used to filter the text, removing white spaces, punctuation, and stop words to get tokens/lemmas of interest. Matplotlib is used to visualize the distribution of sentence scores (the % of tokens/lemmas of interest in the sentence). 
