## 🎬 Singapore HDB Resale Flat Prices Project

## 📖 Overview

The Singapore HDB Resale Flat Prices Project is focused on analyzing historical resale flat transactions and predicting resale prices in Singapore using a Random Forest model.  
The project demonstrates data cleaning, feature engineering, predictive modeling, and deployment using Streamlit.


## 🎯 Project Objectives

- Clean and preprocess HDB resale flat data to ensure quality  
- Understand how factors like location, flat type, floor area, and remaining lease affect resale prices  
- Build a Random Forest model to accurately predict resale prices  
- Deploy the model using Streamlit for interactive user predictions  


## 🧩 Dataset Details

*Source:* [HDB Resale Flat Prices – data.gov.sg]( https://beta.data.gov.sg/collections/189/view )  
*Number of Records:* ~200,000 transactions  

*Key Features:*

- town – HDB town name  
- flat_type – Type of flat (e.g., 3 ROOM, 4 ROOM)  
- block – Block number  
- street_name – Street name  
- floor_area_sqm – Floor area in square meters  
- flat_model – Flat model type  
- lease_commence_date – Year lease started  
- remaining_lease – Remaining lease years  
- resale_price – Resale price in SGD  


## 🧠 Tools & Technologies Used

*Language:* Python 🐍  

*Libraries:*

- Data Handling → pandas, numpy  
- Machine Learning → scikit-learn (Random Forest Regressor)  
- Deployment → Streamlit  


## 🧹 Data Cleaning & Preprocessing

Preprocessing steps included:

- Handling missing or inconsistent values in key columns  
- Converting data types (e.g., dates and numeric values)  
- Extracting resale year from transaction date  
- Encoding categorical variables  
- Handling outliers in floor area and resale price  
- Removing duplicate records  


## 📊 Analysis & Modeling

- Built a *Random Forest Regressor* to predict resale prices  
- Used key features like town, flat type, floor area, flat model, and remaining lease  
- Evaluated model performance using metrics like RMSE, MAE, and R²  


## 🚀 Deployment

- The trained Random Forest model was deployed using *Streamlit*  
- Users can input flat details (town, flat type, floor area, etc.) and get a predicted resale price  


## 🔮 Future Improvements

- Integrate additional datasets such as nearby amenities, MRT access, or neighborhood facilities  
- Explore advanced machine learning models like XGBoost or LightGBM for better accuracy  
- Implement automated model retraining with new resale transactions  
- Develop a more interactive dashboard with filters and price comparisons  
- Add feature importance visualization for better model interpretability  


## 📁 Project Structure

Singapore_HDB_Resale_Prices/ ├── data/ │   └── combined_resale_flat_prices.csv ├── notebooks/ │   └── HDB_Resale_Model.ipynb ├── models/ │   └── hdb_price_model.pkl ├── app/ │   └── streamlit_app.py ├── requirements.txt └── README.md


## 💡 Learning Outcomes

- Data cleaning and preprocessing of real-world datasets  
- Feature engineering for predictive modeling  
- Training and evaluating a Random Forest regression model  
- Deploying a machine learning model using Streamlit  


## 👤 Author

Palagiri Reshma  
📧 [reshmapalagiri1807@gmail.com]  
💼 [www.linkedin.com/in/palagiri-reshma]  
🌐 [https://github.com/reshmapalagiri-ds]
