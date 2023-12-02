# Chatbot using Natural Language Processing

This repository contains a Python implementation of a chatbot leveraging natural language processing techniques. The code utilizes the NLTK library for sentiment analysis and TF-IDF vectorization for word embedding. The chatbot reads a dataset from "dialogs.txt" into a Pandas DataFrame, explores the data, performs data visualization, and normalizes text by removing special characters and converting to lowercase. The chatbot then identifies important sentences and provides top positive, negative, and neutral sentences based on sentiment analysis. Additionally, the code includes a chatbot functionality using cosine similarity to match user queries with the most similar questions in the dataset, offering responses with confidence scores and sentiment analysis results. Users can interact with the chatbot through a simple loop, entering queries until choosing to exit.

## Instructions for Use:

1. Clone the repository to your local machine.
2. Ensure Python and required libraries are installed (NLTK, Pandas, Matplotlib, WordCloud, scikit-learn).
3. Run the code using a Python environment.
4. Enter queries when prompted, and the chatbot will provide responses.

## File Descriptions:

- `chatbot.py`: Main Python script implementing the chatbot functionality.
- `dialogs.txt`: Input dataset containing question-response pairs.
- `nlp_utils.py`: Utility script with text normalization functions.
- `README.md`: Documentation providing an overview of the chatbot and instructions for use.

Feel free to explore, modify, and enhance the code as needed for your applications.
