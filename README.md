# YouTube Video Popularity Prediction using Machine Learning

This project explores the factors influencing the popularity of YouTube videos using regression-based machine learning models. By analysing video metadata such as views, likes, dislikes, and comment counts, we aim to predict video popularity and evaluate model performance.

## Project Overview

- ***Goal***: Predict whether a video will be popular based on features such as views, likes, comments, dislikes.
- ***Approach***: Train and evaluate multiple regression models to identify the most accurate predictor.
- ***Dataset***: A custom YouTube dataset including both numerical and categorical video features.

## Models Used

- Random Forest Regressor
- Decision Tree Regressor
- Linear Regression
  
**Each model was evaluated using:**
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

## Dataset

The original dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset), containing extensive metadata on trending YouTube videos across multiple countries.

For this project:
- **File**: `MX_youtube_trending_data.csv`
- **Contents**: A single CSV file with cleaned and selected features for regression and classification analysis.

### Usage Instructions
1. Unzip `dataset.zip` in the project directory.
2. Load the CSV file (`MX_youtube_trending_data.csv`) into the notebook for preprocessing and modelling steps.

> ⚠️ **Note**: The original Kaggle dataset contains additional countries, features, and records that were not used in this project to keep the scope focused and relevant.



## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/fatmabusratilki/YouTube-popularity-analysis-ML.git
2. Open the notebook `main.ipynb` in Jupyter or Colab.
3. Run all cells to preprocess data, train models, and view results.

## Contributors 
- Fatma Büşra Tilki
- Sümeyye Korkmaz
- Aslı Yılmaz

## Acknowledgment
This project was developed as part of the ***Turkcell Women Writing the Future Artificial Intelligence Programme***, during the completion of ***Module 1***.



