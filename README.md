# 🌸 Iris Dataset Classifier

This project demonstrates the classification of the famous **Iris flower dataset** using various Machine Learning models, including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

Beautiful visualizations using **PCA (Principal Component Analysis)** and **decision boundaries** are included to show how each model performs in reduced 2D space.

---

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository - Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- 150 samples with 4 features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 classes:
  - Iris Setosa
  - Iris Versicolor
  - Iris Virginica

---

## 🧠 Models Used

| Model                | Technique        |
|---------------------|------------------|
| Logistic Regression | Linear Model     |
| KNN                 | Instance-Based   |
| SVM (RBF)           | Margin-Based     |
| Decision Tree       | Tree-Based       |
| Random Forest       | Ensemble Method  |

---

## 🖼️ Visualizations

✅ PCA Projection  
✅ Decision Boundaries for each model  
✅ Confusion Matrices  
✅ Accuracy Comparison Bar Charts  
✅ Decision Tree Plot

---

## 📦 Libraries Used

- `scikit-learn`
- `matplotlib`
- `seaborn`
- `numpy`
- `pandas`

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/advait-vikas/Iris_Dataset_Classification.git
cd Iris_Dataset_Classification

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Iris_Data_Classification.ipynb
