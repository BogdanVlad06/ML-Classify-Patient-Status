# ML-Classify-Patient-Status

## Description
This project uses machine learning techniques to classify patient status as dead or alive based on medical features, utilizing various classification models and evaluation metrics.
For more information, refer to the task description: [Nitro AI Problem Statement](https://judge.nitro-ai.org/roai-2025/simulare-ojia-2/problems/1/task)

## Tools Used
- **Development Environment**: Jupyter Lab
- **Modules**: `pandas`, `scikit-learn`
- **Models**: Logistic Regression and Random Forest Classifier.
- **Data**: Patient health records dataset with features such as tumor size, blood pressure, etc.

## Steps
1. **Data Preprocessing**: Clean and preprocess the dataset, handling missing values, encoding categorical features and scale numerical attributes.
2. **Model Training**: Train different classification models (Logistic Regression, Random Forest) and tune hyperparameters.
3. **Feature Selection**: Experiment with different feature to identify the most impactful ones.
4. **Evaluation**: Evaluate model performance using 'Dead' class precision.

## Final Thoughts
This project has provided valuable insights into the process of building and refining machine learning models. By experimenting with feature selection, data preprocessing, and evaluating model performance using cross-validation, I was able to identify which features had the most impact on the outcome.

Through this project, I gained a deeper understanding of how even small adjustments, such as dropping or adding specific features can drastically affect model performance. The comparison between models, especially Random Forest and Logistic Regression, further highlighted the importance of choosing the right model for the task at hand.

While the final model shows strong performance, there are still opportunities for further improvement, such as other encoding methods, experimenting with more advanced algorithms, or incorporating additional data sources. This process also emphasized the importance of continuous iteration and validation to ensure the model is robust and generalizable.

Overall, this project has not only strengthened my machine learning skills but also reinforced the value of a systematic, data-driven approach to model development.
