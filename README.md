# 🎌 Anime Recommendation System

## 📌 Project Overview

This project is based on the **Anime Recommendations Database** dataset from Kaggle.

The main goal of this project is to analyze anime data and build a Machine Learning-based system for understanding anime ratings and user preferences.

The dataset contains information about different anime along with ratings provided by users.

---

## 📊 Dataset

**Dataset Name:** Anime Recommendations Database

**Dataset Source:**

https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database

The dataset contains information collected from **MyAnimeList**.

It includes:

* Anime details
* Anime genres
* Anime types
* Number of episodes
* Average ratings
* User ratings

---

## 📁 Dataset Files

The dataset contains two main files:

### 1️⃣ anime.csv

This file contains information about anime.

| Column     | Description                                 |
| ---------- | ------------------------------------------- |
| `anime_id` | Unique ID of the anime                      |
| `name`     | Name of the anime                           |
| `genre`    | Genres of the anime                         |
| `type`     | Type of anime (TV, Movie, OVA, etc.)        |
| `episodes` | Number of episodes                          |
| `rating`   | Average rating of the anime                 |
| `members`  | Number of members associated with the anime |

---

### 2️⃣ rating.csv

This file contains ratings given by users.

| Column     | Description              |
| ---------- | ------------------------ |
| `user_id`  | Unique ID of the user    |
| `anime_id` | Unique ID of the anime   |
| `rating`   | Rating given by the user |

**Note:** A rating value of `-1` indicates that the user watched the anime but did not provide a rating.

---

## 🎯 Project Objective

The main objectives of this project are:

* To perform data preprocessing.
* To analyze the anime dataset.
* To understand user preferences.
* To handle missing values.
* To explore anime ratings and genres.
* To train Machine Learning models.
* To evaluate and compare the performance of different models.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## 🔄 Machine Learning Workflow

The project follows the following workflow:

```text
Dataset Collection
        ↓
Data Loading
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Model Comparison
        ↓
Model Saving
```

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Loading the dataset
* Checking dataset shape
* Checking column names
* Checking missing values
* Removing unnecessary or invalid data
* Handling missing values
* Converting categorical data into numerical form
* Preparing features for Machine Learning models

---

## 🤖 Machine Learning Models

Different Machine Learning models were trained and evaluated.

The models can be compared based on their performance metrics.

Example models:

* Linear Regression
* Random Forest
* Decision Tree
* K-Nearest Neighbors
* Other Machine Learning models

---

## 📈 Model Evaluation

The trained models are evaluated using suitable performance metrics.

Depending on the problem, the following metrics can be used:

### For Regression

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 💾 Model Saving

The trained Machine Learning model can be saved using **Joblib**.

Example:

```python
import joblib

joblib.dump(model, "model.pkl")
```

To load the model:

```python
model = joblib.load("model.pkl")
```

---

## 📂 Project Structure

```text
Anime-Recommendation-Project/
│
├── data/
│   ├── anime.csv
│   └── rating.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── train_model.py
│   └── evaluate_model.py
│
├── models/
│   └── trained_model.pkl
│
├── requirements.txt
│
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```

### Step 3: Download the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database

### Step 4: Run the Project

```bash
python train_model.py
```

---

## 📊 Results

The project compares different Machine Learning models to understand which model performs better on the given dataset.

The results are analyzed using appropriate evaluation metrics.

---

## 🔮 Future Improvements

* Build an Anime Recommendation System.
* Use Collaborative Filtering.
* Implement Content-Based Recommendation.
* Develop a Hybrid Recommendation System.
* Create a web application using Streamlit.
* Improve model performance.
* Deploy the trained model.

---

## 📚 Dataset Source

**Kaggle – Anime Recommendations Database**

https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database

---

## 👩‍💻 Author

**Jalumuri Lavanya**

B.Tech – Artificial Intelligence and Machine Learning

---

⭐ If you like this project, feel free to star the repository!
