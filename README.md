Height Prediction using Simple Linear Regression

This project demonstrates a Simple Linear Regression model that predicts a person’s height (cm) from their weight (kg). The dataset is taken from Kaggle, and the project uses popular Python libraries for data analysis, visualization, and machine learning.

📊 Dataset

The dataset is sourced from Kaggle (Height-Weight dataset).

Feature (X): Weight (kg)

Target (y): Height (cm)

No missing values

🛠️ Technologies & Libraries Used

NumPy → numerical computations

Pandas → data handling and preprocessing

Matplotlib → data visualization

Seaborn → statistical plots

scikit-learn → model training and evaluation

⚙️ Workflow

Import Dataset

Load the dataset from Kaggle using Pandas.

Exploratory Data Analysis (EDA)

Summary statistics of height & weight

Visualizations using Matplotlib and Seaborn (scatter plots, distribution plots, regression line)

Data Preprocessing

Check for null values (none present)

Train-test split

Model Training

Apply Simple Linear Regression from sklearn.linear_model

Fit model on training data

Model Evaluation

Predictions on test data

Evaluation metrics: R² Score, MAE, RMSE

Visualization

Plot regression line on scatterplot of height vs. weight

📈 Results

The model shows a positive correlation between weight and height.
R-squared (uncentered):                   0.004
Adj. R-squared (uncentered):             -0.024
slope of the train data is  [10.07430396]
intercept of the train data is  169.21621621621622
📌 Future Improvements

Add multiple features (age, gender, BMI) for better accuracy

Try Polynomial Regression and other models

Deploy model with Flask / Streamlit for interactive predictions

📂 Repository Structure
height-prediction/
│-- data/                 # Kaggle dataset (Height-Weight.csv)
│-- Height_Prediction.ipynb
│-- README.md
│-- requirements.txt

📜 License

This project is open-source and available under the MIT License.
