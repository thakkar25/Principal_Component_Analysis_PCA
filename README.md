# Principal_Component_Analysis_PCA

## 📖 Overview

This project demonstrates the implementation of **Principal Component Analysis (PCA)** using Python and Scikit-learn.

PCA is an **Unsupervised Machine Learning** technique used to reduce the number of features while preserving the maximum amount of information (variance).

---

# 📚 What is PCA?

Principal Component Analysis (PCA) transforms a dataset with many features into a smaller set of new features called **Principal Components**.

These components retain most of the important information while reducing the dimensionality of the dataset.

---

# 🎯 Objective

- Reduce dimensions of the dataset.
- Preserve maximum information.
- Improve data visualization.
- Reduce computational complexity.
- Prepare data for machine learning models.

---

# 📂 Dataset

**File:** `student_pca_dataset.xlsx`

### Features

- Study Hours
- Attendance
- Previous Score
- Assignment Score
- Internal Marks

---

# ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenPyXL

---

# 📝 Steps Performed

### Step 1
Load the dataset.

### Step 2
Select the numerical features.

### Step 3
Calculate the mean of every feature.

### Step 4
Standardize the dataset using StandardScaler.

### Step 5
Calculate the covariance matrix.

### Step 6
Calculate Eigenvalues and Eigenvectors.

### Step 7
Apply PCA.

### Step 8
Reduce the dataset from 5 dimensions to 2 principal components.

### Step 9
Visualize the transformed data.

### Step 10
Display the explained variance ratio.

---

# 📊 Outputs

- Dataset Preview
- Mean of Features
- Standardized Data
- Covariance Matrix
- Eigenvalues
- Eigenvectors
- Principal Components
- Explained Variance Ratio
- Before PCA Graph
- After PCA Graph
- Explained Variance Bar Graph

---

# 📈 Graphs

### 1. Before PCA

Shows the original relationship between Study Hours and Attendance.

### 2. After PCA

Shows the transformed dataset using the first two principal components.

### 3. Explained Variance Ratio

Shows how much information is retained by each principal component.

---

# 🌍 Applications

- Face Recognition
- Image Compression
- Medical Diagnosis
- Data Visualization
- Feature Extraction
- Recommendation Systems
- Finance
- Bioinformatics

---

# ✅ Advantages

- Reduces dimensions.
- Removes redundant information.
- Faster model training.
- Better visualization.
- Reduces overfitting.
- Handles correlated features effectively.

---

# ❌ Disadvantages

- Principal components are difficult to interpret.
- Some information is lost.
- Sensitive to feature scaling.
- Works best with linear relationships.

---

# 📚 Conclusion

Principal Component Analysis (PCA) is an effective dimensionality reduction technique that transforms high-dimensional data into a smaller number of principal components while preserving most of the original information. It helps improve visualization, reduces computational cost, and prepares datasets for machine learning algorithms.

---
