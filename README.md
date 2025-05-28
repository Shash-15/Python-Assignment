# Data Visualization in Python
TITLE: An Object-Oriented Approach to Data Matching and Visualization Using SQLAlchemy, Pandas, and Bokeh

## 🚀 Project Overview

The goal of this project is to:
- Load and store training, ideal, and test datasets using `SQLAlchemy`.
- Identify the best-fit ideal functions (from 50) for 4 training functions using **least squares deviation**.
- Match test data to the ideal functions based on a √2-deviation rule.
- Store the matched test results in the database.
- Visualize training data, ideal functions, and matched test data using **Bokeh**.

## 📁 Project Structure

Main
  ├── Src
      ├── Python_Project(bokeh).ipynb    # Jupyter Notebook with full implementation 
  ├── Datasets 
      ├── train.csv                      # Training dataset (Y1–Y4)
      ├── ideal.csv                      # Ideal functions (Y1–Y50)
      ├── test.csv                       # Test dataset (X, Y)
  ├── README.md                          # Project Documentation


## Technologies Used:
  -Python 3.12+
  -Pandas
  -NumPy
  -SQLAlchemy
  -SQLite
  -Bokeh
  -Jupyter Notebook

## How to Run:
1. Clone the repository:
   git clone https://github.com/your-username/function-matching.git
   cd function-matching

2.Install required packages:
   pip install -r requirements.txt

3.Run the Notebook:
   we can use Jupyter Notebook or Visual Studio code to run the cells in "Python_Project(bokeh).ipynb"
   
## Unit Testing
Basic unit tests can be added using the unittest module to check function outputs for:
  -Least squares deviation
  -Ideal function selection
  -Mapping logic
  
## Sample Output
  -Training and ideal functions plotted using Bokeh.
  -Test points shown with deviations to the ideal functions.
  -Hover tool and color-coded markers for better interpretation.
