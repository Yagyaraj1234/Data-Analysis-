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

> ⚠️ **IMPORTANT:** Extract the ZIP file to view the full folder structure!

- **Assignment Paper**: Academic research document  
- **Dataset and Preprocessing**:  
  - `accident_data_set` folder containing:
    - Original dataset (⚠️ Not included — please download from the original source)
    - Preprocessed dataset
    - Preprocessing script  
  *(NOTE: Dataset not uploaded due to GitHub free version file size limitations)*  
- **ML Model Python**: Python script for machine learning model
- **Pyspark**: Spark script and associated dataset
- **Reference Research Papers**: Collection of similar research papers used for reference
- **Screenshot of Visualization**: All reference visualization images
- **Train and Test**:  
  - Data split into training and testing sets  
  - Python script used for data splitting  
  *(NOTE: `train.csv` and `test.csv` files are not included due to GitHub file size limitations)*  
- **Viz_Python_File**: Python code used for visualization


## 📁 Full File Access (Includes Research Paper and All Data)

🔗 [Download Complete Folder from Google Drive](https://drive.google.com/file/d/1c4YOvWxgdvLWu-4XTb2eUmYa5EBK4TEp/view?usp=sharing)


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




