# Heart-Disease-Predictor
This project aims to predict the presence of heart disease using machine learning techniques. By analyzing medical attributes such as blood pressure, cholesterol levels, and ECG results, models like KNN, Logistic Regression, and Random Forest are trained and evaluated. The goal is to provide an early warning system that aids in medical diagnosis.



# ❤️ Heart Disease Prediction 🔬  

## 📌 Overview  
Heart disease is one of the leading causes of mortality worldwide. Early detection can significantly improve treatment outcomes. This project leverages **machine learning** to predict the presence of heart disease based on various health indicators.  

Using a dataset containing multiple medical attributes, we trained and evaluated models such as:  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression**  
- **Random Forest Classifier**  

Additionally, we applied **cross-validation** techniques to ensure robust model performance.  

---

## 📊 Dataset & Features  
The dataset contains **various medical attributes** that can indicate heart disease. Below is a breakdown of the key features:  

| Feature | Description |
|---------|------------|
| **age** | Age in years |
| **sex** | Sex (1 = Male, 0 = Female) |
| **cp** | Chest pain type (0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal, 3 = Asymptomatic) |
| **trestbps** | Resting blood pressure (mm Hg) |
| **chol** | Serum cholesterol (mg/dl) |
| **fbs** | Fasting blood sugar > 120 mg/dl (1 = True, 0 = False) |
| **restecg** | Resting electrocardiographic results (0 = Normal, 1 = ST-T Wave abnormality, 2 = Left ventricular hypertrophy) |
| **thalach** | Maximum heart rate achieved |
| **exang** | Exercise-induced angina (1 = Yes, 0 = No) |
| **oldpeak** | ST depression induced by exercise relative to rest |
| **slope** | Slope of peak exercise ST segment (0 = Upsloping, 1 = Flat, 2 = Downsloping) |
| **ca** | Number of major vessels (0-3) colored by fluoroscopy |
| **thal** | Thalium stress test result (1,3 = Normal, 6 = Fixed defect, 7 = Reversible defect) |
| **target** | Presence of heart disease (1 = Yes, 0 = No) |

---

## 🛠️ Technologies & Libraries Used  
- **Python** 🐍  
- **Pandas** (Data manipulation)  
- **NumPy** (Numerical computations)  
- **Matplotlib & Seaborn** (Data visualization)  
- **Scikit-learn** (Machine learning models & evaluation)  

---

## 🚀 Model Implementation  
1. **Exploratory Data Analysis (EDA)**  
   - Visualized data distributions  
   - Checked correlations between features  
   - Identified missing or outlier values  

2. **Data Preprocessing**  
   - Standardized numerical features  
   - Handled categorical variables  
   - Split data into **training** and **test** sets  

3. **Model Training & Evaluation**  
   - Implemented **KNN, Logistic Regression, and Random Forest**  
   - Used **cross-validation** to validate performance  
   - Evaluated models using metrics such as **accuracy, precision, recall, F1-score, and ROC curves**  

---

## 📈 Results & Findings  
- **Random Forest** showed the highest accuracy in our experiments.  
- **Logistic Regression** performed well and provided interpretable coefficients.  
- **Cross-validation** helped reduce overfitting and improved model generalization.  
- **Feature importance analysis** revealed key indicators of heart disease, such as **chest pain type, number of major vessels, and thalium stress test results**.  

---

## 🔥 How to Use  
### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```
### 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```
### 3️⃣ Run the Model  
```sh
python heart_disease_predictor.py
```

---

## 📌 Future Improvements  
- Implement **Deep Learning models (ANNs)** for better accuracy.  
- Optimize hyperparameters using **GridSearchCV**.  
- Deploy the model using **Flask / Streamlit** for real-world applications.  

---

## 📜 References  
- **UCI Heart Disease Dataset** (https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Scikit-learn Documentation** (https://scikit-learn.org/)  

---

## 🤝 Contributing  
Contributions are welcome! Feel free to **fork** this repo, make improvements, and submit a **pull request**.  

🔗 **GitHub:** [Your Profile]([https://github.com/your-username](https://github.com/software2304))  

