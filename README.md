🚗 Ford Car Price Prediction Model

This repository contains a machine learning project dedicated to predicting the price of used Ford cars using a dataset containing various features like mileage, engine size, fuel type, and transmission.

The primary goal is to apply regression techniques to build an accurate predictive model that can estimate the market value of a Ford vehicle.

🌟 Key Features

Exploratory Data Analysis (EDA): Visualization and analysis of key features (e.g., correlation between mileage and price).

Data Preprocessing: Handling categorical variables using one-hot encoding.

Model Training: Implementation and training of a Linear Regression Model.

Model Evaluation: Assessment of model performance using metrics like R-squared, MAE, and MSE.

🛠 Project Structure and Files

File

Description

ford-car-price-prediction.ipynb

The Jupyter Notebook containing all the code for data loading, preprocessing, model creation, and evaluation.

ford.csv

The raw dataset used for training the model.

requirements.txt

Lists all necessary Python dependencies (libraries) to run the notebook successfully.

.gitignore

Ensures development environment files (like .ipynb_checkpoints and venv/) are not tracked by Git.

🚀 How to Run the Project

To set up the project locally and run the analysis:

1. Clone the Repository

git clone [https://github.com/ayush1k/Ford-Car-Price-Prediction.git](https://github.com/ayush1k/Ford-Car-Price-Prediction.git)
cd Ford-Car-Price-Prediction



2. Install Dependencies

You need Python and pip installed. The required libraries are listed in requirements.txt.

pip install -r requirements.txt


3. Run the Notebook

Launch a Jupyter environment and open the core notebook:

jupyter notebook ford-car-price-prediction.ipynb


You can then execute the cells sequentially to see the data processing, model training, and final predictions.

💡 Technologies Used

Python (3.x)

Jupyter Notebook

Pandas (for data manipulation)

NumPy (for numerical operations)

Scikit-learn (sklearn) (for model implementation and evaluation)

Matplotlib/Seaborn (for data visualization)

📊 Results Summary

The model was trained using features such as mileage, year, engineSize, and encoded categorical variables (model, fuelType, transmission).

The final model evaluation provided the following insights:

Metric

Result

R-squared
0.8396626991294074

R-squared Score
0.8387377808685319


🔗 Connect with Me

💼 LinkedIn

🐦 Twitter

📧 ayushkumar47834@gmail.com
