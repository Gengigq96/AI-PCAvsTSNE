# Dimensionality Reduction with PCA and t-SNE

This project aims to reduce the dimensionality of a dataset using **PCA (Principal Component Analysis)** and **t-SNE (t-Distributed Stochastic Neighbor Embedding)**. Through these methods, we can effectively visualize the distribution and relationships between data points in a two-dimensional space.

## Description

Dimensionality reduction is a crucial step in exploratory data analysis and visualization. In this project, a dataset is processed by applying PCA and t-SNE to project the original high-dimensional data into a 2D space. This makes it easier to visualize patterns and relationships in the data that might not be immediately apparent in a high-dimensional space.

### Libraries Used

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualizing the results.
- **Seaborn**: For enhancing graphical visualizations with additional features.
- **Scikit-learn**: Used for data standardization, dimensionality reduction (PCA and t-SNE), and classification modeling.
- **NLTK**: For text processing and feature extraction.
- **Latent Dirichlet Allocation (LDA)**: For topic modeling and textual feature extraction.

### Project Steps

1. **Data Preprocessing**:
   - Standardization of data using `StandardScaler`.
   - Tokenization and stopword removal in textual data using **NLTK**.
   - Text feature extraction using `CountVectorizer`.

2. **Dimensionality Reduction**:
   - Application of **PCA (Principal Component Analysis)** to reduce the dimensions of the original dataset.
   - Use of **t-SNE** for more effective visualization in a 2D space.

3. **Visualization**:
   - Generated plots using **Matplotlib** and **Seaborn** to show how the data is distributed in the 2D space after applying PCA and t-SNE.

4. **Modeling**:
   - Built a classification model using **RandomForestClassifier**.
   - Evaluated the model with metrics such as accuracy and classification reports.
