# Plotter_IDA

The Plotter - IDA is the application to derive the Fragility Curve, available as an executable (.exe) file, and is a powerful tool designed for researchers in the field of structural engineering, particularly those studying the effects of seismic activity on structures.

# User Technical Guide: Incremental Dynamic Analysis (IDA) & Fragility Curve Application

This guide provides detailed instructions on how to use the IDA & Fragility Curve Application. This application performs Incremental Dynamic Analysis (IDA) and generates fragility curves, valuable tools in probabilistic risk assessments.

## 1. Launching the Application

To launch the application, navigate to the directory where the Python script is located and run the script using Python. The first time it will take some time to open it, and if it does not work, please open it with administration rights.

## 2. Interface Overview

The application opens with a table for data entry and a series of buttons for various operations. The table includes the following eight columns: 

1. Intensity Measure
2. Demand Parameter
3. Standard Deviation

At the top of the interface, you'll find fields for entering the 'Demand Limit' and 'Additional Uncertainty'. 

Below these input fields, you'll find various operation buttons:

1. Add Row
2. Paste from Excel
3. Uncertainty
4. Analyze Data
5. Regression Data
6. Plot Linear Regression
7. Plot Fragility Graph
8. Clear Table
9. Visit Website
10. Contact via Email

## 3. Adding Data

Three main data sets of columns are required to perform the analysis: Intensity measure (Spectral Acceleration (g)), Demand parameters (Output of analysis, i.e., Maximum Drift ratio, Inter-story Drift ratio), and Standard deviation observed in the Demand parameters.

There are two ways to add data to the table:

1. **Manually**: Click the 'Add Row' button to add a new row to the table. Then, click on each cell in the row to enter data manually.

2. **From Excel**: If your data is in an Excel spreadsheet, copy the rows you wish to import, then click the 'Paste from Excel' button to populate the table. 

## 4. Setting Demand Limit and Additional Uncertainty

Enter the desired 'Demand Limit' and 'Additional Uncertainty' in the respective fields. These values are used in the calculation of uncertainties.

## 5. Analyzing Data

Once you've entered your data and set the parameters, click the 'Analyze Data' button. The application will analyze the data, calculate uncertainties, and display the results.

## 6. Regression Data

Click the 'Regression Data' button to calculate and add the derived optimum mean IM from the 'Analyze Data' button to the data into figures. This will provide additional insights and is a necessary step before plotting graphs.

## 7. Plotting Graphs

This application can generate two types of plots:

1. **Linear Regression Plot**: Click the 'Plot Linear Regression' button to generate a linear regression plot of the data.
2. **Fragility Curve**: Click the 'Plot Fragility Graph' button to generate a fragility curve.

## 8. Resetting the Application

If you want to start over with new data, click the 'Clear Table' button. This will clear all the data from the table.

## 9. Additional Features

Use the 'Visit Website' button to visit the developer's website for more information about the application. If you encounter any issues or questions, use the 'Contact via Email' button to contact the developer.

## Troubleshooting

If you encounter issues, ensure you have entered valid data and all required parameters before attempting to analyze the data or generate plots. If problems persist, contact the developer via the 'Contact via Email' button.
