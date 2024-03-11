# Sentiment-Analysis-Using-NLP-For-Game-Review-Data


"This project aims to develop a sentiment analysis pipeline for analyzing text sentiment in reviews. Leveraging Python libraries such as NLTK and Pandas, we preprocess the review data by converting it to lowercase, removing punctuation, and tokenizing it using both the Treebank and casual tokenizers to accommodate various text formats. We further apply stemming and lemmatization techniques to reduce words to their root forms and obtain a more accurate representation of the text. Using SentiWordNet, we compute sentiment scores for each review, categorizing them as positive, negative, or neutral based on the overall sentiment expressed. The project also includes a user input feature, allowing users to input their own review text interactively and obtain sentiment analysis results in real-time."


# Steps Involved Are

1. Data Loading and Preprocessing:

The code starts by importing necessary libraries and loading a CSV file (small_corpus.csv) containing reviews using Pandas.
It preprocesses the review text by converting it to lowercase, removing punctuation, and tokenizing it using the Treebank tokenizer.

2. Tokenization:

Two tokenization techniques are applied: Treebank tokenizer (tb_tokenizer) and casual tokenizer (casual_tokenize). Treebank tokenizer is a standard tokenizer that splits text into words based on spaces and punctuation, while casual tokenizer is more relaxed and can handle informal language and social media texts.

3. Stemming:

Stemming is performed using the Porter Stemmer to reduce words to their root form.

4. Lemmatization:

Lemmatization is applied using WordNet Lemmatizer. Lemmatization reduces words to their base or dictionary form, considering the context and part-of-speech of each word.

5. Sentiment Analysis:

Sentiment scores are computed for each review using SentiWordNet. The sentiment score represents the overall sentiment of the review, with positive scores indicating positive sentiment, negative scores indicating negative sentiment, and neutral scores indicating a lack of sentiment.

6. User Input Feature:

The code allows users to input their own review text interactively. They can input any text, and the code will analyze its sentiment using the sentiment analysis pipeline described above.
Users can input reviews one after another until they decide to exit by typing 'exit'.
