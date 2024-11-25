# Income_Prediction  

Transform decision-making with our **Income Prediction App**, a powerful tool designed to predict an individual's income level based on key personal and professional details. Built using a **Decision Tree model with Gini Index**, the app provides accurate predictions to assist in various analytical and decision-making tasks.

## Detailed Description  

The **Income Prediction App** is a Flask-based application with an intuitive HTML form interface. Users input personal details like age, education, marital status, occupation, and more, and the app predicts whether their income is below or above a certain threshold.  

### Features  
- **User-Friendly Form**:  
  The form collects the following details:  
  - **Age**: Enter the individual's age.  
  - **Working Class**: Select from options like `Federal-gov`, `Private`, etc.  
  - **Education**: Specify the highest level of education (e.g., `10th`, `Bachelors`).  
  - **Marital Status**: Choose from statuses like `Married`, `Divorced`, etc.  
  - **Occupation**: Input the job title (e.g., `Adm-clerical`, `Exec-managerial`).  
  - **Relationship**: Specify the relationship (e.g., `Husband`, `Wife`).  
  - **Race**: Select the individual's race (e.g., `Amer Indian Eskimo`, `White`).  
  - **Gender**: Choose `Male` or `Female`.  
  - **Capital Gain**: Input a value between `0` and `99,999`.  
  - **Capital Loss**: Input a value between `0` and `4,356`.  
  - **Hours per Week**: Input hours worked per week (range `1-99`).  
  - **Native Country**: Specify the country of origin (e.g., `Cambodia`, `United States`).  

- **Submit Button**: Once all details are entered, click on `Submit` to receive the income prediction.  

### Model Details  
- **Algorithm**: Decision Tree with **Gini Index** to handle categorical and numerical data effectively.  
- **Training Dataset**: The model is trained on a comprehensive dataset available on Kaggle:  
  [**Income Prediction Dataset**](https://www.kaggle.com/datasets/sarimr/income-prediction-dataset).  

### How It Works  
1. Fill out the Income Prediction Form with the required details.  
2. Submit the form to send the data to the model for processing.  
3. The trained Decision Tree model predicts whether the individual's income is above or below the threshold.  

### Deployment  
The application is powered by **Flask** and uses HTML templates for an interactive and seamless user experience.  

### Model Training Code  
The model-building code, including the use of the Decision Tree algorithm with Gini Index, is included in the repository. Users can retrain the model on the dataset provided in the above link.  

### Usage  
Clone the repository, set up the Flask application, and access the form via your local server. Follow the documentation for detailed setup instructions.  

Make better decisions with the **Income Prediction App** today!  
