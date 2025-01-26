# Breast-Cancer-Detection-Diagnosis-and-Classification
## Leveraging machine learning, significally neural networks (NN), offers the potential to automate and enhance diagnostic accuracy, enabling early detection and better patient outcomes.
![Breast Cancer](https://github.com/user-attachments/assets/ff5df2b3-adc9-49ce-8247-856e1b4bceb1)

# Introduction
Breast cancer is one of the most common cancers affecting women globally, with over 2.2 million new cases diagnosed annually. Early detection and accurate diagnosis are crucial for improving survival rates. However, manual interpretation of diagnostic data can be time-consuming and prone to human error. This project leverages machine learning techniques, specifically Artificial Neural Networks (ANN), to automate breast cancer detection and classification, aiming to improve accuracy, efficiency, and patient outcomes.

# Problem Statement
The diagnosis and classification of breast cancer into benign or malignant categories are critical to patient care. Traditional diagnostic methods, while effective, face challenges such as:
- Time-consuming manual analysis.
- Potential for human error.
- Limited capacity for large-scale screening.
The need for advanced machine learning methods is evident to address these challenges and provide a robust, scalable solution for early cancer detection.

# Project Aim
The project aims to develop and evaluate a Neural Network model to:
1. Detect and classify breast cancer cases.
2. Differentiate between benign and malignant diagnoses.
3. Enhance accuracy and reduce misclassification in breast cancer diagnosis.

# Methodology
1. Data Understanding:
   - Dataset: 569 observations with 31 variables, including a diagnosis variable (benign/malignant).
   - Data extracted from digitized fine needle aspirate (FNA) images.
2. Exploratory Data Analysis:
   - Summary statistics and density plots to understand the data distribution.
   - Correlation matrix to identify relationships between variables.
3. Data Preprocessing:
   - Encoding the diagnosis variable as a factor.
   - Splitting the dataset into training (60%) and testing (40%) sets.
   - Ensuring no missing data.
4. Model Development:
   - Building an Artificial Neural Network (ANN) with 15 hidden neurons using the `nnet` package in R.
   - Training the model on the training dataset.
5. Evaluation:
   - Using a confusion matrix and metrics like accuracy, sensitivity, and specificity to evaluate the model's performance.

# Exploratory Data Analysis (EDA)
- The dataset contains a slightly imbalanced class distribution: 63% benign and 37% malignant cases.
- High correlations observed between several variables such as radius, perimeter, and area, indicating their potential relevance in classification.
- Visualization techniques like density plots and correlation heatmaps revealed key insights into the data distribution.

# Key Insights
1. The model achieved an accuracy of 93.8%, indicating reliable classification.
2. Sensitivity (ability to correctly identify malignant cases): 87.5%.
3. Specificity (ability to correctly identify benign cases): 97.7%.
4. High correlations among variables like texture, smoothness, and concavity suggest these features contribute significantly to the diagnosis.

# Recommendations
1. Clinical Integration:
   - Use machine learning-assisted diagnostics to complement manual analysis in hospitals and clinics.
   - Focus on models with high sensitivity to minimize false negatives.
2. Future Enhancements:
   - Incorporate patient history or biopsy results into the model for improved performance.
   - Develop simplified neural architectures to reduce computational complexity while maintaining accuracy.
3. Data Expansion:
   - Use larger, more diverse datasets to improve generalizability.
   - Collect primary data for better control over dataset variability.

# Conclusion
The Neural Network model demonstrated high accuracy and reliability in detecting and classifying breast cancer. By automating the diagnostic process, this project highlights the potential of machine learning to improve healthcare efficiency and reduce diagnostic errors. Future work could explore integrating other clinical data and applying the approach to other medical conditions to expand its utility.
