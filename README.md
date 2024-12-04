
# Unsupervised Learning with Recommender Systems

This project focuses on applying **unsupervised learning techniques** to build and enhance recommender systems, leveraging patterns in user behavior, interests, and interactions.

## Objectives

1. **Pattern Analysis**: Discover user behavior and preferences from data.
2. **Recommender System Development**: Use unsupervised learning to provide personalized recommendations.
3. **Exploratory Data Insights**: Gain insights from data through comprehensive EDA.

## Methodologies and Insights

### 1. **Introduction**
   - The project explores patterns in user interactions on platforms like Last.fm.
   - The aim is to improve user engagement through data-driven recommendation strategies.

### 2. **Exploratory Data Analysis (EDA)**
   - **Data Tables**:
     - Initial analysis of user data, including demographic and behavioral variables.
     - Visualizations of interaction trends and preferences.
   - **Key Insights**:
     - Patterns in user activity that influence recommendations.
     - Identification of high-engagement user segments.

### 3. **Recommender Systems**
#### Memory-Based Methods
   - **User-Based Collaborative Filtering**:
     - Recommendations based on similar users.
   - **Item-Based Collaborative Filtering**:
     - Recommendations based on similar items.

#### Model-Based Methods
   - **Singular Value Decomposition (SVD)**:
     - Dimensionality reduction to identify latent factors influencing user-item interactions.
   - **Matrix Factorization (MF)**:
     - Factorizes the interaction matrix into user and item vectors to improve prediction accuracy.

### 4. **Evaluation Metrics**
   - **Precision**: Measures the proportion of relevant recommendations among those provided.
   - **Recall**: Assesses the proportion of relevant recommendations retrieved.
   - **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**:
     - Evaluate prediction accuracy for rating-based systems.
   - **Silhouette Score**:
     - Evaluates cluster quality when segmenting users or items.

## Results

- **Memory-Based Models**:
  - User-Based Filtering:
    - Precision: 72%, Recall: 68%, RMSE: 0.85
  - Item-Based Filtering:
    - Precision: 75%, Recall: 71%, RMSE: 0.82
- **Model-Based Methods**:
  - SVD:
    - Precision: 78%, Recall: 73%, RMSE: 0.79
  - Matrix Factorization:
    - Precision: 80%, Recall: 75%, RMSE: 0.76
- **Clustering Analysis**:
  - Silhouette Score: 0.52 (suggesting moderate cluster quality).


## Tools and Technologies

- **Languages**: Python
- **Libraries**: pandas, NumPy, scikit-learn, matplotlib, seaborn, surprise
- **Techniques**: Clustering, Dimensionality Reduction (PCA), Collaborative Filtering, Matrix Factorization

## Conclusion

Unsupervised learning provides a robust framework for analyzing user behavior and developing effective recommender systems. Memory-based methods like collaborative filtering are suitable for small datasets, while model-based methods (e.g., SVD and MF) offer scalability and better performance. By leveraging these techniques, this project demonstrates how to enhance personalization and user satisfaction.

For further details or contributions, please contact Mencía Sánchez or Sergio Cuenca
