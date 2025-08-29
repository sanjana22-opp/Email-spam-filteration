 Email Spam Filtering Project

 📌 Overview
This project implements a **Spam Email Classifier** using **Natural Language Processing (NLP)** and **Machine Learning**.  
The classifier is trained on the **SMS Spam Collection dataset**, which contains text messages labeled as either "notspam (genuine)" or "spam (unwanted messages)".  

We used the **Multinomial Naive Bayes** algorithm, which is a well-known method for text classification tasks like spam detection.  

---

 ⚙️ Features
- Data preprocessing (renaming columns, handling unwanted columns)
- Feature extraction using **Bag of Words (CountVectorizer)**
- Trained a **Naive Bayes Classifier** inside a **Scikit-learn Pipeline**
- Achieved **98% accuracy**
- Provides precision, recall, and F1-score for both spam and ham categories

--📂 Dataset
- **Source**: [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- **Total Records**: 5,572 messages  
- **Columns**:
  - `Categories`: Label → `ham` (not spam) or `spam`  
  - `Messages`: The text message content  
  - `spam`: Converted binary label → `1 = spam`, `0 = ham`


.

🚀 How to Run

Clone/download this repository.

Install dependencies:

pip install -r requirements.txt


Run the script:

python spam_filter.py


