# Pymaceuticals Inc. SCC Treatment Data Visualization using Matplotlib and Pandas

## Overview
This project involves the analysis of data from an animal study conducted by Pymaceuticals, Inc., focusing on potential treatments for squamous cell carcinoma (SCC). The study monitored 249 mice with SCC tumors over 45 days, testing various drug regimens, including Pymaceuticals' drug of interest, Capomulin. The goal is to compare the performance of Capomulin against other treatments.

### Steps Taken

**Prepared the Data:**
First of all I Imported all the dependencies and Merged mouse_metadata and study_results DataFrames. I then cleaned the data having duplicated mouse Id and created another clean dataframe "clean_mouse_data". 

**Generated Summary Statistics:**
I calculated mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

**Created Bar Charts and Pie Charts:**
- Bar charts displaying the total number of timepoints for each drug regimen.
- Pie charts showing the distribution of unique female versus male mice in the study.

**Calculated Quartiles, Find Outliers, and Create a Box Plot:**

- I analyzed final tumor volumes for four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Also, identified potential outliers and visualized the data using a box plot.

**Created a Line Plot and a Scatter Plot:**

- Line plot of tumor volume over time for a mouse treated with Capomulin.
- Scatter plot of mouse weight versus average observed tumor volume for the Capomulin regimen.

**Calculate Correlation and Regression:**

- I calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin regimen.

**Tools & Techniques**
- Python: For data manipulation and analysis.
- Pandas: For handling data frames and performing calculations.
- Matplotlib: For creating visualizations.

**Applications**
This project provides comprehensive insights into the efficacy of different drug regimens, identifies potential outliers and trends in tumor development, and supports data-driven decisions for future treatment strategies. The visualizations and statistical analysis help in understanding the performance of Capomulin compared to other treatments, aiding in strategic planning and further research.

### Conclusion:
Overall, the project demonstrates the power of data visualization and statistical analysis in evaluating drug efficacy, ultimately supporting informed decision-making for future research and development strategies in cancer treatment.

- Refered to matplotlib quick start documentation https://matplotlib.org/3.7.1/tutorials/introductory/quick_start.html for charts.
- Refered to https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html for regression analysis.

Thank you !