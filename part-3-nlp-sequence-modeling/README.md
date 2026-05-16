# NLP & Sequence Modeling Mini Project

## Problem Statement
Built a complete NLP pipeline for customer support ticket sentiment classification using traditional and sequence modeling approaches.

## Dataset
- **File**: `customer_support_text_classification.csv`
- **Records**: ~1500
- **Target**: `sentiment_label` (positive, negative, neutral)

## Approach

### Task 1: Dataset Understanding
- Analyzed class distribution, average text length, and samples.

### Task 2: Text Preprocessing
- Lowercasing, special character removal, tokenization, stopword removal.

### Task 3: Text Vectorization
- **TF-IDF** for traditional ML
- **Tokenizer + Padding** for deep learning

### Task 4: Baseline Model
- **Logistic Regression + TF-IDF**
- Achieved good accuracy on sentiment classification.

### Task 5: Sequence Model
- **LSTM** model with Embedding layer
- Demonstrated sequence modeling capability.

### Task 6: Reflection
- Explained limitations of RNNs, benefits of LSTMs, Attention, and Transformers.

## Results
- Visualizations: `class_distribution.png`, `wordcloud.png`, `training_curves.png`
- Models: `baseline_model.pkl`, `lstm_model.h5`
- Predictions: `sample_predictions.txt`

## Technologies Used
- Python, Pandas, Scikit-learn, TensorFlow/Keras, NLTK, Matplotlib, Seaborn

## How to Run
1. Open notebook in Google Colab
2. Upload dataset
3. Run all cells

4. Dataset Link:  https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs
