# Used Cars Price Prediction using Machine Learning

This project aims to predict the selling price of used cars based on various features like car brand, manufacturing year, fuel type, kilometers driven, and more. Built using Python and machine learning algorithms, the model assists potential car buyers and sellers in making informed pricing decisions.

---

## Overview

The goal of this project is to develop a regression model that can accurately predict the price of a used car based on relevant attributes. A clean, preprocessed dataset is used to train multiple models, and the best-performing one is selected based on performance metrics like R² score and RMSE.

---

## Features Used

- Car Name / Brand  
- Year of Manufacture  
- Fuel Type  
- Transmission Type  
- Number of Owners  
- Kilometers Driven  
- Seller Type  
- Present Price  
- Other categorical & numerical features  

---

## Machine Learning Techniques

- **Data Cleaning & Preprocessing**
  - Handling missing values
  - One-hot encoding for categorical variables
  - Feature scaling (if needed)

- **Modeling**
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest Regressor
  - XGBoost Regressor

- **Model Evaluation**
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - Cross-validation

---

## Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Jupyter Notebook**

---

## Results

- The best-performing model achieved an **R² Score of ~0.89**, showing strong predictive power for real-world use cases.
- The model generalizes well across various car segments and price ranges.

---

## Future Improvements

- Deploy as a web application using Flask or Streamlit
- Real-time scraping of used car data from websites like CarDekho or OLX
- UI to allow users to input car details and get price predictions instantly

---

## Project Structure

```bash
.
├── Client/                            # Frontend files (HTML/CSS/JS)
├── Server/                            # Backend server files (Flask or Streamlit)
├── Car.jpg                            # Project illustration/image
├── README.md                          # Project documentation
├── Untitled.ipynb                     # Jupyter Notebook for model development
├── cardekho_dataset.csv              # Raw dataset
├── cleaned_cardekho_dataset.csv      # Preprocessed dataset


