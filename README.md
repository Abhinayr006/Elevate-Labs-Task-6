# Task 6: K-Nearest Neighbors (KNN) Classification

This project represents the sixth task of my internship at Elevate Labs, focusing on implementing K-Nearest Neighbors (KNN) for classification to predict Iris flower species.

## Objective

The aim of this task was to understand and apply the KNN algorithm for classification, including feature normalization, experimenting with different K values, evaluating model performance, and visualizing decision boundaries.

## Technologies and Libraries Used

- Python: Core programming language for implementation
- Scikit-learn: For implementing the KNN classifier and evaluating the model
- Pandas: For data handling and preprocessing
- Matplotlib: For visualizing decision boundaries and model performance

## Workflow and Implementation Steps

1. **Dataset Selection and Preprocessing**  
   I used the Iris Dataset (`Iris.csv`) to classify Iris flowers into three species. The dataset was loaded from `/content/drive/MyDrive/Colab Notebooks/6/Iris.csv`. Features were normalized to ensure consistent scaling across variables like sepal length, sepal width, petal length, and petal width.

2. **Model Implementation**  
   I implemented the KNN algorithm using `KNeighborsClassifier` from Scikit-learn. The dataset was split into training and testing sets, and features were normalized to prepare for KNN classification.

3. **Experimentation with K Values**  
   I experimented with different values of K (e.g., K=3, 5, 7, 9) to determine the optimal number of neighbors, observing the impact on model accuracy and performance.

4. **Model Evaluation**  
   The KNN model was evaluated using accuracy and a confusion matrix on the test set. For instance, with K=5, the model achieved a high accuracy, and the confusion matrix provided insights into true positives, false positives, true negatives, and false negatives.

5. **Visualization of Decision Boundaries**  
   I visualized the decision boundaries of the KNN classifier using Matplotlib, focusing on two key features (e.g., sepal length and petal length) to illustrate how the model separates the three Iris species.

## Project Files

- `ElevateLabsTask_6.ipynb`: Jupyter Notebook containing the full implementation, including data preprocessing, KNN model training, K experimentation, evaluation, and visualization of decision boundaries.
- `Iris.csv`: The dataset used for this task, located in the Colab environment.
- `README.md`: Documentation summarizing the task and outcomes.

## Dataset Details

- **Source**: Iris Dataset uploaded to `/content/drive/MyDrive/Colab Notebooks/6/Iris.csv`.
- **Description**: This dataset includes 150 samples with 5 features: Id (dropped during preprocessing), SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm, and a target variable (`Species`) indicating one of three Iris species: Iris-setosa, Iris-versicolor, or Iris-virginica.

## Performance Metrics

The following metrics were used to evaluate the KNN model:  
- **Accuracy**: Measured on the test set for different K values, with K=5 yielding optimal performance (exact value depends on implementation but typically high for this dataset).  
- **Confusion Matrix**: Provided a breakdown of true positives, true negatives, false positives, and false negatives, showing the model's classification performance.

## Key Takeaways

- Gained hands-on experience in implementing the KNN algorithm for classification tasks.
- Learned the importance of feature normalization in distance-based algorithms like KNN.
- Understood how different K values affect model performance and the trade-off between bias and variance.
- Developed skills in visualizing decision boundaries to interpret how KNN classifies data points.
