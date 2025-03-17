# Customer_Shopping_Churn_Analysis
Analyzing customer shopping churn using machine learning. This project explores customer behavior, builds a predictive model using Random Forest, and evaluates factors contributing to churn in retail/e-commerce datasets.

## Project Overview

This project focuses on analyzing customer shopping churn using a dataset containing customer shopping data. The goal is to understand the factors that contribute to customer churn and to build a predictive model using machine learning techniques.

### Dataset
The dataset used in this project is `customer_shopping_data.csv`, which contains the following columns:
- `invoice_no`: Unique identifier for each invoice.
- `customer_id`: Unique identifier for each customer.
- `gender`: Gender of the customer.
- `age`: Age of the customer.
- `category`: Category of the product purchased.
- `quantity`: Quantity of the product purchased.
- `price`: Price of the product.
- `payment_method`: Payment method used by the customer.
- `invoice_date`: Date of the invoice.
- `shopping_mall`: Shopping mall where the purchase was made.

### Objectives
1. **Data Exploration**: Understand the dataset by performing exploratory data analysis (EDA).
2. **Data Preprocessing**: Clean and preprocess the data for modeling.
3. **Model Building**: Build a predictive model using Random Forest Classifier.
4. **Evaluation**: Evaluate the model's performance using accuracy, classification report, and confusion matrix.
5. **Visualization**: Create visualizations to better understand the data and model performance.

### Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For machine learning (train_test_split, RandomForestClassifier, accuracy_score, classification_report, confusion_matrix).
- **Matplotlib**: For data visualization.
- **Seaborn**: For statistical data visualization.

### Steps
1. **Loading Data**: The dataset is loaded from Google Drive.
2. **Data Exploration**: 
   - Display the first few rows of the dataset.
   - Check the shape of the dataset.
   - Check for missing values.
   - Get an overview of the dataset using `info()` and `describe()`.
   - Explore categorical variables.
3. **Data Visualization**:
   - Distribution of product categories.
   - Distribution of payment methods.
   - Age distribution.
   - Relationship between quantity and price.
4. **Model Building**:
   - Split the data into training and testing sets.
   - Train a Random Forest Classifier.
   - Evaluate the model's performance.
5. **Results**:
   - The model's accuracy and classification report are displayed.
   - Confusion matrix is plotted to visualize the model's performance.

