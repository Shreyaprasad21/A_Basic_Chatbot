# CHATBOT
This project has been developed as a personal project where I utilized natural language processing and sentiment analysis to create a robust chatbot for answering general queries. Working on this project allowed me to enhance my skills in natural language processing and sentiment analysis in a self-paced environment.
  
## Contents
1. [Introduction](#introduction)
2. [Features](#features)  
3. [Dependencies](#dependencies)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Deployment](#deployment)
7. [Notes](#notes)

## Introduction
The General Query Chatbot is designed to assist users by providing automated responses to a variety of common queries. The chatbot leverages natural language processing (NLP) techniques to understand and respond to user queries effectively. The system aims to enhance user experience by providing quick and accurate information about various topics. The project integrates sentiment analysis to gauge user sentiment and visualize word clouds to understand the frequent topics of queries and responses. The application is implemented in Python and can be extended to cover a wider range of queries.

## Features
- **Automated Responses:** Provides quick and accurate responses to common queries.
- **Sentiment Analysis:** Uses VADER sentiment analysis to evaluate the sentiment of user queries.
- **Word Cloud Visualization:** Generates word clouds to visualize frequent words in user queries and responses.
- **TF-IDF Vectorization:** Implements TF-IDF vectorization for text data.
- **Chat History:** Maintains a chat history and displays relevant information.
- **User Greeting:** Greets users upon interaction.
- **Confidence Scores:** Provides confidence scores for the relevance of responses.

## Dependencies
- Python 3.9 or higher
- pandas
- nltk
- matplotlib
- wordcloud
- scikit-learn
- vaderSentiment

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/Shreyaprasad21/A_Basic_Chatbot.git

2. Run the chatbot script:
      ```sh
   Chatbot.ipynb

3. Follow the prompts to interact with the chatbot. Type 'exit' to end the conversation.

## File Structure
- `Chatbot.ipynb`: Main script implementing the chatbot functionality.
- `dialogs.txt`: Dataset containing pre-stored general questions and responses.
- `nlp_utils.py`: Utility functions for text normalization.
- `contractions.py`: Helper functions for handling contractions in text.
- `README.md`: Instructions and information about the project.
- `LICENSE`: License information.

## Deployment

1. Start the chatbot by running:
  ```
  python Chatbot.ipynb
  ```

2. Interact with the chatbot in the console. Type 'exit' to end the conversation.

## Notes
- The project was developed using Python, with the main chatbot functionality implemented in `Chatbot.ipynb`.
- `nlp_utils.py` contains helper functions for text normalization.
- The dataset (`dialogs.txt`) is provided and contains sample questions and responses.
- Sentiment analysis and word cloud visualization are integrated into the chatbot.
- TF-IDF vectorization is used to match user queries with stored questions.
- The project can be extended to cover more queries and provide more detailed responses.
