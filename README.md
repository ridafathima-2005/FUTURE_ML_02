Support Ticket Classification & Prioritization (Task 2)

Project Overview

This project uses Machine Learning and Natural Language Processing (NLP) to automatically classify support tickets and prioritize them based on their content.

Organizations receive a large number of support tickets daily. Manually categorizing and prioritizing them is time-consuming and inefficient. This system helps automate that process.

---

Objective

* Classify support tickets based on their content
* Predict ticket priority or category
* Improve response efficiency
* Reduce manual workload

---

Features

✔ Text preprocessing using NLP techniques
✔ Feature extraction using TF-IDF
✔ Machine Learning classification model
✔ Prediction of ticket category/priority
✔ Model evaluation using classification metrics
✔ Sample predictions for better understanding

---

 Tech Stack

* Python
* Pandas
* Scikit-learn
* NLP techniques (text cleaning, tokenization)
* Jupyter Notebook

---

How It Works

1. **Data Loading**

   * Load support ticket dataset

2. **Text Preprocessing**

   * Lowercasing
   * Removing stopwords
   * Cleaning text

3. **Feature Extraction**

   * Convert text into numerical form using TF-IDF

4. **Model Training**

   * Train a classification model on ticket data

5. **Prediction**

   * Predict category/priority of new tickets

6. **Evaluation**

   * Use classification metrics to evaluate model performance

---

Output

* Classified support tickets
* Predicted categories or priorities
* Model performance metrics (precision, recall, F1-score)

---

How to Run

1. Install dependencies:

```bash
pip install pandas scikit-learn
```

2. Open the notebook:

```
Support_Ticket_Classification.ipynb
```

3. Run all cells

---

Files

* `Support_Ticket_Classification.ipynb` → Main implementation
* Dataset (if included)

---

Insights

* Automated ticket classification reduces manual effort
* Helps prioritize urgent issues faster
* Improves customer support efficiency

---

