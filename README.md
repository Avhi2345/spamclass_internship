# 📱 SMS Spam Classifier

This project builds a machine learning model to detect spam messages in SMS using Python and scikit-learn. The model uses text preprocessing and the Naive Bayes algorithm to accurately classify messages as either **spam** or **ham (not spam)**.

---

## 🔍 Objective

To develop a robust SMS classification model that accurately identifies spam messages from legitimate ones.

---

## 🗂️ Dataset

- **Source:** Included in the repository as `spam.csv`
- **Size:** 5,572 SMS messages
- **Features:**
  - `v1`: Label (`ham` or `spam`)
  - `v2`: Message content

---

## 🛠️ Steps Involved

1. **Data Cleaning:** Removed unnecessary columns, renamed for clarity.
2. **Label Encoding:** Converted `ham/spam` to binary `0/1`.
3. **Text Vectorization:** Used TF-IDF to convert text to numerical form.
4. **Model Training:** Trained using Multinomial Naive Bayes.
5. **Evaluation:** Measured accuracy, precision, recall, and F1-score.

---

## 📊 Results

- **Accuracy:** ~96.7%
- **Precision (Spam):** 1.00
- **Recall (Spam):** 0.75
- **F1-Score (Spam):** 0.86

---

## 🧪 Technologies Used

- Python
- Pandas
- scikit-learn
- TfidfVectorizer
- Naive Bayes

---

## 🚀 How to Run

