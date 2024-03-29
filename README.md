# Topic Modeling and Sentiment Analysis on IMDb Reviews

This project focuses on analyzing IMDb reviews to perform sentiment classification and uncover latent topics within the texts. Utilizing the Large Movie Review Dataset, this study applies advanced natural language processing techniques to explore the intricacies of movie review sentiment and thematic elements.

## Project Overview

### Goals
- To classify sentiments of IMDb reviews as either positive or negative.
- To identify and analyze topics within the reviews using topic modeling techniques.

### Dataset
The analysis utilizes the Large Movie Review Dataset v1.0, which includes 25,000 highly polarized movie reviews for both training and testing. Reviews are divided into positive and negative categories, providing a comprehensive base for sentiment analysis.

### Methodology

#### Preprocessing
- Lowercasing and cleaning text to remove noise such as URLs.
- Tokenization, removal of numbers, and exclusion of punctuation and stopwords.
- Lemmatization to bring words to their base form.
- Compilation of clean reviews into a structured DataFrame, saved for analysis.

#### Data Exploration and Visualization
- Identification of popular tokens and adjectives in reviews, providing insights into common linguistic patterns.
- Use of word clouds to visualize frequent words in positive and negative reviews, highlighting dominant sentiments.

#### Topic Modeling
- Implementation of N-gram analysis to explore word sequences.
- Application of Latent Dirichlet Allocation (LDA) to identify and visualize prevalent topics across reviews.

#### Sentiment Classification
- Application of Bag of Words (BoW) and sequence models to classify review sentiments.
- Evaluation of models based on accuracy, precision, recall, and F1-score, with detailed analysis of model performance.

## Results
The project successfully identified key topics within IMDb reviews and classified sentiments with notable accuracy. The Two Words (Bigrams) with TF-IDF Encoding model emerged as highly effective, achieving an accuracy of 89.04% and demonstrating the value of nuanced language representation in sentiment analysis.

## Tools and Libraries Used
- Python for data processing and analysis.
- Natural Language Toolkit (NLTK) and scikit-learn for NLP tasks.
- TensorFlow and Keras for building and training neural network models.

## Conclusion
This study underscores the efficacy of NLP techniques in extracting meaningful insights from textual data. The exploration of IMDb reviews through topic modeling and sentiment analysis reveals the depth of sentiment and thematic content, providing valuable perspectives on movie critique dynamics.

For further details on methodologies, findings, and code implementations, please refer to the complete project documentation.

