# Machine Learning And Data Analysis Project
Progetto d' Esame di MACHINE LEARNING AND DATA ANALYSIS - Università degli Studi di Perugia

# 🧠 Obesity Levels Analysis and Modeling: A Machine Learning Approach

This project applies **machine learning techniques** to analyze and predict **obesity levels** using demographic data, eating habits, and lifestyle information.

The goal is to build classification models capable of predicting the obesity category of individuals based on their physical conditions and behavioral patterns.

🎓 Machine Learning Project (2023/2024)  
👤 Author: **Daniele Angeloni**  
🎓 Degree: *Ingegneria Informatica e Robotica – Curriculum Data Science and Data Engineering*

---

# 📊 Dataset

The dataset used in this project is **"Estimation of Obesity Levels Based on Eating Habits and Physical Condition"**, available in the **UCI Machine Learning Repository**.

🔗 https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

It contains:

- **2111 observations**
- **17 attributes**
- Individuals from **Mexico, Peru and Colombia**

The dataset includes variables related to:

### 👤 Demographic Information
- Age
- Gender
- Height
- Weight

### 🍎 Eating Habits
- Vegetable consumption
- Number of daily meals
- Consumption of high caloric food
- Eating between meals

### 🏃 Lifestyle Factors
- Physical activity frequency
- Alcohol consumption
- Time spent using technological devices
- Transportation used

### 🧬 Health History
- Family history of overweight

The target variable **NObeyesdad** classifies individuals into **7 obesity categories**:

- Insufficient Weight  
- Normal Weight  
- Overweight Level I  
- Overweight Level II  
- Obesity Type I  
- Obesity Type II  
- Obesity Type III  

The dataset consists of:

- **23% real data** collected through a web platform  
- **77% synthetic data** generated using **SMOTE** with the Weka tool.

---

# ⚙️ Methodology

The project follows a typical **machine learning pipeline**.

### 1️⃣ Data Exploration
The dataset was initially explored to understand the distribution of variables and their relationships with obesity levels.

### 2️⃣ Data Preprocessing
The preprocessing phase included:

- encoding categorical variables
- feature scaling
- train/test split
- multicollinearity analysis using **Variance Inflation Factor (VIF)**

Two normalization techniques were tested:

- **StandardScaler**
- **MinMaxScaler**

### 3️⃣ Model Training

Several classification algorithms were implemented and compared:

- 📈 **Logistic Regression**
- 👥 **K-Nearest Neighbors (KNN)**
- 📉 **Support Vector Machine (SVM)**
- 🧠 **Neural Network (Multi-Layer Perceptron)**

Hyperparameters were optimized using **GridSearchCV with K-Fold Cross Validation**.

---

### 🏆 Best Model

The **best performing model** selected during the project was:

**Logistic Regression**

Performance on the **test dataset**:

| Metric | Value |
|------|------|
| Accuracy | **0.967** |
| F1-score | **0.967** |

The model demonstrated strong capability in correctly classifying the different obesity levels.

---

# 📊 Evaluation Metrics

Model performance was evaluated using:

- **Confusion Matrix**
- **F1-score**
- **ROC Curve**
- **AUC**
- **Classification Report**

These metrics allowed a comprehensive comparison between the different models.

---

# ✅ Conclusion

This project demonstrates how **machine learning techniques can be applied to health-related datasets** to analyze complex relationships between lifestyle factors and obesity.

The results highlight that behavioral, demographic, and physical attributes are strongly associated with obesity levels and can be effectively used for **predictive modeling and health data analysis**.

Machine learning models therefore represent valuable tools for supporting **data-driven insights in public health research**.
