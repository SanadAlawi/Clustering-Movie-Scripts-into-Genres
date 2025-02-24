# Clustering Movie Scripts into Genres (Text)

## Overview
This project clusters movie scripts based on their textual content using NLP and machine learning techniques. It involves data preprocessing, text vectorization, clustering using K-Means, and visualization.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

## Steps
1. **Load and Preprocess Data**
    - Load dataset (`IMDB Dataset.csv`)
    - Remove duplicates
    - Clean text (lowercasing, removing punctuation, stopwords)
2. **Convert Text to Numerical Features**
    - Use TF-IDF vectorization
3. **Apply Clustering Algorithms**
    - Determine optimal clusters using the Elbow Method
    - Apply K-Means clustering
    - Evaluate using Silhouette Score
    - Reduce dimensions using PCA for visualization

## Running the Code
1. Install required libraries:
    ```
    pip install pandas matplotlib seaborn nltk scikit-learn
    ```
2. Download NLTK stopwords:
    ```
    import nltk
    nltk.download('stopwords')
    nltk.download('punkt')
    ```
