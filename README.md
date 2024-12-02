# Fake News Detection

This repository contains a machine learning pipeline to detect fake news using logistic regression and TF-IDF vectorization. The project demonstrates text preprocessing, feature extraction, and model evaluation steps to achieve accurate classification.

## Features
- Text data preprocessing (stopword removal, stemming, and tokenization).
- Feature extraction using TF-IDF Vectorization.
- Classification using Logistic Regression.
- Performance evaluation metrics like accuracy score.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FakeNewsDetection.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The project requires a dataset containing labeled news articles as fake or real. Ensure the dataset is preprocessed or follows a similar structure as expected by the script.

## Usage
1. Open the Jupyter Notebook file:
   ```bash
   jupyter notebook FakeNews.ipynb
   ```
2. Run the cells sequentially to:
   - Load the dataset.
   - Preprocess the data.
   - Train the model.
   - Evaluate performance.

## Dependencies
- pandas
- numpy
- nltk
- scikit-learn

Install dependencies using:
```bash
pip install pandas numpy nltk scikit-learn
```

## Results
The project evaluates the accuracy of the model on a test dataset and provides insights into its performance.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

