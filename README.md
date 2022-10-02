# Forecasting-With-Time-Series-Dataset

### Name: Akshit Bansal
### Roll: 101903693
### Subject: Building Innovative Systems UCS757

# Multi-input time series data : Predicting values of 5 parameters.

### Directories info:

- `allSectionsExcel`: excel files generated for all the sections individually included in this directory
- `output` : the predictions and expected output with RMSE between them included in this directory. <br>
Each section file in `output` directory have 3 rows:
`1st row` : actual value
`2nd row` : predicted value
`3rd row` : Root Mean Square Error
- `visulaization` : the plottings of predicted and expected value for all the sections included in this directory.


### Input File (data.xlsx)

- Original dataset contains 1009 rows and 15 columns
- First column denotes each road section
- Second column denotes the year no. for which parameter values are recorded
- Dataset is divided into 101 sections
- Columns 3 to 15 represents values for parameters 1 to 13

### Requirements

- Predict values for coulumn 9 to 13 for last (10th) year of each road section.
- Visualizing the predicted and actual values, plotting graphs.

### Methodology

- Gradient Boosting: decision trees for Regression
- Light Gradient Boosting Machine - Regression Model
- Boosting

### Evaluation Metric

- RMSE: Root Mean Square Error

### Final Result

Final RMSE = 34.091
