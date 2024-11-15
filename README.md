# codsoft_taskno_1
This is the machine learning project of movie genre classification


# Movie Genre Prediction

## Overview
The **Movie Genre Prediction** project aims to predict the genre of a movie based on its description and poster. This system leverages natural language processing (NLP) and computer vision (CV) techniques to analyze textual and visual features. It provides a robust tool for automatic classification, simplifying the process for movie enthusiasts and content managers.

## Objectives
- Extract and process features from movie posters using computer vision techniques.
- Process movie descriptions using NLP for semantic understanding.
- Combine extracted features to achieve accurate predictions.

## Workflow
1. **Data Collection**: Gathered movie descriptions and posters.
   - **link of dataset** : https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb
3. **Preprocessing**:
   - **Posters**: Resized and normalized for consistent input.
   - **Descriptions**: Tokenized, cleaned, and converted into word embeddings.
4. **Model Development**:
   - Created separate sub-models for poster and description processing.
   - Merged features from both modalities.
   - Final prediction using a fully connected neural network.
5. **Evaluation**: Validated on test data to measure accuracy and reliability.

## Challenges
- Limited labeled data for training.
- Balancing feature contributions from visual and textual inputs.
- Designing an efficient architecture to handle multi-modal data.

 ## Future Enhancements
- **Dataset Expansion**: Incorporate larger and more diverse datasets for better generalization.
- **Multi-label Prediction**: Enable the system to predict multiple genres for a single movie.
- **Fine-tuning Models**: Apply transfer learning techniques with pre-trained models for better feature extraction from posters and descriptions.
- **User Interface**: Develop a web or mobile app for real-time genre prediction based on user-uploaded movie data.
- **Explainability**: Integrate visualization tools to explain how the model reaches its predictions.

## Contributor
- **Tejas Sinroja**: Project development, model design, and implementation. 

Feel free to contribute by suggesting improvements or reporting issues via GitHub!

