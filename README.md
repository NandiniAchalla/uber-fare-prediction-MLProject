# 🚖 Uber Fare Prediction — Machine Learning Project
Overview
This project predicts Uber ride fares using machine learning algorithms. It features a user-friendly interface and geo-map integration for location selection, ensuring seamless and accurate fare estimation.
It predicts Uber ride fares based on trip distance, pickup and dropoff locations, and time-related features.  
It compares **Linear Regression** and **Random Forest Regressor** models to determine which algorithm provides better prediction accuracy.

This project was completed during my **Google – AI/ML Virtual Internship (EduSkills)**.

## ⚙️ Tech Stack
- **Programming:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn  
- **Environment:** spyder(Anaconda Navigator) 

## 🧩 Key Objectives
- Perform **data cleaning** and handle missing values.  
- Implement **feature engineering** (distance calculation, time-based features).  
- Train and evaluate **regression models** (Linear Regression, Random Forest).  
- Measure performance using **R², RMSE, and MSE** metrics.  
- Visualize relationships and model predictions for interpretability.  

## 🧠 Dataset
- Source: Uber Ride dataset (Kaggle)  
- Features include:
  - `pickup_datetime`
  - `pickup_longitude`
  - `pickup_latitude`
  - `dropoff_longitude`
  - `dropoff_latitude`
  - `passenger_count`
  - `fare_amount`

## 🚀 Implementation Steps
1. **Data Preprocessing**
   - Removed null and invalid values  
   - Filtered unreasonable coordinates and fare values  
   - Calculated distance between pickup and drop locations using the Haversine formula  

2. **Exploratory Data Analysis (EDA)**
   - Visualized fare distribution and distance-fare correlation  
   - Analyzed impact of passenger count and trip time  

3. **Model Building**
   - Implemented Linear Regression and Random Forest Regressor  
   - Tuned hyperparameters for Random Forest using GridSearchCV  

4. **Model Evaluation**
   Model:Linear Regression
   R² Score:0.86
   RMSE:2.93
   MSE:8.59

   Model:Random Forest
   R² Score:0.93
   RMSE:2.15
   MSE:4.62

   ✅ **Random Forest** outperformed Linear Regression in predictive accuracy.
   
**Installation:**
- Clone the repository.  
- git clone https://github.com/your-username/uber-fare-prediction.git 
- Navigate to the project directory.  
- cd uber-fare-prediction.  

**Install dependencies:**
pip install -r requirements.txt  

**Run the application:**
python app.py  

->Access the interface in your browser at http://localhost:5000.

->Select pickup and drop-off locations on the map, and view the predicted fare.

**Project Highlights:**
*Clean and well-documented code.
*Robust data preprocessing pipeline.
*User-friendly design with integrated map functionality.
*Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
