# 🌸 Flower Species Classification using Random Forest Classifier

## 📌 Overview
This project uses a **Random Forest Classifier** to identify the type of flower based on its physical features. It is trained on a dataset that includes different flower species (like the popular Iris dataset) and predicts the class based on measurements such as petal and sepal dimensions.

## 📊 Features Used
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 🌼 Target Classes
- Setosa
- Versicolor
- Virginica

## 🤖 ML Algorithm
- **Random Forest Classifier**
  - Ensemble of Decision Trees
  - High accuracy and robustness
  - Reduces overfitting

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

## 📂 Project Structure
```
├── data/
│   └── iris.csv                    # Dataset (if not using sklearn's built-in)
├── models/
│   └── random_forest_model.pkl     # Saved model (optional)
├── notebook/
│   └── flower_classification.ipynb # Jupyter Notebook with training and results
├── main.py                         # Script file (if applicable)
├── requirements.txt                # Dependencies
└── README.md                       # Project overview
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flower-classification.git
   cd flower-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script:
   - Open `flower_classification.ipynb` in Jupyter Notebook
   - Or run `main.py`

## 📈 Model Performance
- Accuracy: `97%`
- Confusion Matrix: Included in notebook

## 📷 Sample Output
*(Include confusion matrix, classification report, and decision boundary plot)*

## 📚 Dataset
- Source: [Iris Dataset from UCI or scikit-learn]
- Description: Contains 150 samples of iris flowers with 4 features each

## 📌 Future Improvements
- Add GUI using Streamlit or Tkinter
- Hyperparameter tuning using GridSearchCV
- Add support for more flower datasets

## 🙋‍♂️ Author
- Name: **Abdur Rafay**
- GitHub: [A6dur](https://github.com/A6dur)
