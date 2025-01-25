# EEG Eye State Classification Using SVM
This project focuses on analyzing and classifying EEG eye state data using machine learning techniques, specifically a Support Vector Machine (SVM) classifier. The key steps in the code are outlined below:

### Data Preparation:
A random sample of 2000 entries from the EEG dataset is selected for analysis. Quantile transformation is applied to normalize the features, which helps reduce noise and improve model performance. Outliers are managed using Winsorization, based on the interquartile range, to mitigate the impact of unusual data points on the model. The dataset is then standardized using StandardScaler, ensuring that features are on a similar scale for optimal performance of machine learning algorithms.

### Model Training:
An SVM classifier is chosen for its accuracy and efficiency in classification tasks. Hyperparameter tuning is performed using GridSearchCV, which involves testing various configurations to identify the best-performing model settings.

### Model Evaluation:
After training, the model's performance is evaluated using multiple metrics, including accuracy, precision, recall, and F1 score. Visual analyses such as confusion matrices and precision-recall curves are generated to provide deeper insights into the model's performance, strengths, and weaknesses.

This project serves as an effective framework for analyzing EEG data and can be extended to other classification tasks within the fields of neuroscience and psychology. Its results can have applications in various areas, including mental health diagnosis and biomedicine.
