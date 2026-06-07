# AI & ML Master's Program - Coursework & Assignments (2026)

Welcome to the **AI & ML Master's Program** repository. This repository houses programming assignments, projects, and coursework completed as part of the curriculum.

---

## 📂 Repository Structure

The repository is organized by topic/assignment index to keep the workspaces tidy and structured.

```text
ai-ml-2026-masters/
├── .gitignore
├── README.md
├── 01-linear-regression/
│   ├── linear_regression_assignment_1.ipynb   # Linear Regression notebook
│   ├── bike_train.csv                         # Training dataset (bike sharing)
│   ├── bike_test.csv                          # Testing dataset (bike sharing)
│   └── submission_3.csv                       # Prediction submissions
│
└── 02-mlp-linear-regression/
    └── mlp_linear_regression_assignment.ipynb # Comparing Linear Models & MLPs
```

---

## 🛠️ Setup & Installation

To run any of the notebooks locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/pipiLongstocking/ai-ml-2026-masters.git
cd ai-ml-2026-masters
```

### 2. Create and Activate a Virtual Environment
```bash
# Create a virtual environment
python -m venv venv

# Activate it (macOS/Linux)
source venv/bin/activate

# Activate it (Windows)
# venv\Scripts\activate
```

### 3. Install Dependencies
Install the required machine learning and data science libraries:
```bash
pip install --upgrade pip
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## 📝 Assignments Details

### 1. [Linear Regression](file:///Users/raviteja/Documents/ai-ml-2026-masters/01-linear-regression)
* **Goal**: Implement and evaluate Linear Regression and Ridge Regression models on a bike-sharing dataset.
* **Key Tasks**: Data preprocessing, feature engineering, polynomial features, regularization parameter tuning, and predicting bike rentals.
* **Main Notebook**: [linear_regression_assignment_1.ipynb](file:///Users/raviteja/Documents/ai-ml-2026-masters/01-linear-regression/linear_regression_assignment_1.ipynb)

### 2. [Multi-Layer Perceptrons & Linear Models Comparison](file:///Users/raviteja/Documents/ai-ml-2026-masters/02-mlp-linear-regression)
* **Goal**: Compare the performance of classical linear models and Multi-Layer Perceptrons (MLPs) on a classification task.
* **Key Tasks**: Data loading, model configuration, forward/backward propagation implementation/tuning, training loop development, and performance evaluation.
* **Main Notebook**: [mlp_linear_regression_assignment.ipynb](file:///Users/raviteja/Documents/ai-ml-2026-masters/02-mlp-linear-regression/mlp_linear_regression_assignment.ipynb)

---

## 🚀 Future Assignments
More folders will be added sequentially as the coursework progresses. New folders will follow the `XX-topic-name` naming convention for consistency.
