# 🚗 US Traffic Accidents Big Data Analysis (2016–2021)

This project applies **big data analysis and visualization** techniques using **Apache Spark** and **Python** to explore and understand traffic accident trends across the United States. The dataset contains over 7.5 million accident records from 2016 to 2021.

## 📊 Project Objectives

- Analyze accident severity trends across U.S. states.
- Perform scalable processing on a dataset too large for traditional tools.
- Apply Apache Spark for big data aggregation.
- Visualize results to identify high-risk states.
- Evaluate accident patterns for potential real-world improvements.

## 📁 Dataset

- **Source**: [Kaggle – US Accidents (2016–2021)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Size**: ~7.5 million rows, 49 features
- **File used**: `preprocessed_accidents.csv` (after cleaning and reduction)

## ⚙️ Technologies Used

- Python 3.11
- Apache Spark 3.5.5
- Pandas
- Matplotlib / Seaborn
- VS Code (Local execution on Windows 10)

## 🔥 Key Features

- Apache Spark used to process millions of rows efficiently.
- Aggregated **average severity by state**.
- Converted Spark DataFrames to Pandas for output due to native I/O limitations on Windows.
- Clean, visual bar chart showing severity patterns across states.
- CSV output and visualization generated locally.

## 📦 Repository Structure
!!!!!!!!!!! Extract zip fie to get folder stracture !!!!!!!!!!!!!

Assignment Paper : Academic research file
Dataset and Prepocessing : accident_data_set with preprocessed file, original file, preprocessing script (NOTE : download dataset from original source, i uas unable to upload due to size limitation of free verion of github)
ML model python : python script of machine learning model
pyspark : spark script and dataset
Refrence research paper : list of similar research paper
Screen shot of vizilization : all images takes as refrence
Train and test : split of datafile and python scrit to split data
Viz_Python_file : python code for visualization 


## 📷 Sample Visualization

![Viz_8](https://github.com/user-attachments/assets/244f5732-fd27-41d9-b37d-f2bb9a801e9f)
![Viz_9](https://github.com/user-attachments/assets/fec5fa05-69cd-4020-a97f-fe645f294461)
![Viz_5](https://github.com/user-attachments/assets/b4adc96f-7dc6-4ff9-8a1d-4af36a4b8936)


## 🧠 Author

**Yagya Raj Sharma**  
*Master’s Student - CSC-40048: Data Visualization*  
Supervisor: Divya Tara Shakya  
Keele University (The British College)
May 2025

## 📃 License
This project is part of an academic coursework. It is provided for learning and demonstration purposes only.




