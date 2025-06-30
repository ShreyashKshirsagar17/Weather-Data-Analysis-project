# Data_Analysis_on_Weather_Dataset
Data Analysis on Weather Dataset using Python
<!DOCTYPE html>
<html>

<body>
<h2>Introduction</h2>
<p>Data Analysis is one major part that you must master before learning or diving into the machine learning algorithms section because data analysis is a process to explore the data to get a better understanding of data.</p>
<h2>Dataset Overview</h2>
<p>The dataset we will use is a simple weather dataset which is a time-series dataset that stores the temperature, humidity, wind speed, etc on an hourly basis on different dates in 2012Load Dataset.</p>
<h2>Load Dataset</h2>
<p>You have the dataset and open the Jupyter Notebook or you can also create a Kaggle notebook over there itself. The first step is to import the necessary libraries and load the dataset into a notebook.</p>
<h2>Basic Python Pandas Data Analysis Functions</h2>
<h3>1. Shape</h3>

  ```bash
 data.shape
```
  <h3>2. Data types</h3>
  
  ```bash
 data.dtypes
```

<h3>3. Unique </h3>
  
   ```bash
 data['Weather'].unique()
```
  
<h3>4. Count</h3>
  
   ```bash
 data.count()
```
  
<h3>5. Value counts</h3>
  
   ```bash
 data['Weather'].value_counts()
```
  
<h3>6.information</h3>
  
   ```bash
 data.info
```
  
<h3>7.Describe</h3>
  
   ```bash
data.describe()
```
