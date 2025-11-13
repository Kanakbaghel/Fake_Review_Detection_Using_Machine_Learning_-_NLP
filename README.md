# <p align='center'><font size=5>Fake Review Detection Using Machine Learning</font></p>
-------
<p align="center">
  <em>TechNest Task : 9 for Amazon Reviews</em>
</p>

---

 _Explore my more TechNest Tasks_ [Here](https://github.com/Kanakbaghel/TechNest-Internship)
 --------
<p align="center">
<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/7f5b370d-9c9f-4ebd-ac63-07cc05e47525" />
</p>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.7+-blue.svg" alt="Python Version"></a>
  <a href="https://jupyter.org/"><img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg" alt="Jupyter Notebook"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License"></a>
</p>

-------
## Project Overview

This project presents a comprehensive pipeline for detecting fake reviews in online platforms using machine learning (ML) and natural language processing (NLP). It primarily leverages a dataset of over 80,000 Google Play Store reviews to build predictive models that classify reviews as genuine or fake. The solution employs data preprocessing, feature engineering, exploratory data analysis (EDA), multiple ML classifiers, and an optional state-of-the-art deep learning approach with BERT for improved accuracy.

----
## Key Features
- **Data Cleaning & Preprocessing:** Text normalization, stopwords removal, and lemmatization to prepare raw review texts.
- **Heuristic Labeling:** Creation of fake/genuine labels based on review length, capitalization usage, and sentiment-score alignment.
- **Feature Engineering:** Extracts features such as review length, exclamation counts, capitalization ratio, and user review frequency.
- **Exploratory Data Analysis:** Visualizations including class distribution, sentiment vs. rating, and word clouds to understand patterns.
- **Machine Learning Models:** Trains and evaluates Logistic Regression, Random Forest, and XGBoost classifiers.
- **Deep Learning (Optional):** Fine-tunes a pretrained BERT model for sequence classification, demonstrating enhanced performance.
- **Evaluation:** Comprehensive model assessment using classification reports, confusion matrices, and ROC-AUC scores.
-------
## Dataset
- The dataset comprises **80,651** Google Play Store reviews.
- Key columns include `reviewId`, `userName`, `content` (the review text), `score`, `thumbsUpCount`, `reviewCreatedVersion`, `at` (date), and `appVersion`.
- Reviews are labeled as fake or genuine through heuristic rules due to absence of explicit ground truth labels.
----
## Project Structure
- `data/` - Contains the dataset file (e.g., `reviews.csv`).
- `notebooks/` - Jupyter notebook with the full pipeline:
  - Data loading 
  - Preprocessing 
  - EDA 
  - Modeling (ML & BERT)
  - Evaluation
- `results/` - Folder for storing model outputs, visualizations, and logs.
-------
## Requirements
- Python 3.7+
- Libraries:
  - pandas, numpy, matplotlib, seaborn
  - scikit-learn, xgboost
  - nltk, spacy
  - textblob, wordcloud
  - transformers, torch
- Install using pip:
  ```bash
  pip install -r requirements.txt
  ```
  *(Create a `requirements.txt` with the above libraries for easier installation.)*
---

## Want to Help?

Love this project? Awesome! Here's how you can contribute:
- **Report Issues:** Spot a bug? Open an [issue](https://github.com/Kanakbaghel/Data_Pipeline_Development/issues).
- **Suggest Ideas:** Have a cool tweak? Share it!
- **Code Together:** Send a pull request with improvements.

---

## Get in Touch

Got questions or want to chat about data? Reach out:
- **GitHub:** [Kanakbaghel](https://github.com/Kanakbaghel)
- **LinkedIn:** [Kanak Baghel](https://www.linkedin.com/in/kanakbaghel)

---

## License

This project is open-source under the MIT License. Feel free to use, share, and build on it!

---

> _“Data becomes meaningful when it tells a story that leads to better decisions.”_

<p align="center">
  <em>Crafted with by <strong>Kanak Baghel</strong> | <a href="https://www.linkedin.com/in/kanakbaghel">LinkedIn</a></em>
</p>
