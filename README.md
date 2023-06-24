# news-classifier

## Project Description

The goal of this project is to develop a robust Natural Language Processing model by exploring various approaches to text vectorization, such as Bag of Words (BOW), TF-IDF, BERT, Word2Vec (Skipgram & CBOW), and Long Short-Term Memory (LSTM). The project also explores the use of the Latent Dirichlet Allocation (LDA) for topic modelling.

## Repository Contents

The code provided in this repository includes:

- **Data Import**: Reading in the necessary data and conducting preliminary analysis.
- **Data Cleaning**: Cleaning and preprocessing the data using techniques such as lemmatization, removal of stopwords and special characters.
- **Data Vectorization**: Transforming text data into numerical vectors using techniques such as BOW, TF-IDF, BERT, Word2Vec (Skipgram & CBOW).
- **Training and Validation**: Training a variety of machine learning models, including logistic regression and LSTM, on the vectorized data. The models are validated using metrics such as accuracy, precision, and F1 score.
- **Topic Modelling**: Conducting topic modelling using LDA to identify major topics in the dataset.

## Libraries Used

The project uses the following Python libraries:

- pandas
- numpy
- re
- sklearn
- tensorflow
- matplotlib
- nltk
- gensim
- transformers


## Future Work

- Optimize the BERT model for better performance.
- Explore other NLP techniques and models.
- Use a larger and more diverse dataset for better generalization.
