# 20Newsgroup Analysis

This project focuses on the analysis and classification of the 20 Newsgroups dataset, which contains approximately 20,000 newsgroup documents, partitioned across 20 different categories. The objective was to explore clustering and classification techniques to distinguish between these categories based on the textual content.

## Project Structure

1. **KMeans Clustering & WordClouds**:
   - Applied KMeans clustering to group the documents.
   - Generated word clouds for each of the 20 categories to visualize the most common words in each cluster.

2. **Classification Models**:
   - **Neural Network (PyTorch)**:
     - Built a neural network using PyTorch.
     - Achieved an accuracy of 68% on the test set.
   - **Logistic Regression**:
     - Applied Logistic Regression, which provided the best results.
     - Achieved an accuracy of 72.2%.
   - **Random Forest Classifier**:
     - Used RandomForestClassifier, which resulted in an accuracy of 64.7%.

3. **Custom Message Classification**:
   - Tested custom messages with both the Neural Network and Logistic Regression models.
   - Both models correctly predicted the categories for the custom messages.

## Key Findings

- **Best Performance**: Logistic Regression outperformed the other models, achieving an accuracy of 72.2%, indicating that it was the most effective method for this dataset.
- **Model Insights**:
  - The Neural Network model, although not the top performer, still provided reasonable accuracy.
  - The RandomForestClassifier had the lowest accuracy among the three models, showing that it may not be the best choice for this text classification task.
- **Custom Message Prediction**: The successful classification of custom messages by both the Neural Network and Logistic Regression models suggests robustness in handling unseen data.

## Requirements

- Python 3.x
- pandas
- numpy
- PyTorch
- scikit-learn
- matplotlib
- wordcloud
- nltk

## Conclusion

This project highlights the challenges and opportunities in text classification, showcasing the importance of model selection and feature engineering. Logistic Regression emerged as the best-performing model for the 20 Newsgroups dataset, while the custom message testing further validated the robustness of the models.
