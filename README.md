# Automatic Text Summarization using Natural Language Processing

This Python script implements an automatic story summarization system based on user queries. It utilizes Natural Language Processing (NLP) techniques to analyze and summarize text from three different stories. The summarization is performed by scoring each sentence based on its relevance to the user query and the frequency of words in the sentence.

## Features:

- **Preprocessing**: The script preprocesses the text by tokenizing, removing stop words, stemming, and calculating word frequencies.
- **User Query Processing**: It prompts the user to enter a query, preprocesses the query, and calculates similarity scores between query words and words in the sentences.
- **Scoring**: Sentences are scored based on a combination of term frequency-inverse document frequency (TF-IDF) and query similarity.
- **Summarization**: The script generates a summary for each story by selecting sentences with scores above a certain threshold.

## Usage:

1. Ensure Python and NLTK (Natural Language Toolkit) are installed.
2. Place the text files containing the stories in the same directory as the script.
3. Run the script and follow the prompts to enter a query.
4. View the generated summaries for each story.

## Code Improvements:

- **Readability**: Meaningful variable names, comments, and modular functions improve code readability.
- **Efficiency**: Optimized code for faster execution, especially in scoring sentences.
- **Error Handling**: Incorporated error handling mechanisms, such as file I/O errors.
- **Documentation**: Added comments and a README file to provide context and usage instructions.
