# test


Our project is chatbot NLU:Chatbots that use machine learning are chatbots that can learn and become better over time. 

the first step to build a chatbot is to extract data from StackOverflow to obtain dataset (json file) then we will apply NLP to the datasets after that we need TF-idf and random forest to improve the accuracy and to predict the response for dataset

The dependencies:
to run this program you need first:
-install python 3.7.6
-install anaconda
-configure the library: NLTK, BeautifulSoup, pandas, NumPy, scipy, matplotlib

Step:
after installing python and downloading the file, open the code in the jupyter notebook and execute it with <shift + enter>.

result:
The file extract concerns the extraction of the StackOverflow dataset how we give ourselves 10,000 questions in a json file named test.json.
The NLP_Dataset file to learn and capture knowledge related to NLP, it includes (remove punctuation, tokenize, remove stop words and lemmatization).
the final file is TF_IDF, this file behaves as the first step to read the dataset, applies the NLP functions then count the frequencies of the terms and convert a collection of documents into a matrix of functionalities and improve predictive precision and control over-adjustment.



