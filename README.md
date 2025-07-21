# END-TO-END-DATA-SCIENCE-PROJECT

*COMPANY*: COOTECH IT SOLUTIONS

*Name*: SATENDRA VEER SINGH

*INTERN ID*: CT04DG3324

*DOMIAN*: DATA SCIENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH


#Description of the Task


### **House Price Prediction Project in Jupyter Notebook**

This Jupyter Notebook outlines a full data science project workflow focused on predicting house prices using machine learning, from data collection to deployment using Flask. The notebook is organized into several logical parts, making it a comprehensive example of an end-to-end data science pipeline.


### **1. Setup and Data Collection**

The project begins with the import of essential Python libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and various modules from `scikit-learn`. The dataset used in this project is the **California Housing dataset**, which is loaded using Scikit-learn's built-in function. The dataset includes features like median income, house age, number of rooms, and population, and the target variable is the house price.


### **2. Exploratory Data Analysis (EDA)**

In the EDA section, the notebook examines the dataset's shape, structure, and statistical summary. The dataset is confirmed to be clean, with no missing values. A histogram of house prices is plotted to understand the distribution of the target variable. Additionally, a **correlation heatmap** is created to visualize relationships between features and to identify highly correlated variables. These visualizations are also saved for future use in a web interface.

### **3. Data Preprocessing**

For model preparation, the data is split into features (`X`) and target (`y`), and then into training and testing sets (80-20 split). Since all the features are numerical, a preprocessing pipeline is built using Scikit-learn’s `Pipeline` and `ColumnTransformer`. The pipeline includes a `SimpleImputer` to handle any potential missing data using the **median strategy**, and a `StandardScaler` to normalize feature values.

### **4. Model Building and Evaluation**

Two different regression models are trained and evaluated:

* **Linear Regression**: A pipeline combines preprocessing with a `LinearRegression` model. After training, the model is evaluated using **Mean Squared Error (MSE)** and **R² score**, which provide insight into the model's accuracy and fit.

* **Random Forest Regressor**: A second pipeline is created with a `RandomForestRegressor` using 100 decision trees. This model typically performs better on complex, non-linear data. Again, MSE and R² are calculated to compare performance.

The results of both models are printed, helping identify the more effective model based on error metrics and predictive power.

### **5. Model Deployment**

To complete the project, the notebook includes preparation steps for deploying the trained model using a **Flask web application**. Necessary components like trained model saving (using `pickle`) and templates for rendering predictions on a web page are prepared, though actual Flask code appears to be partially shown or implied.

### **Conclusion**

This Jupyter Notebook successfully demonstrates a full machine learning workflow: from data exploration and cleaning, through feature scaling and model training, to evaluation and deployment. By using both linear and ensemble methods, and integrating deployment practices, it showcases a practical and industry-relevant application of data science. The use of pipelines ensures a modular and reproducible approach, ideal for real-world projects.


OUTPUT : TASK 3

![Image](https://github.com/user-attachments/assets/0045ac9f-e2fe-4edc-b753-23ad845be92d)
