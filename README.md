# Scientific Report on Breast Cancer Diagnosis Classification
### Introduction: <br>
Breast cancer is one of the most prevalent forms of cancer among women worldwide. Early detection and accurate classification of breast tumors are crucial for effective treatment and prognosis. In this study, we analyzed the Breast Cancer Wisconsin Diagnostic dataset to develop machine learning models for classifying tumors as benign or malignant based on their shape and geometry features.
<br><br>
### Dataset Description:<br>
The dataset contains features computed from digitized images of breast mass samples, including characteristics such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. Each sample is labeled as benign (B) or malignant (M), representing the two classes of breast tumors.

Here's an explanation of the columns present in the dataset:
1.	ID: Unique identifier for each sample.
2.	Diagnosis: The target variable indicating the classification of the tumor as either benign (B) or malignant (M).
3.	Radius Mean: Mean of distances from the center to points on the perimeter of the tumor mass.
4.	Texture Mean: Standard deviation of gray-scale values in the image, representing the variation in texture.
5.	Perimeter Mean: Mean size of the tumor mass perimeter.
6.	Area Mean: Mean size of the tumor mass area.
7.	Smoothness Mean: Mean of local variation in radius lengths.
8.	Compactness Mean: Measure of how compact the shape of the tumor mass is.
9.	Concavity Mean: Severity of concave portions of the tumor mass.
10.	Concave Points Mean: Number of concave portions in the tumor mass.
11.	Symmetry Mean: Symmetry of the tumor mass.
12.	Fractal Dimension Mean: Measure of complexity of the tumor mass boundary.
13.	Radius SE: Standard error of distances from the center to points on the perimeter.
14.	Texture SE: Standard error of gray-scale values, indicating the variation in texture.
15.	Perimeter SE: Standard error of tumor mass perimeter.
16.	Area SE: Standard error of tumor mass area.
17.	Smoothness SE: Standard error of local variation in radius lengths.
18.	Compactness SE: Standard error of tumor mass compactness.
19.	Concavity SE: Standard error of concave portions of the tumor mass.
20.	Concave Points SE: Standard error of concave portions in the tumor mass.
21.	Symmetry SE: Standard error of tumor mass symmetry.
22.	Fractal Dimension SE: Standard error of tumor mass fractal dimension.
23.	Radius Worst: Worst or largest mean value for radius in the tumor mass.
24.	Texture Worst: Worst or largest mean value for texture in the tumor mass.
25.	Perimeter Worst: Worst or largest mean value for perimeter in the tumor mass.
26.	Area Worst: Worst or largest mean value for area in the tumor mass.
27.	Smoothness Worst: Worst or largest mean value for smoothness in the tumor mass.
28.	Compactness Worst: Worst or largest mean value for compactness in the tumor mass.
29.	Concavity Worst: Worst or largest mean value for concavity in the tumor mass.
30.	Concave Points Worst: Worst or largest mean value for concave points in the tumor mass.
31.	Symmetry Worst: Worst or largest mean value for symmetry in the tumor mass.
32.	Fractal Dimension Worst: Worst or largest mean value for fractal dimension in the tumor mass.
Each of these features provides valuable information about the characteristics of breast tumors, aiding in the diagnosis and classification process.

### Methodology:<br>
We applied seven classification techniques to the dataset: Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Logistic Regression, Naive Bayes, Gradient Boosting, and XGBoost. For model evaluation, we used stratified k-fold cross-validation with five folds to ensure robust performance assessment.<br>
#### Results:<br>
Here are the evaluation scores for each model:<br>
•	Random Forest:<br>
•	Accuracy: 96.49%
•	Precision: 93.33%
•	Recall: 97.67%
•	F1-score: 95.45%<br><br>
•	SVM:
•	Accuracy: 93.86%
•	Precision: 95.00%
•	Recall: 88.37%
•	F1-score: 91.57%
•	KNN:
•	Accuracy: 95.61%
•	Precision: 91.11%
•	Recall: 97.62%
•	F1-score: 94.25%
•	Logistic Regression:
•	Accuracy: 97.35%
•	Precision: 100.00%
•	Recall: 92.86%
•	F1-score: 96.30%
•	Naive Bayes:
•	Accuracy: 96.49%
•	Precision: 95.35%
•	Recall: 95.35%
•	F1-score: 95.35%
•	Gradient Boosting:
•	Accuracy: 97.35%
•	Precision: 97.56%
•	Recall: 95.24%
•	F1-score: 96.39%
•	XGBoost:
•	Accuracy: 97.37%
•	Precision: 93.48%
•	Recall: 100.00%
•	F1-score: 96.63%
Conclusion:
Based on the evaluation scores, we observe that logistic regression achieved the highest accuracy among all models (97.35%). However, considering other metrics such as precision, recall, and F1-score, gradient boosting and XGBoost demonstrate competitive performance.
Recommendations:
•	Further investigation into feature engineering: Exploring additional feature engineering techniques or selecting a subset of informative features could potentially enhance model performance.
•	Ensemble techniques: Experimenting with ensemble methods such as stacking or blending multiple models could further improve classification accuracy.
•	Regularization: Implementing regularization techniques to prevent overfitting and improve generalization of the models.
•	Interpretability: Considering the interpretability of models, particularly for medical applications, could aid in understanding the underlying factors contributing to tumor classification decisions.
Overall, the developed models demonstrate promising performance for breast cancer diagnosis classification, providing valuable support for healthcare professionals in early detection and treatment planning.
