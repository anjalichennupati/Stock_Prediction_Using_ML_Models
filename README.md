# 📈 Stock Price Prediction

This project was part of a college coursework focused on predicting future stock prices using basic machine learning algorithms and data preprocessing techniques. Below is an overview of the analysis, along with sample outputs and results. This project was done in Nov' 2022.
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)


---

### 🚀Installation and Directory Structure

1. **Upload files to Google Colab:**
    - Open [Google Colab](https://colab.research.google.com/).
    - Click on **File** > **Upload notebook** and upload the `.ipynb` file from the `/KNN`, `/SVM`, or `/Decision_Trees` folders.
    - Upload the corresponding `.csv` file from your `/data` folder by using the following code in Colab:
     

2. **Adjust file paths:**
    - After uploading, use the filename directly if the file was uploaded to the Colab environment.
    

3. **Run the code**: Execute the notebook cells one by one to run the model.


- `/data`: Contains all the CSV files used in the project.
- `/KNN and SVM`: Jupyter notebooks related to K-Nearest Neighbors (KNN) model and  Vector Machines (SVM) model.
- `/Decision Trees`: Jupyter notebooks related to Decision Trees model.

---

## 🛠️ Data Pre-processing

- **Libraries Used:**  
  The necessary libraries such as `pandas`, `matplotlib`, `numpy`, and `seaborn` were imported for data manipulation and visualization.

- **Data Import:**  
  The dataset for stock prices (e.g., INFY) was imported using `pandas`.

- **Correlation Analysis:**  
  Correlation between different columns was calculated, and a heatmap was plotted to visualize the correlation matrix.

- **Data Preparation:**  
  The last 72 hours of data were removed, and future close values were predicted.

---

## 🤖 Machine Learning Algorithms

### 1. K-Nearest Neighbors (KNN) Algorithm
- **Training and Testing:**  
  The dataset was split into training and testing sets using `train_test_split`.
- **Model Training:**  
  The `KNeighborsRegressor` model was trained on the training data.
- **Cross Validation:**  
  Cross-validation was performed using the `KFold` method.
- **Accuracy Evaluation:**  
  The accuracy of the model was evaluated.


### 2. Support Vector Machine (SVM) Algorithm
- **Model Training:**  
  A `Support Vector Regressor (SVR)` model with a linear kernel was trained on the training data.
- **R² Score Calculation:**  
  The coefficient of determination (R² score) was calculated to evaluate the model's accuracy.

### 3. Decision Trees Algorithm
- **Model Training:**  
  The `DecisionTreeRegressor` model was trained on the training data.
- **Prediction:**  
  Predictions were made using the trained model.
- **Accuracy Calculation:**  
  The accuracy of the model was calculated.

---

## 📊 Sample Output Analysis

- **Heatmap Plots:**  
  Heatmaps displaying correlations between different aspects of stocks for multiple datasets (e.g., Infosys, Cipla, ICICI).
  ![image](https://github.com/user-attachments/assets/17f0cb9a-c984-4c76-9872-55b2f5d3a539)


- **KNN Plots:**  
  Bar graphs showing actual vs. predicted closing values for each dataset using the KNN algorithm.
  ![image](https://github.com/user-attachments/assets/f549d86b-8ae2-4f54-94cc-f46cb5316f7e)

- **SVM Plots:**  
  Bar graphs illustrating actual vs. predicted closing values for each dataset using the SVM algorithm.
  ![image](https://github.com/user-attachments/assets/d0fe52ee-b8eb-4fd4-9fe0-08dde86796f7)

- **Decision Trees Plots:**  
  Bar graphs displaying actual vs. predicted closing values for each dataset using the Decision Trees algorithm.
  ![image](https://github.com/user-attachments/assets/8cba4c5d-f0b9-40e9-a61d-8b9aca86bc7a)

---

## 📋 Accuracy Summary

Here’s a summary of the accuracy values for each dataset and algorithm:

| Dataset | Algorithm      | Accuracy |
| ------- | -------------- | -------- |
| Infosys | KNN            | 0.985    |
|         | SVM            | 0.982    |
|         | Decision Trees | 0.970    |
| Cipla   | KNN            | 0.959    |
|         | SVM            | 0.955    |
|         | Decision Trees | 0.921    |
| ICICI   | KNN            | 0.976    |
|         | SVM            | 0.978    |
|         | Decision Trees | 0.947    |

---

## 🎯 Conclusion

This project demonstrates the effectiveness of various machine learning algorithms in predicting future stock prices. The analysis reveals that different algorithms perform differently depending on the dataset. Among the chosen datasets, **Infosys** (an MNC) exhibited the highest accuracy, particularly with the **KNN algorithm**. The project concludes by emphasizing the importance of machine learning algorithms in stock price prediction, acknowledging their variability in accuracy depending on the dataset characteristics.

## Running Tests

The project can be implemented and tested to verify funtionality
