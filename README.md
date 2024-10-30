# CODSOFT_ML
# 📊 Machine Learning Internship Tasks - Codsoft

Welcome to my project repository for the **Codsoft Machine Learning Internship**! This internship focused on applying machine learning techniques for **movie genre classification**, **credit card fraud detection**, and **SMS spam detection**. Each task leverages real-world datasets and applies classification algorithms to solve distinct problems.

---

## 🚀 Project Overview

### 1. **Movie Genre Classification**
   - **Goal**: Predict the genre of a movie based on plot summaries.
   - **Techniques**: TF-IDF vectorization for feature extraction, followed by classifiers like Naive Bayes, Logistic Regression, and Support Vector Machines.
   - **Dataset**: IMDb-based data with titles, plot summaries, and genres.

   <details>
   <summary><strong>About the Dataset</strong></summary>
   
   The IMDb dataset is an extensive database including movies, TV programs, and more. IMDb began as a fan-operated website in 1990 and moved to the web in 1993, eventually becoming a subsidiary of Amazon. This dataset includes plot summaries, genres, and other metadata for various titles.
   
   [Learn more on IMDb](https://www.imdb.com/) 🌐
   </details>

### 2. **Credit Card Fraud Detection**
   - **Goal**: Detect fraudulent credit card transactions.
   - **Techniques**: Logistic Regression, Decision Trees, and Random Forests, with hyperparameter tuning to classify transactions.
   - **Dataset**: Simulated data of credit card transactions spanning from January 2019 to December 2020.

   <details>
   <summary><strong>About the Dataset</strong></summary>
   
   The dataset simulates transactions using the **Sparkov Data Generator** by Brandon Harris. It includes transaction details from 1,000 customers at 800 merchants. Profiles, age ranges, and spending distributions were applied to simulate realistic transactions.
   
   [Explore Sparkov Data Generation Tool](https://github.com/brandonharris/sparkov-data-generator) 🌐
   </details>

### 3. **SMS Spam Detection**
   - **Goal**: Classify SMS messages as spam or legitimate (ham).
   - **Techniques**: Natural Language Processing (NLP) techniques, including tokenization and vectorization, paired with classification models like Naive Bayes and SVM.
   - **Dataset**: A collection of tagged SMS messages in English.

   <details>
   <summary><strong>About the Dataset</strong></summary>
   
   The SMS Spam Collection is a set of 5,574 tagged SMS messages, collected for SMS spam research. It includes both spam and ham messages, with data contributions from sources like the **Grumbletext** website and the **NUS SMS Corpus**.
   
   [More on the SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) 🌐
   </details>

---

## ⚙️ Installation and Setup

To run these models locally, set up a virtual environment and install the dependencies:
```bash
# Clone this repository
git clone https://github.com/your-username/ml-internship-codsoft.git
cd ml-internship-codsoft

# Create and activate a virtual environment
python -m venv env
source env/Scripts/activate  # For Windows
# source env/bin/activate    # For MacOS/Linux

# Install required libraries
pip install -r requirements.txt
