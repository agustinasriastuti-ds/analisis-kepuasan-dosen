# Lecturer Satisfaction Analysis: PCA vs t-SNE

## 📌 Project Overview

This project analyzes student evaluation data of lecturers using two dimensionality reduction techniques: **Principal Component Analysis (PCA)** and **t-SNE (t-Distributed Stochastic Neighbor Embedding)**.

The analysis aims to explore patterns in high-dimensional lecturer evaluation data and compare how PCA and t-SNE represent the data in a lower-dimensional space.

## 📊 Dataset

The dataset contains **14,334 student evaluation records** with **10 Likert-scale evaluation variables** measuring different aspects of lecturer performance.

The evaluation scores use a scale from **1 to 5**.

Due to data privacy considerations, the original dataset is not publicly uploaded to this repository.

## 🎯 Objectives

The objectives of this project are to:

- Analyze patterns in student lecturer-evaluation data.
- Reduce the dimensionality of the evaluation variables.
- Compare PCA and t-SNE as dimensionality reduction techniques.
- Visualize the structure of the evaluation data in two-dimensional space.
- Explore patterns that may support further evaluation and analysis.

## ⚙️ Methods

### 1. Principal Component Analysis (PCA)

PCA was used to transform the original evaluation variables into principal components while preserving as much variance in the data as possible.

The first two principal components explained approximately:

- **PC1: 79.779%**
- **PC2: 4.219%**
- **Cumulative variance: 83.998%**

### 2. t-SNE

t-SNE was used to visualize the high-dimensional evaluation data in a two-dimensional space and explore local patterns and similarities among observations.

## 🔄 Data Processing

The analysis workflow included:

1. Data inspection
2. Data cleaning
3. Feature selection
4. Data standardization using `StandardScaler`
5. Dimensionality reduction using PCA
6. Dimensionality reduction using t-SNE
7. Visualization and interpretation

## 📈 Visualization

The project includes:

- PCA two-dimensional scatter plot
- t-SNE two-dimensional visualization
- Comparison of data representation between PCA and t-SNE

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🔍 Key Findings

The analysis showed that:

- PCA was able to represent a large proportion of the total variance using the first two principal components.
- The first two PCA components explained approximately **83.998% of the total variance**.
- t-SNE provided a two-dimensional visualization that helped explore local patterns within the evaluation data.
- PCA and t-SNE provide different perspectives when visualizing high-dimensional evaluation data.

## 💡 Business / Academic Relevance

The analysis can support institutions in exploring large-scale student evaluation data and identifying patterns that may be useful for further academic evaluation and teaching-quality improvement.

## 🚀 Future Improvements

Future development of this project could include:

- Interactive dashboard development using Power BI or Looker Studio.
- Applying clustering techniques such as K-Means to identify groups based on evaluation patterns.
- Comparing additional dimensionality reduction techniques.
- Developing a classification model for further analysis.

## 📁 Project Structure

```text
analisis-kepuasan-dosen/
│
├── README.md
├── notebook.ipynb
└── images/
    └── visualization-results.png

## Autor
Agustina Sri Astuti, S.Kom., M.Kom.
IT Business Analyst | Data & Business Analytics
    
