# Fake News Detection using DistilBERT + Deep CNN

## Overview

This project presents a Fake News Detection system developed using Natural Language Processing (NLP) and Deep Learning techniques. It leverages DistilBERT for contextual text embeddings and a Deep Convolutional Neural Network (DCNN) for binary classification of news articles as **Real** or **Fake**.

## Features

- Data preprocessing and text cleaning
- HTML and URL removal
- DistilBERT tokenizer
- Custom PyTorch Dataset
- DistilBERT + Deep CNN architecture
- Model training and evaluation
- Confusion Matrix
- Classification Report
- ROC Curve
- Precision-Recall Curve
- Matthews Correlation Coefficient (MCC)

## Dataset

The project was experimented on multiple fake news datasets, including:

- WELFake Dataset
- LIAR Dataset
- ISOT Fake News Dataset

> Dataset files are not included in this repository due to their size.

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Pandas
- NumPy
- Scikit-learn
- BeautifulSoup
- Matplotlib

## Project Structure

```
fake-news-detection-distilbert-dcnn/
│
├── notebooks/
│   ├── welfake.ipynb
│   ├── liar.ipynb
│   └── isot.ipynb
│
├── README.md
├── requirements.txt
```

## Results

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Precision-Recall Curve
- Matthews Correlation Coefficient

## Future Improvements

- Deploy the model using Flask or FastAPI
- Develop a web interface for real-time prediction
- Integrate additional datasets
- Optimize inference time

## Author

Firdous Anjum