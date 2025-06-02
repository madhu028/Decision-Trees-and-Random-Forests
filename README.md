# Decision-Trees-and-Random-Forests

# ❤️ Heart Disease Prediction with Decision Tree and Random Forest

This project demonstrates how to use **Decision Trees** and **Random Forests** for classification using the [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

---

## 🔧 Tools Used

- Python 3
- Scikit-learn
- Pandas, Matplotlib, Seaborn
- Graphviz (for tree visualization)
- Google Colab (or Jupyter Notebook)

---

## 📊 Project Tasks

### 1. Train a Decision Tree Classifier and Visualize the Tree
- Tree built with `max_depth=3` to prevent overfitting
- Visualized using Graphviz

### 2. Analyze Overfitting and Prune Tree Depth
- Accuracy vs. depth plotted
- Shows how deeper trees overfit and shallower trees generalize better

### 3. Train a Random Forest and Compare Accuracy
- Random Forest with 100 estimators and `max_depth=5`
- Generally higher accuracy than a single Decision Tree

### 4. Interpret Feature Importances
- Important features include:
  - `cp` (chest pain type)
  - `thalach` (max heart rate)
  - `oldpeak` (ST depression)

### 5. Evaluate Models using Cross-Validation
- 5-fold CV used for both models
- Shows that Random Forest is more stable

---

## 📈 Results

| Model           | Test Accuracy | CV Accuracy |
|----------------|---------------|-------------|
| Decision Tree  | ~0.80         | ~0.79       |
| Random Forest  | ~0.87         | ~0.83       |

---

## 🚀 How to Run

### ✅ Google Colab

1. Open `notebook/heart_disease_model.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run the first cell and upload `heart.csv` when prompted
3. The rest of the cells will execute automatically

### ✅ Local Python (.py) or Jupyter

1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run the Jupyter Notebook or Python script

---

## 📦 Dependencies

pandas
numpy
scikit-learn
matplotlib
seaborn
graphviz


---

## 📁 Dataset

- You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Place it inside the `data/` directory as `heart.csv`

---

## 👨‍💻 Author

- Your Name
- GitHub: [MADHUMITHA](https://github.com/madhu028/madhu.git)

---
