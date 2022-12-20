# ZENITH
a chatbot that can answer questions and provide information on a wide range of topics
The script reads in a dataset from a file called "WikiQA-train.tsv" and performs some data exploration and cleaning on it. It then writes the data from the dataset to a new file called "text2.txt".

After that, the script downloads some libraries from the Natural Language Toolkit (nltk) package, including punkt, wordnet, and omw-1.4. These libraries are used for tasks such as sentence boundary detection and word sense disambiguation.

The script then defines some functions for tokenization, lemmatization, and normalization of text data. It also defines a function for greeting the user and a function for generating a response to the user's input.

Finally, the script runs a loop that prompts the user for input and generates a response based on the user's input, using the functions defined earlier.
