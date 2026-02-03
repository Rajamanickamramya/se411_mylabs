# Student Performance Prediction using Machine Learning

## Project Overview
This project predicts the performance of students based on their study habits and other factors using **Linear Regression**.  
It demonstrates an **end-to-end machine learning workflow**, including data creation, exploration, model training, prediction, and evaluation.

---

## Dataset
The dataset contains information about 10 students with the following features:

| Feature               | Description |
|-----------------------|-------------|
| Hours_Studied         | Number of hours the student studied per day |
| Previous_Scores       | Scores obtained in previous exams |
| Sleep_Hours           | Average hours of sleep per day |
| Practice_Papers       | Number of practice papers completed |
| Performance_Index     | Target variable representing overall performance |

> The dataset is **created manually** for demonstration purposes.

---

## Features & Target
- **Input Features (X):** Hours_Studied, Previous_Scores, Sleep_Hours, Practice_Papers  
- **Target Variable (y):** Performance_Index

---

## Tools & Libraries
- **Python 3**  
- **Pandas** – data handling  
- **NumPy** – numerical calculations  
- **Matplotlib** – data visualization  
- **Scikit-learn** – machine learning (Linear Regression)  
- **Google Colab** – online Jupyter Notebook environment  

---

## Workflow
1. **Data Creation & Exploration:**  
   - Created a small dataset with relevant features.  
   - Explored using `info()` and `describe()` to check structure and statistics.

2. **Feature Selection:**  
   - Selected input features (X) and target variable (y).

3. **Train-Test Split:**  
   - Split dataset into 80% training and 20% testing sets.

4. **Model Training:**  
   - Trained a **Linear Regression** model on the training set.

5. **Prediction & Evaluation:**  
   - Predicted performance for test data.  
   - Evaluated using **Mean Squared Error (MSE)** and **R² Score**.  

---

## Results
- **Mean Squared Error (MSE):** 4.35  
- **R² Score:** 0.967  

> The model performs well, accurately predicting student performance.

---

## How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/) or any Jupyter Notebook environment.  
2. Run all cells sequentially.  
3. The notebook will generate predictions and evaluation metrics automatically.

---

## Key Learnings
- End-to-end workflow of a simple **regression project**.  
- Importance of train-test split for evaluating model performance.  
- How to use Linear Regression with multiple input features.  
- How to upload a machine learning project to **GitHub**.

---

## Future Improvements
- Use a **larger, real-world dataset** for better accuracy.  
- Explore other regression models like **Decision Tree Regressor** or **Random Forest Regressor**.  
- Add **data visualization** to better understand feature correlations.

---

## GitHub Repository
https://github.com/Rajamanickamramya/se411_mylabs/blob/main/Student_Performance_prediction.ipynb

---

## Author
Ramya Rajamanickam  
- AI & ML Researcher and Lecturer  
- GitHub: Rajamanickamramya(https://github.com/Rajamanickamramya)
