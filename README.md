# TikTok Claim Classification Analysis  

## Overview  
This project was completed as part of the Google Advanced Data Analytics course in the "Get Started with Python" chapter. It involves analyzing a dataset provided by TikTok, which contains information about videos classified as either **claims** (unverified information) or **opinions** (personal beliefs). The goal is to clean, explore, and analyze the dataset to extract meaningful insights that can support predictive modeling and improve content moderation strategies.  

## Project Objective  
The objective of this project is to:  

- Inspect and clean the provided dataset.  
- Identify key variables and assess data quality.  
- Explore trends and correlations between claim status and engagement metrics.  
- Prepare the data for future exploratory data analysis (EDA) and predictive modeling.  
- Extract insights that can help in classifying videos and improving content moderation on TikTok.  

## Dataset  
The dataset, `tiktok_dataset.csv`, contains **19,383 rows** and **12 columns**, representing TikTok videos where a claim or opinion has been made. It includes variables related to video engagement, user status, and claim classification. The key attributes in the dataset include:  

- `claim_status`: Whether the video is a "claim" or an "opinion."  
- `verified_status`: Indicates if the user is verified.  
- `author_ban_status`: The user’s account status (active, under scrutiny, or banned).  
- `video_view_count`, `video_like_count`, `video_share_count`, `video_comment_count`: Engagement metrics for each video.  

## Structure  
tiktok-claim-analysis
│-- data/ # Folder containing the raw dataset
│ ├── tiktok_dataset.csv
│-- notebooks/ # Jupyter notebooks for data inspection and analysis
│ ├── 01_data_inspection.ipynb
│ ├── 02_eda.ipynb
│ ├── 03_model_preparation.ipynb
│-- src/ # Python scripts for data processing and model development
│ ├── preprocessing.py
│ ├── model.py
│-- README.md
│-- requirements.txt

## Installation  
To get started, clone this repository to your local machine:  
git clone https://github.com/yourusername/tiktok-claim-analysis.git

Ensure you have the necessary dependencies installed:  
pip install pandas numpy matplotlib seaborn scikit-learn

## How to Use  

### 1. Load the dataset  
Use the following Python code to load the dataset:  
import pandas as pd
df = pd.read_csv('data/tiktok_dataset.csv')

### 2. Data Cleaning
Handle missing values.
Remove duplicates.
Convert data types if necessary.

### 3. Exploratory Data Analysis (EDA)
Analyze the distribution of claim vs. opinion videos.
Explore engagement trends based on claim status.
Investigate correlations between user attributes and engagement.

### 4. Model Building
Prepare the dataset for machine learning classification.
Train a model to predict whether a video is a claim or an opinion.

## Results
The dataset contains a mix of claims and opinions, with trends showing that claim videos often receive different engagement levels compared to opinion videos.
User verification and ban status appear to influence video classification and engagement.
Certain engagement metrics, such as likes and shares, may help distinguish claims from opinions.

## Next Steps
Perform deeper exploratory data analysis (EDA) to identify patterns in video engagement.
Develop a classification model using machine learning to automate claim detection.
Optimize the model to improve accuracy.
Deploy the model for real-time content classification.

## Contributing
Contributions are welcome! If you have suggestions for improvements, feel free to fork this repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

Let me know if you need any modifications! 🚀

