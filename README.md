# SentimentalAnalysis

SentimentalAnalysis is a demonstration of a probability-based sentiment analysis algorithm implemented without using any machine learning libraries. The dataset used for this demonstration is very small, consisting of only 5 datapoints. However, the algorithm is designed to work with larger datasets as well.

## Features

- **Probability-Based Algorithm**: Uses a basic probability-based approach for sentiment analysis.
- **No Machine Learning Libraries**: Implemented without the use of any external machine learning libraries.
- **Demonstration Purpose**: Uses a small dataset for demonstration, but scalable to larger datasets.

## Installation

### Prerequisites

- Python 3.6+
- Pip (Python package installer)
- Numpy
- Pandas


## Usage

1. **Prepare Your Dataset**

    Create a CSV file named `Reviews.csv` with the following structure:

    ```csv
    review,label
    "This product is great!",1
    "I am not happy with this item.",0
    "Absolutely fantastic experience.",1
    "The worst purchase I ever made.",0
    "Pretty decent for the price.",1
    ```

    The CSV should have two columns:
    - **review**: Containing the string to be classified.
    - **label**: It has two possible values: `1` for positive and `0` for negative sentiments.

2. **Run the Notebook**

    Open the Jupyter Notebook provided in the repository and run all the cells to see the sentiment analysis in action.

3. **View Results**

    The results of the sentiment analysis will be displayed within the notebook.
