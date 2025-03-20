**Used Bike Price Prediction Using AI**

*📌 Project Overview*

Used bike prices can vary based on multiple factors such as brand, age, kilometers driven, and ownership history. This project utilizes artificial intelligence and machine learning to build a predictive model that estimates the price of a used bike based on these features. By analyzing historical bike sales data, we aim to develop an accurate and efficient pricing model to assist both buyers and sellers in making informed decisions.

**🎯 Objectives**

*Data Collection: Gather historical bike sales data with relevant attributes.
*Data Preprocessing: Handle missing values, encode categorical variables, and remove outliers.
*Data Visualization: Analyze feature relationships through graphs and statistical insights.
*Model Selection: Train and compare multiple regression models.
*Evaluation & Validation: Assess model performance using various metrics (R², MSE, MAE) and validate the best-performing model.

**📂 Project Structure**

"D:\Git\Picture1.png"
**📊 Dataset**

Source: Kaggle ([](url)Used Bikes Prices in India)
Size: 32,648 records
Features:
bike_name: Name of the bike
price: Target variable (bike price)
city: City of listing
kms_driven: Kilometers driven
owner: Ownership type (First, Second, etc.)
age: Age of the bike
brand: Bike manufacturer
power: Engine power (if available)

🏗 Methodology

1️⃣ Data Preprocessing

->Feature encoding for categorical variables
->Handling missing values
->Outlier detection and treatment using kurtosis analysis
->Normalization of numerical features

2️⃣ Model Selection

The following machine learning regression models were implemented:

*Linear Regression
*K-Nearest Neighbors (KNN)
*Naïve Bayes
*Random Forest Regression (Best-performing model)

3️⃣ Evaluation Metrics
R² Score :Measures the goodness of fit
Mean Squared Error (MSE) :Evaluates the average squared difference between actual and predicted values
Mean Absolute Error (MAE): Determines the absolute difference between actual and predicted prices

🔥 Results

Best Model: Random Forest Regression
->Performance:

R² Score: 99.86%
MAE: 700.0
MSE: 3,980,347.6

*The model shows high accuracy and generalizability on test data.

📌 Key Insights

*Bikes with the first ownership have higher prices.
*Higher age & kilometers driven negatively impact price.
*Certain brands hold better resale value than others.
*Outliers in the dataset were effectively handled using kurtosis.

🔮 Future Enhancements

->Implement deep learning models like LSTM for better accuracy.
->Explore alternative outlier detection methods like Principal Component Analysis (PCA).
->Perform feature selection to optimize the model’s performance.
->Integrate a web application where users can input bike details and get price predictions.

📌 How to Run the Project

*Clone the Repository
*Install Dependencies
*Run the Jupyter Notebook

Open Used_Bike_Price_Prediction.ipynb and execute the cells.

👨‍💻 Technologies Used

*Python* :(NumPy, Pandas, Matplotlib, Scikit-Learn, Seaborn)
*Machine Learning *:(Regression Models)
*Data Visualization*: (Matplotlib, Seaborn)
