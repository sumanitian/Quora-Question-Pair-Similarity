# Quora-Question-Pair-Similarity

This project aims to identify duplicate questions on Quora, leveraging machine learning techniques. By detecting duplicate questions, we can improve the user experience by reducing redundancy and providing more accurate and relevant answers.

<h1>Overview</h1>

Quora, a popular question-and-answer platform, often encounters similar or duplicate questions posted by different users. Identifying these duplicates manually can be time-consuming and inefficient. Therefore, this project focuses on automating the process using machine learning algorithms.

<h1>Duplicate Detection Methods</h1>

To detect duplicate questions, we explore various machine learning models, including Logistic Regression, Linear Support Vector Machines (SVM), and XGBoost. These models are trained on a labeled dataset of question pairs, with each pair labeled as either duplicate or non-duplicate.

Logistic Regression and Linear SVM are traditional linear models known for their simplicity and interpretability. XGBoost, on the other hand, is a powerful ensemble learning algorithm that combines multiple weak learners to create a strong predictive model.

<h1>Model Performance</h1>

During model evaluation, we consider metrics such as precision, recall, and accuracy to assess the performance of each model. Precision measures the proportion of correctly predicted duplicate questions out of all predicted duplicates, while recall measures the proportion of correctly predicted duplicate questions out of all actual duplicates. The goal is to maximize both precision and recall to achieve accurate duplicate detection.

Among the models tested, XGBoost performs exceptionally well, surpassing the linear models in terms of precision, recall, and overall accuracy. The XGBoost model demonstrates significant improvements, particularly in the precision and recall for class 1, which represents duplicate questions.

Furthermore, the XGBoost test-log, a measure of log loss, achieves the lowest value (0.35%) compared to other machine learning models. This indicates that the XGBoost model provides more confident and reliable predictions.

<h1>Conclusion</h1>

This project successfully develops a machine learning-based solution for duplicate question detection on Quora. By comparing question pairs and leveraging models such as Logistic Regression, Linear SVM, and XGBoost, we can identify duplicate questions accurately.

The XGBoost model emerges as the top performer, outperforming the linear models in terms of precision, recall, and overall accuracy. The model's ability to minimize log loss indicates its strong predictive capabilities and improved confidence in duplicate question predictions.

By automating the process of duplicate question detection, Quora can enhance the user experience by reducing redundancy and providing more accurate answers to its users.

Moving forward, this solution can be further integrated into the Quora platform to improve question search, recommendation systems, and moderation processes. The model can be continuously optimized and updated to handle evolving patterns of duplicate questions effectively.
