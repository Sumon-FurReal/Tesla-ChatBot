# Tesla-ChatBot
"Wall-E" is a Tesla chatbot that uses NLP, TF-IDF, and a text corpus to answer FAQs about Tesla.

This Python code is a simple chatbot named "Wall-E" designed to answer frequently asked questions (FAQs) about Tesla. The chatbot uses Natural Language Processing (NLP) techniques and a Term Frequency-Inverse Document Frequency (TF-IDF) algorithm to provide appropriate responses to user input.

The code starts by importing necessary libraries such as NumPy, NLTK, and string. It then imports a text corpus file named "TeslaCorpus.txt" and preprocesses the data using functions such as lowering the text case, tokenizing the text, removing punctuation, and lemmatizing the words.

The code then defines a set of input greetings and corresponding responses to handle the user's initial input. If the user does not input a greeting, the code extracts features from the text using TF-IDF and calculates the similarity between the user input and the text corpus. The code then returns the most similar sentence as the chatbot's response.

The code also includes start and end protocols for the chatbot. Once the chatbot is initiated, it greets the user and waits for the user input. If the user inputs "bye," the chatbot responds with a goodbye message and terminates the conversation.

To run the code, make sure to have the necessary libraries installed and have a text corpus file named "TeslaCorpus.txt" in the same directory as the Python file. Run the code and initiate a conversation with "Wall-E" by typing in any question or statement related to Tesla.
