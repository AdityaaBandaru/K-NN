# 🏋️‍♂️ Gym Membership Classifier using K-Nearest Neighbors

This project builds a K-Nearest Neighbors (K-NN) classifier to predict whether a person is a regular gym-goer based on their age and monthly membership fee. The model is trained on a synthetic dataset designed to mimic realistic gym behavior patterns.

---

## 📊 Dataset Overview

The dataset includes:
- `Age`: Age of the individual (18–60)
- `MonthlyFee`: Monthly gym subscription fee (in USD)
- `RegularGymGoer`: Target label (1 for regular, 0 for not)

🧠 The dataset simulates behavior where young or budget-conscious individuals are more likely to attend regularly.

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas & NumPy for data handling
- Matplotlib for visualization
- Scikit-learn for K-NN classification

---

## 🚀 How It Works

1. **Preprocessing**:
   - Feature scaling using `StandardScaler`
2. **Modeling**:
   - K-Nearest Neighbors classifier (`KNeighborsClassifier`)
   - Train-test split (75%-25%)
3. **Prediction**:
   - Predicts if a new person is likely a regular gym-goer

---

## 📈 Results

- Accuracy: **~90%** on test data
- Visualisation Training set
- <img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/96e75f44-56a8-4ca8-8a40-70a3ba58d62f" />

- Visualisation Testing set
- <img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/65a2f8b1-1b55-4fc2-93e0-4067952c9323" />

- Confusion Matrix:
<img width="246" height="86" alt="image" src="https://github.com/user-attachments/assets/babdf621-2fca-473f-bbde-fe8ea53d0f5c" />


