# Emotion Classification in Text Samples

This repository contains a Jupyter Notebook implementing a machine learning pipeline to classify emotions in text samples. The project covers the following key components:

## Objectives
1. **Loading and Preprocessing**: Clean and prepare text data by removing noise and irrelevant features.
2. **Feature Extraction**: Transform text data into numerical representations using `TfidfVectorizer`.
3. **Model Development**: Train and evaluate machine learning models:
   - Naive Bayes (MultinomialNB)
   - Support Vector Machine (SVM with linear kernel)
4. **Model Comparison**: Compare the models using metrics such as accuracy and F1-score.

## Project Structure
- **Notebook**: `enhanced_nlp_dataset.ipynb` contains all the code and explanations for the project.
- **Dataset**: Ensure the `nlp_dataset.csv` file is available in the same directory as the notebook.

## How to Use
1. Clone the repository.
2. Ensure the required Python libraries are installed. You can use the following command to install dependencies:
   ```bash
   pip install pandas scikit-learn
