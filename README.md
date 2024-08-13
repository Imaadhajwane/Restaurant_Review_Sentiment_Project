# Restaurant Review Sentiment Analysis

This repository contains the implementation of sentiment analysis on a restaurant review dataset. The project involves analyzing customer reviews to determine sentiment, predict ratings, and understand factors influencing opinions using various machine learning models and a web interface.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Tasks and Methods](#tasks-and-methods)
    - [Data Analysis](#data-analysis)
    - [Sentiment Classification](#sentiment-classification)
    - [Data Preprocessing](#data-preprocessing)
- [Results and Evaluation](#results-and-evaluation)
- [Folder Structure](#folder-structure)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [Contact](#contact)

## Project Description
This project focuses on analyzing and classifying restaurant reviews to determine their sentiment. The primary objective is to extract meaningful insights from reviews, predict ratings, and develop a web application to interact with the sentiment analysis model. The project employs various machine learning models to achieve these goals.

![Project Flow](path/to/flowchart.png)  <!-- Replace with the path to your flowchart image -->

## Dataset
**Dataset Name:** Restaurant reviews.csv

**Columns:**
- **Restaurant:** Name of the restaurant where the review was left.
- **Reviewer:** Name of the person who left the review.
- **Review:** Text of the review.
- **Rating:** Rating given by the reviewer.
- **Metadata:** Additional metadata related to the review.
- **Time:** Timestamp of the review.
- **Pictures:** Any pictures attached to the review.

## Tasks and Methods

### Data Analysis
The analysis of the dataset includes:
- Statistical summaries of reviews and ratings.
- Visualizations to understand the distribution of ratings and review sentiments.

### Sentiment Classification
Various machine learning models were implemented to classify the sentiment of reviews:
- **Multinomial Naive Bayes (MultinomialNB)**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNN)**
- **XGBoost**
- **Naive Bayes**

The best-performing model is saved as `model.pkl` for deployment.

### Data Preprocessing
The preprocessing steps involved:
- **Handling Missing Values:** Imputed or removed missing data.
- **Text Processing:** Tokenized, lemmatized, and vectorized text data.
- **Feature Scaling:** Normalized numerical features.
- **Data Splitting:** Divided the data into training and testing sets.

## Results and Evaluation
Each model was evaluated using accuracy, precision, recall, and F1 score. Detailed performance reports and visualizations are included in the `statistics/` directory.

## Folder Structure
├── statistics/ # Contains all analysis and plots
│ └── analysis_plots.png # Example plot
├── restaurant_review/ # Contains all ML model implementations
│ └── model.pkl # Saved model file
├── app.py # Web application integration
├── requirements.txt # Dependencies for the project
└── README.md # Project description and documentation


## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/restaurant-review-sentiment-analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd restaurant-review-sentiment-analysis
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the web application:
    ```bash
    python app.py
    ```

5. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to interact with the sentiment analysis model.

## Dependencies
Make sure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- XGBoost
- Flask

You can install the required packages using the following command:
```bash
pip install -r requirements.txt

## Contact
For any questions or feedback, please contact Imaad Hajwane / www.linkedin.com/in/imaad-hajwane-i280703h
