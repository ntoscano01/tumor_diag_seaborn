# Tumor Diagnosis With Seaborn

## Exploratory data analysis with seaborn

For this project I used Seaborn to discover and explore the relationships in the <a href="https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))">Breast Cancer Wisconsin (Diagnostic) data set</a>. Below are the tasks copmleted for this project: 

### **Task 1:** Introduction and Importing the Data

<img src="" width="400" height="300">

### **Task 2:** Separate Target from Features

Seperate target features into a new dataframe.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/target_variable.png" width="400" height="300">

### **Task 3:** Diagnosis Distribution Visualization

Let's use seaborn countplot() to look at the diagnosis distriubition between benign and malignant tumors.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/distributions.png" width="400" height="300">

We can use dataframe.describe() to get a summary of our data. dataframe.describe() provides descriptive statistics that summarize the central tendency, dispersion and shape of a dataset’s distribution, excluding NaN values.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/data_description.png" width="400" height="300">

### **Task 4:** Visualizing Standardized Data with Seaborn

Use violin plot to visualize standarized data.  We can look at the separation between the median values to determine whether this would be a good feature to use for classification.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/violin_plot.png" width="400" height="300">

### **Task 5 :** Violin Plots and Box Plots

A boxplot is useful for detecting outliers amont the features in the data set.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/box_plot.png" width="400" height="300">

### **Task 6:** Using Joint Plots for Feature Comparison 

This joint plot is an effective way of visualizing correlation between two feartures in a data set.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/joint_plot.png" width="400" height="300">

### **Task 7:** Observing the Distribution of Values and their Variance with Swarm Plots

Swarm plot does a really good job of showing which features may have better predictive power than others.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/swarm_plot.png" width="400" height="300">

### **Task 8:** Observing all Pairwise Correlations

A correlation plot shows relatiopnship between all features in the dataset within one table.  The color coded results enable anlaysts to quickly identify where strong correlation exists.

<img src="https://github.com/ntoscano01/tumor_diag_seaborn/blob/main/corr_plot.png" width="400" height="300">

_Note: I completed this project on Coursera_



<img src="https://github.com/ntoscano01/certificates/blob/main/exploratory%20data%20analysis%20with%20seaborn.png" width="400" height="300">

***Course Certificate***


