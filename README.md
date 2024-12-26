# Wine Quality Prediction

This project leverages machine learning to predict the quality of wine based on its physicochemical properties. The predictive system classifies wine into good or bad quality using a **Random Forest Classifier**.

## Overview

Wine quality prediction involves analyzing various chemical attributes of wine, such as acidity, residual sugar, and alcohol content, to determine its quality. This project provides insights into data preprocessing, visualization, and predictive modeling using Python and machine learning libraries.

## Features

- **Data Analysis and Visualization**: 
  - Understand data distributions and correlations using statistical measures and visualizations.
  - Generate heatmaps and bar plots to explore the relationships between wine quality and features.

- **Model Training and Evaluation**:
  - Use a Random Forest Classifier for classification.
  - Evaluate the model using accuracy scores on test datasets.

- **Predictive System**:
  - Input custom physicochemical parameters to predict the quality of wine (good or bad).

## Tools and Libraries Used

- **Python Libraries**: 
  - NumPy, Pandas: For data manipulation and analysis.
  - Matplotlib, Seaborn: For data visualization.
  - Scikit-learn: For machine learning algorithms.
    
## **How to Run**  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/wine-quality-prediction.git
   ```

2. **Install Dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Add Dataset**:  
   ```bash
   Place the winequality-red.csv dataset in the project directory.
   ```

4. **Run the script**:  
   -python Wine_quality_prediction.py

---
## Dataset

The project uses the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality), which contains physicochemical tests of red wine samples and their quality ratings.

## Results

- Achieved an accuracy of **92%** on the test dataset.
- Provides insights into the key factors influencing wine quality.

## Future Scope

- Enhance the model by incorporating other classifiers or tuning hyperparameters.
- Extend to multi-class classification for detailed quality ratings.
- Develop a web-based interface for user-friendly predictions.
