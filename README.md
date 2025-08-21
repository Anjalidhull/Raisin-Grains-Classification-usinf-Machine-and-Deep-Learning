

   ![collection-of-various-raisins-free-photo](https://github.com/user-attachments/assets/c5423efe-6182-4e08-8c33-d61023855b97)




# Raisin Grain Classification using Machine Learning & MLP

## 📌 Project Overview
This project focuses on classifying raisin grains into two categories: **Kecimen** and **Besni** using traditional **Machine Learning models** and a **Multi-Layer Perceptron (MLP)**.  
The dataset contains morphological features of raisin grains, and the goal is to compare the performance of multiple ML algorithms with a neural network model.

---

## 📂 Dataset
- **Source**: [Raisin Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Raisin+Dataset)
- **Total Samples**: 720
- **Classes**: 2 (Kecimen, Besni)
- **Features**:
  - `Area`
  - `Perimeter`
  - `MajorAxisLength`
  - `MinorAxisLength`
  - `Eccentricity`
  - `ConvexArea`
  - `Extent`
- **Target Column**: `Class` (Binary classification)

---

## 🛠 Tech Stack
- **Language**: Python
- **Libraries**:
  - `NumPy`, `Pandas` – Data manipulation
  - `Matplotlib`, `Seaborn` – Data visualization
  - `Scikit-learn` – ML models & evaluation
  

---

## 🔍 Project Workflow
1. **Data Preprocessing**
   - Handling missing values (if any)
   - Encoding target labels (Kecimen = 0, Besni = 1)
   - Feature scaling (StandardScaler)
   - Train-Test split
2. **Exploratory Data Analysis (EDA)**
   - Feature distribution plots
   - Correlation heatmap
3. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - k-Nearest Neighbors (k-NN)
   - Multi-Layer Perceptron (MLP)
4. **Model Evaluation**
   - Accuracy
   - Confusion Matrix
   - Classification Report
5. **Model Comparison**

---

## 🧠 Models Used & Accuracy
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 90%      |
| Decision Tree       | 85%      |
| Random Forest       | 88%      |
| SVM                 | 88%      |
| Linear- SVC         | 90%      |
| **MLP**             | 92%      |



---






---




