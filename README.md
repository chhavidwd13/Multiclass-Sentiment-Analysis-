# Mental Health Text Classification

## Overview

This project uses Natural Language Processing (NLP) and Machine Learning techniques to analyze text and classify it into multiple mental health-related categories. The system processes textual data and predicts patterns associated with depression, anxiety, stress, emotions, and eating behavior.

## Features

* Text preprocessing and cleaning
* TF-IDF feature extraction
* Multi-class text classification
* Machine Learning-based prediction
* Data visualization and analysis
* Mental health category detection

## Dataset

The project utilizes five datasets related to different mental health dimensions:

* Anxiety Detection Dataset
* Depression Detection Dataset
* Eating Behavior Dataset
* Emotion Detection Dataset
* Stress Detection Dataset

All datasets are included in the `dataset/` directory.

## Project Structure

```text
Mental-Health-Text-Classification/
├── dataset/
│   ├── anxiety_detection.csv
│   ├── depression_detection.csv
│   ├── eating_behavior_dataset.csv
│   ├── emotion_detection.csv
│   └── stress_detection.csv
│
├── notebook/
│   └── nlp_multiclass_sentiment_analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Workflow

1. Load and preprocess text datasets
2. Clean and normalize text
3. Extract features using TF-IDF
4. Train classification models
5. Evaluate model performance
6. Generate predictions and insights

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook from the `notebook/` directory.

## Future Improvements

* Deep Learning-based classification
* Transformer models (BERT)
* Web-based deployment
* Real-time prediction interface

## Author

Developed as an NLP and Machine Learning project focused on mental health text analysis.
