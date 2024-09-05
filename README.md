# Soil Quality Assessment System

## Overview

The Soil Quality Assessment System is designed to evaluate soil quality based on various nutrient and chemical parameters. The system employs machine learning models to predict the percentage of vegetation cover, providing insights into soil fertility and helping users make informed decisions on soil management. This project includes a Jupyter notebook for model training and an Excel dataset with soil parameters.

## Project Structure

The project repository contains the following files:

- **`Soil Quality Assessment.ipynb`**: Jupyter notebook containing the code for data preprocessing, model training, evaluation, and prediction.
- **`soil_data.xlsx`**: Excel file with the dataset used for training the models.

## Features

- **Data Preprocessing**: Handles missing values and normalizes data.
- **Model Training**: Trains multiple regression models, including:
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression
- **Evaluation Metrics**: Computes various metrics, including:
  - Mean Square Error (MSE)
  - Root Mean Square Error (RMSE)
  - Mean Absolute Error (MAE)
  - R2 Score
- **Prediction**: Allows users to input soil parameters and predicts vegetation cover percentage.
- **Advice**: Provides recommendations based on the prediction results.

## Setup

### Requirements

Ensure you have the following Python packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `joblib`

Install these packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib
```


### Running the Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ManchalaSrinithin/soil-quality-assessment-system.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd soil-quality-assessment-system
   ```

3. **Open the Jupyter Notebook or Google Colab**

   Start Jupyter Notebook in your terminal:

   ```bash
   jupyter notebook
   ```

   Open the `Soil Quality Assessment.ipynb` notebook from the Jupyter interface.

4. **Run the Notebook**

   Execute the cells in the notebook to preprocess the data, train the models, and make predictions.

## Usage

- **Data Input**: Update the `soil_data.xlsx` file with your own soil data.
- **Prediction**: Follow the prompts in the Jupyter notebook to input soil parameters and get predictions.
- **Results**: View evaluation metrics and prediction results directly in the notebook.

## Troubleshooting

- **File Not Found**: Ensure the `soil_data.xlsx` file is located in the same directory as the notebook.
- **Package Issues**: Verify that all required packages are installed and up-to-date.

## Contribution

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.


## Contact

For any questions or issues, please contact [Srinithin Manchala](mailto:srinithin17.com).


### Key Points to Note:

1. **Overview**: Provides an introduction to the project.
2. **Project Structure**: Lists the files and their purpose.
3. **Features**: Describes the main functionalities of the system.
4. **Setup**: Instructions on installing dependencies.
5. **Running the Project**: Step-by-step guide to clone the repository and run the notebook.
6. **Usage**: How to use the notebook and interpret results.
7. **Troubleshooting**: Common issues and solutions.
8. **Contribution**: How others can contribute.
9. **Contact**: Contact information for support or inquiries.



