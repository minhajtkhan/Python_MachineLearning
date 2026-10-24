# Python-Lectures: AI & Machine Learning Notebooks

A structured collection of Jupyter Notebooks covering **Python fundamentals** and the complete **data preprocessing pipeline for Machine Learning**: from NumPy and Pandas basics to outlier detection, encoding, scaling, feature engineering, data splitting, and handling imbalanced datasets.

Each notebook is self-contained, hands-on, and designed to be followed in order.

---

## Table of Contents

- [Repository Structure](#-repository-structure)
- [Topics Covered](#-topics-covered)
- [Learning Path](#-learning-path)
- [Getting Started](#-getting-started)
- [Tech Stack](#-tech-stack)
- [Contributing](#-contributing)
- [Author](#-author)

---

## Repository Structure

```
Python-Lectures/
│
├── Python_Basics.ipynb
│
├── AI_ML_1_Numpy_Basics.ipynb
├── AI_ML_2_Pandas_Fundamentals.ipynb
├── AI_ML_3_EDA_Understanding_a_Dataset.ipynb
├── AI_ML_4_Missing_Values_Imputation.ipynb
│
├── AI_ML_5_Outliers.ipynb
├── AI_ML_5_1_Outliers_Detection_using_IQR.ipynb
├── AI_ML_5_2_Outliers_Detection_using_Z_Score.ipynb
├── AI_ML_5_3_Outlier_Detection_using_Isolation_Forest.ipynb
├── AI_ML_5_4_Outliers_Detection_using_Clustering.ipynb
├── AI_ML_5_5_Outliers_Detection_using_K_NN.ipynb
│
├── AI_ML_6_Numerical_vs_Categorical_Data.ipynb
├── AI_ML_6_1_Label_Encoding.ipynb
├── AI_ML_6_2_OneHot_Encoding.ipynb
│
├── AI_ML_7_Feature_Scaling.ipynb
├── AI_ML_8_Feature_Engineering.ipynb
├── AI_ML_9_Feature_Selection.ipynb
│
├── AI_ML_10_1_Feature_vs_Target.ipynb
├── AI_ML_10_2_Train_Test_Split.ipynb
├── AI_ML_10_3_Training_Dataset.ipynb
├── AI_ML_10_5_Testing_Dataset.ipynb
├── AI_ML_10_6_Stratified_Sampling.ipynb
├── AI_ML_10_7_Data_Leakage.ipynb
│
├── AI_ML_11_Understanding_Class_Imbalance.ipynb
├── AI_ML_12_Random_Oversampling.ipynb
├── AI_ML_13_Random_UnderSampling.ipynb
└── AI_ML_14_SMOTE.ipynb
```

---

## Topics Covered

## Foundations
| Notebook | Description |
|----------|-------------|
| `Python_Basics` | Core Python syntax, data types, control flow, functions, and more |
| `AI_ML_1_Numpy_Basics` | Arrays, indexing, slicing, broadcasting, and vectorized operations |
| `AI_ML_2_Pandas_Fundamentals` | Series, DataFrames, filtering, grouping, merging, and data manipulation |

### Data Understanding & Cleaning
| Notebook | Description |
|----------|-------------|
| `AI_ML_3_EDA_Understanding_a_Dataset` | Exploratory Data Analysis: summary statistics, distributions, and visualizations |
| `AI_ML_4_Missing_Values_Imputation` | Detecting and handling missing data (mean/median/mode, and other imputation methods) |

### Outlier Detection
| Notebook | Description |
|----------|-------------|
| `AI_ML_5_Outliers` | Introduction to outliers: what they are and why they matter |
| `AI_ML_5_1_Outliers_Detection_using_IQR` | Interquartile Range (IQR) method |
| `AI_ML_5_2_Outliers_Detection_using_Z_Score` | Z-Score / standard deviation method |
| `AI_ML_5_3_Outlier_Detection_using_Isolation_Forest` | Isolation Forest (tree-based anomaly detection) |
| `AI_ML_5_4_Outliers_Detection_using_Clustering` | Clustering-based outlier detection |
| `AI_ML_5_5_Outliers_Detection_using_K_NN` | K-Nearest Neighbors based detection |

### Encoding Categorical Data
| Notebook | Description |
|----------|-------------|
| `AI_ML_6_Numerical_vs_Categorical_Data` | Understanding data types in ML datasets |
| `AI_ML_6_1_Label_Encoding` | Converting categories to integer labels |
| `AI_ML_6_2_OneHot_Encoding` | Converting categories to binary columns |

### Feature Preparation
| Notebook | Description |
|----------|-------------|
| `AI_ML_7_Feature_Scaling` | Normalization and standardization (MinMax, StandardScaler, etc.) |
| `AI_ML_8_Feature_Engineering` | Creating new, more informative features from existing data |
| `AI_ML_9_Feature_Selection` | Choosing the most relevant features for modeling |

### Splitting & Sampling Data
| Notebook | Description |
|----------|-------------|
| `AI_ML_10_1_Feature_vs_Target` | Separating independent features (X) from the target (y) |
| `AI_ML_10_2_Train_Test_Split` | Splitting data into training and testing sets |
| `AI_ML_10_3_Training_Dataset` | Working with the training set |
| `AI_ML_10_5_Testing_Dataset` | Working with the testing set |
| `AI_ML_10_6_Stratified_Sampling` | Preserving class proportions when splitting |
| `AI_ML_10_7_Data_Leakage` | What data leakage is and how to prevent it |

### Handling Imbalanced Data
| Notebook | Description |
|----------|-------------|
| `AI_ML_11_Understanding_Class_Imbalance` | Why class imbalance hurts models and how to detect it |
| `AI_ML_12_Random_Oversampling` | Balancing classes by duplicating minority samples |
| `AI_ML_13_Random_UnderSampling` | Balancing classes by removing majority samples |
| `AI_ML_14_SMOTE` | Synthetic Minority Over-sampling Technique |

---

## Learning Path

For the best experience, follow the notebooks in this order:

```
Python Basics → NumPy → Pandas → EDA → Missing Values
      ↓
 Outlier Detection → Encoding → Scaling
      ↓
 Feature Engineering → Feature Selection
      ↓
 Feature/Target → Train-Test Split → Stratified Sampling → Data Leakage
      ↓
 Class Imbalance → Oversampling → Undersampling → SMOTE
```

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/Python-Lectures.git
cd Python-Lectures
```

### 2. (Optional) Create a virtual environment
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

### 4. Launch Jupyter
```bash
jupyter notebook
```
Then open any `.ipynb` file and run the cells in order.

> You can also open the notebooks directly in **Google Colab** or **VS Code** with the Jupyter extension.

---

## Tech Stack

- **Language:** Python 3
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn
- **Environment:** Jupyter Notebook

---

## Contributing

Suggestions and improvements are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## Author

**Minhaj Tahir Khan**

⭐ If you found this repository helpful, consider giving it a star!
