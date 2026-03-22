# Academic-Paper-Similarity-Checker


A machine learning project that identifies and retrieves similar 
research papers based on textual content.

## Dataset
- NIPS Research Papers (1987–2017)
- 7,241 papers from Kaggle

## Tech Stack
- Python, Google Colab
- pandas, scikit-learn, NLTK
- matplotlib, seaborn

## Features
- TF-IDF Vectorization (5000 features, bigrams)
- Cosine Similarity Matrix (7241 × 7241)
- Top-5 similar paper retrieval
- EDA visualizations (bar chart, word frequency, histogram)
- Cosine Similarity Heatmap

## Usage
1. Upload papers.csv dataset
2. Run all cells top to bottom
3. Query: get_similar_papers("neural network")



