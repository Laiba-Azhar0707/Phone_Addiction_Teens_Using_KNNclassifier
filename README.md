# Teen Phone Addiction Prediction using KNN Classifier 📱🤖

This machine learning project uses a K-Nearest Neighbors (KNN) classifier to predict **addiction levels in teens** based on their phone usage patterns. The dataset includes various behavioral and demographic features, and the model aims to help understand which factors are most linked to potential phone addiction.

---

## 📁 Dataset

The dataset used is **`teen_phone_addiction_dataset.csv`**, which contains multiple features including:

- **School Grade** (6 unique levels)
- **Phone Usage Purpose** (5 unique purposes)
- **Screen Time**
- **Sleep Patterns**
- **Parental Control**
- And several other behavioral indicators.

The target variable is:
- **Addiction Level** — categorical classification based on overall usage.

---

## 🧠 Objective

To classify teens into **different addiction levels** using KNN based on patterns in their responses.

---

## ⚙️ Machine Learning Workflow

1. **Data Cleaning**
   - Removed nulls, handled inconsistencies
2. **Encoding**
   - Categorical features like `school grade` and `phone usage purpose` were encoded using `LabelEncoder`
3. **Feature Scaling**
   - Applied `StandardScaler` to normalize feature ranges
4. **Model Selection**
   - Used `KNeighborsClassifier`
   - Tried different values of `k` and metrics (`euclidean`, `manhattan`)
5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix

---

## 🔍 Results

- **Best Accuracy Achieved**: `93.16%`
- **Optimal K**: 5
- **Best Distance Metric**: Manhattan
- **Preprocessing**: StandardScaler used

---

## 📊 Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn (KNN, preprocessing, metrics)
- Matplotlib / Seaborn for optional visualization

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Laiba-Azhar0707/Phone_Addiction_Teens_Using_KNNclassifier.git
