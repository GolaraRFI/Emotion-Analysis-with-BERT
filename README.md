## Introduction

This project focuses on Emotion Analysis using BERT (Bidirectional Encoder Representations from Transformers). The goal is to classify emotions in text data accurately by leveraging BERT's advanced capabilities in understanding context and semantics.

## Getting Started
Prerequisites
Ensure you have the following installed:

- Python 3.7+
- PyTorch
- Transformers (Hugging Face)
- Pandas
- Scikit-learn
- Jupyter Notebook

## Data
Raw Data: Place your raw data files in the Dataset/ directory.

Preprocessing: Preprocess the data using the notebook data_preprocessing.ipynb. This will generate processed data saved in the Dataset/ directory. 


## Model Training
Train the BERT model by running the notebook EmotionAnalysis_BERT.ipynb. The trained model will be saved in the emotion-analysis-bert/ directory.

***

## Project Details
Data Preprocessing

The preprocessing pipeline involves:

- Tokenization: Splitting text into tokens.
- Stop Word Removal: Removing common words that do not contribute much meaning.
- Lemmatization: Reducing words to their base forms.


Model Training

The training process includes:

- Loading Preprocessed Data: Use the processed data for training.
- Fine-tuning BERT: Adjust the pre-trained BERT model on the emotion-labeled dataset to improve its performance in emotion analysis.
- Saving the Model: The fine-tuned model is saved for future use.

Model Evaluation

The evaluation process involves:

- Loading the Trained Model: Load the saved BERT model.
- Evaluating on Test Set: Use a test dataset to evaluate the model’s performance.
- Generating Metrics: Produce classification metrics such as accuracy, precision, recall, and F1-score to assess the model's effectiveness.

## Results
The fine-tuned BERT model showed enhanced accuracy in detecting emotions from text, demonstrating its capability in understanding and classifying human emotions accurately.
