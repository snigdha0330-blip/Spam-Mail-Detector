# Spam-Mail-Detector
A machine learning project to classify SMS messages as spam or ham using TF-IDF and Naive Bayes.
# Spam Mail Detector

This project classifies SMS messages as Spam or Ham using Machine Learning.

## Technologies Used
- Python
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

## Accuracy
96%

## Dataset
SMS Spam Collection Dataset

## Author
SNIGDHA P



# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning. The model learns from housing features such as income, house age, number of rooms, population, and location to estimate house prices.

The project uses the Linear Regression algorithm to predict house prices.

---

## 🎯 Objective

To build a machine learning model that can predict house prices based on various housing features.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Linear Regression

---

## 📂 Dataset

The project uses the California Housing Dataset provided by Scikit-learn.

Features include:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

Target:
- House Price

---

## ⚙️ Machine Learning Algorithm

- Linear Regression

Linear Regression finds the relationship between housing features and house prices and predicts the price of new houses.

---

## 📊 Model Evaluation

The model was evaluated using:

- Mean Squared Error (MSE)
- R² Score

Example Results:

- Mean Squared Error: 0.55
- R² Score: 0.57

---

## 🚀 Installation

Install the required libraries:

```bash
pip install pandas scikit-learn matplotlib
```

---

## ▶️ Run the Project

```bash
python house_price_prediction.py
```

---

## 📈 Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Split Dataset
4. Train Linear Regression Model
5. Predict House Prices
6. Evaluate Model Performance

---

## 🧠 Skills Gained

- Data Preprocessing
- Regression Analysis
- Model Training
- Model Evaluation
- Machine Learning Fundamentals

---

## 📷 Sample Output

```
Mean Squared Error: 0.55
R² Score: 0.57

Predicted House Price:
4.2
```

---

## 🔮 Future Improvements

- Random Forest Regression
- Decision Tree Regression
- XGBoost
- Deep Learning Models

---

## 👨‍💻 Author

SNIGDHA P

BSc Artificial Intelligence and Machine Learning

QSkill AI & ML Internship 2026
# 📧 Spam Mail Detection using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to classify SMS messages as either Spam or Ham (non-spam). The model learns patterns from previously labeled messages and predicts whether a new message is spam.

The project uses Natural Language Processing (NLP) techniques along with the Multinomial Naive Bayes algorithm.

---

## 🎯 Objective

To develop a machine learning model that can automatically identify spam messages and distinguish them from legitimate messages.

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

## 📂 Dataset

The project uses the SMS Spam Collection Dataset.

Dataset columns:

- v1 → Message Category (Spam/Ham)
- v2 → Message Text

---

## ⚙️ Machine Learning Algorithm

### Multinomial Naive Bayes

Naive Bayes is a probabilistic classification algorithm commonly used for text classification tasks such as:

- Spam detection
- Sentiment analysis
- Document classification

---

## 🔄 Project Workflow

1. Load Dataset
2. Data Cleaning
3. Convert Labels into Numerical Values
4. Text Preprocessing
5. TF-IDF Feature Extraction
6. Train-Test Split
7. Train Naive Bayes Model
8. Predict Messages
9. Evaluate Accuracy

---

## 📊 Model Performance

- Accuracy: 96%

Evaluation Metrics:

- Accuracy Score
- Confusion Matrix

Example Output:

```
Accuracy: 0.96

Message Prediction: SPAM
```

---

## 🚀 Installation

Install the required libraries:

```bash
pip install pandas scikit-learn numpy
```

---

## ▶️ Run the Project

```bash
python spam_detector.py
```

---

## 📥 Example Prediction

Input:

```
Congratulations! You won ₹10,000.
```

Output:

```
SPAM
```

Input:

```
Meeting is scheduled at 4 PM.
```

Output:

```
HAM
```

---

## 🧠 Skills Gained

- Text Preprocessing
- Natural Language Processing
- Feature Extraction
- Machine Learning Classification
- Model Evaluation

---

## 🔮 Future Improvements

- Support Vector Machine (SVM)
- Deep Learning Models
- Email Spam Detection
- Web Application Integration

---

## 👨‍💻 Author

SNIGDHA P

BSc Artificial Intelligence and Machine Learning

QSkill AI & ML Internship 2026
