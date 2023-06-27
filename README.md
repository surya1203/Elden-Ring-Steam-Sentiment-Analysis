# Elden Ring Steam Review Sentiment Analysis

## Introduction

This project focuses on sentiment analysis of Steam game reviews for the game "Elden Ring". The goal is to analyze the sentiment of the reviews (recommended or not recommended) using natural language processing techniques and machine learning algorithms. The dataset used for this project is sourced from Steam and contains various attributes such as the review text, voting information, and user details.

## Requirements

To run this project, you need to install the following dependencies:

- transformers
- nlpaug
- imblearn
- pandas
- scikit-learn
- tensorflow
- seaborn
- matplotlib
- nltk

You can install these dependencies using pip:

```
!pip install transformers
!pip install nlpaug
```

## Installation

To install and run this project, please follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/repo-name.git
```

2. Change directory to the project folder:

```
cd repo-name
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Download the dataset "elden_ring_steam_reviews.csv" and place it in the project folder.

## How to Run the Code

1. Open the project folder in your preferred code editor or Jupyter Notebook.

2. Navigate to the main script file (e.g., "elden_ring_sentiment_analysis.py" or "Elden_Ring_Sentiment_Analysis.ipynb").

3. Run the python script or open the notebook on Google Colab to execute the code.

## Results

The project initially sets a baseline using DistilBERT without balancing the data. The baseline model achieved an F1 score of 97% for positive reviews and 53% for negative reviews. However, to address the class imbalance issue, the project performs data augmentation using the "nlpaug" library, resulting in an improved F1 score of 71% for negative reviews.

## Conclusion

The project demonstrates the application of natural language processing techniques and machine learning algorithms for sentiment analysis of game reviews. By addressing the class imbalance issue through data augmentation, the performance of the model improved significantly. The results highlight the importance of handling class imbalance to achieve better accuracy and F1 scores in sentiment analysis tasks.
