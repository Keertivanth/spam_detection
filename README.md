# Spam Detection using Machine Learning

## Project Overview
This project classifies SMS messages as **Spam** or **Ham (Not Spam)** using Machine Learning and Natural Language Processing (NLP).

## Dataset
The dataset contains labeled SMS messages:
- Spam
- Ham

Total Records: 5572

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Joblib

## Project Workflow

1. Load Dataset
2. Clean and Preprocess Text
3. Convert Text into Numerical Features using TF-IDF
4. Split Data into Training and Testing Sets
5. Train Logistic Regression Model
6. Evaluate Model Performance
7. Save Model Pipeline for Future Predictions

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score

## Project Structure

```
spam_detection/
│
├── Spam_Detection.ipynb
├── spam mail(1).csv
├── spam_detection_pipeline.pkl
├── requirements.txt
└── README.md
```

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
jupyter notebook Spam_Detection.ipynb
```

## Sample Prediction

Input:

```text
Congratulations! You have won a free iPhone.
```

Output:

```text
Spam
```

## Author

Keertivanth
