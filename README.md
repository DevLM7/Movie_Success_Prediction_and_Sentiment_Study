# Movie Success Prediction and Sentiment Analysis

This project analyzes movie data to predict box office success and perform sentiment analysis on movie metadata using IMDB and TMDB datasets. The entire analysis is performed within a **Jupyter notebook** environment.

## Project Structure

- `merged_movie_dataset.csv`: Cleaned and merged dataset created by `data_clean_merge.py`
- `movie_analysis.ipynb`: Main Jupyter notebook containing the full analysis pipeline
- `data_clean_merge.py`: Script used to clean and merge the original IMDB and TMDB datasets

## Features

1. **Sentiment Analysis**
   - Uses VADER sentiment analyzer to compute sentiment scores from movie titles and genres
   - Analyzes sentiment distribution across different genres
   - Visualizes sentiment trends

2. **Box Office Success Prediction**
   - Trains regression models to predict movie revenue
   - Uses features such as budget, vote score, runtime, genre, and sentiment
   - Evaluates model performance using R², RMSE, and MAE
   - Displays feature importance using visualizations

## Dependencies

Make sure the following Python libraries are installed in your environment:

- `pandas`
- `numpy`
- `scikit-learn`
- `nltk`
- `vaderSentiment`
- `matplotlib`
- `seaborn`

## Data Sources

- [TMDB Movie Metadata Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [Comprehensive IMDB Dataset](https://www.kaggle.com/datasets/austinwolff/comprehensive-imdb-data)

## Analysis Components

1. **Data Exploration**
   - Statistical summaries and quality checks
   - Correlation heatmaps of key features

2. **Sentiment Analysis**
   - Sentiment score computation using VADER
   - Sentiment breakdown by genre
   - Trend visualization

3. **Success Prediction**
   - Model training using Random Forest Regressor
   - Feature selection and engineering
   - Model evaluation and result visualization

## Results

The analysis provides:
- Insight into sentiment trends across movie genres
- Predictive models for estimating box office success
- Feature importance metrics influencing success
- Clear, visual understanding of sentiment and financial outcomes


The analysis provides:
- Sentiment distribution across different movie genres
- Predictive models for box office success
- Feature importance in determining movie success
- Visualizations of key findings 