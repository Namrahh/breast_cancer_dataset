##  Model Comparison – Breast Cancer Classification

This project compares the performance of different machine learning algorithms on the Breast Cancer dataset.

###  Model Results:

| Model               | Features Used        | Accuracy |
|--------------------|----------------------|----------|
| KNN                | Original (scaled)    | 95%      |
| Naive Bayes        | Original (scaled)    | 96%      |
| SVM                | Original (scaled)    | 98%      |
| Random Forest      | PCA-reduced (2D)     | 98%      |

###  Key Takeaways:
- **SVM** and **Random Forest with PCA** performed best (98%).
- **PCA** effectively reduced dimensionality without loss in accuracy.
- **Naive Bayes** and **KNN** gave solid performance as well.
