# Part 3: NLP and Sequence Modeling Mini Project

## Project Overview
This project demonstrates a complete Natural Language Processing (NLP) pipeline using customer support text data.

The project includes:

- Text preprocessing
- TF-IDF vectorization
- Logistic Regression baseline model
- Sequence modeling using LSTM
- Attention and Transformer reflection
- Model evaluation and visualization

---

## Dataset
Dataset used:
`customer_support_text_classification.csv`

The dataset contains customer support messages with sentiment labels.

---

## Tasks Completed

### Task 1: Dataset Understanding
- Loaded dataset
- Checked dataset shape
- Displayed sample records
- Calculated average text length
- Visualized class distribution

### Task 2: Text Preprocessing
- Lowercasing
- Removing special characters
- Tokenization
- Sequence padding

### Task 3: Text Vectorization
- TF-IDF Vectorization
- Tokenizer-based sequences

### Task 4: Baseline Model
- Logistic Regression Model
- Accuracy evaluation
- Classification report
- Confusion matrix

### Task 5: Sequence Modeling
- LSTM sequence model
- Embedding layer
- Sequence processing explanation

### Task 6: Attention and Transformer Reflection
- RNN limitations
- LSTM memory handling
- Attention mechanism
- Importance of transformers in Generative AI

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- nltk

---

## Results
Results are stored in the `results/` folder:

- class_distribution.png
- confusion_matrix.png
- model_evaluation.txt
- sample_predictions.txt

---

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt