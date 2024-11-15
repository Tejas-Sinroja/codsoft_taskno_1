# codsoft_taskno_1

# Movie Genre Classification Project

This project aims to classify movies into their respective genres based on their plot summaries. It utilizes machine learning techniques such as TF-IDF vectorization and classification algorithms like Logistic Regression and Naive Bayes to achieve genre classification.

---

## Table of Contents
1. [Introduction](#introduction)  
2. [Dataset Overview](#dataset-overview)  
3. [Data Preprocessing](#data-preprocessing)  
4. [Model Building](#model-building)  
5. [Results](#results)  
6. [Future Scope](#future-scope)  
7. [Dependencies](#dependencies)  
8. [Contributor](#contributor)  

---

## Introduction  
Movie Genre Classification is a common problem in natural language processing. By analyzing a movie's plot, we predict its genre using supervised learning techniques. This project processes a dataset of movie plots, applies text preprocessing, and uses machine learning models to classify genres.

---

## Dataset Overview  
- **Training Dataset:** Contains `54,214` entries with the following columns:  
  - `Title`: The title of the movie.  
  - `Genre`: The genre of the movie (e.g., Drama, Comedy, Thriller).  
  - `Plot`: The plot summary of the movie.  

- **Test Dataset:** Contains movie titles and plots but excludes genres.
- **link of dataset** : https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

---

## Data Preprocessing  
The following steps are performed to preprocess the data:  
1. **Removing Stopwords:** Commonly used words like "and", "the", etc., are removed using NLTK's stopwords list.  
2. **Tokenization:** Movie plots are broken into individual words or tokens.  
3. **TF-IDF Vectorization:** Text data is transformed into numerical vectors using the TF-IDF method.  
4. **Cleaning:** Numbers, symbols, and unnecessary characters are removed.  

---

## Model Building  
The models used in this project include:  
- **Logistic Regression**  
- **Multinomial Naive Bayes**  

Both models are trained on the processed TF-IDF features and the corresponding genres.  

---

## Results  
The performance of the models is evaluated using metrics like:  
- **Accuracy**  
- **Classification Report:** Includes precision, recall, and F1-score for each genre.  

The project aims for a robust accuracy by leveraging TF-IDF vectorization and efficient classifiers.

---

## Future Scope  
This project serves as a baseline for genre classification. Potential future enhancements include:  
1. **Deep Learning Integration:**  
   - Implementing neural networks such as LSTMs, GRUs, or Transformers to capture contextual information in plot summaries.  
2. **Multi-Label Classification:**  
   - Extending the model to handle movies with multiple genres.  
3. **Improved Text Representations:**  
   - Leveraging pre-trained embeddings like GloVe, FastText, or BERT for better text representation.  
4. **Dataset Expansion:**  
   - Incorporating additional metadata such as cast, crew, or user reviews to enrich the feature set.  
5. **Real-Time Prediction System:**  
   - Deploying the model as a web application for real-time movie genre prediction.  

---

## Dependencies  
- Python 3.12  
- pandas  
- numpy  
- nltk  
- sklearn  
- matplotlib  
- seaborn  

---

## Contributor
- **Tejas Sinroja**: Project development, model design, and implementation. 

Feel free to contribute by suggesting improvements or reporting issues via GitHub!

