# Viral Social Media Trends Analysis

## Overview
This project focuses on analyzing viral social media trends using **trend analysis** and **anomaly detection** techniques. By leveraging data from various platforms, we uncover engagement patterns, identify key factors driving virality, and detect anomalies in content performance.

## Dataset Description
The dataset contains social media post data with various engagement metrics. The key columns include:
- **Post_ID** – Unique identifier for each post  
- **Platform** – Social media platform where the post was published  
- **Hashtag** – Hashtags used in the post  
- **Content_Type** – Type of content (e.g., video, image, text)  
- **Region** – Geographic region of the post  
- **Views** – Number of views received  
- **Likes** – Number of likes  
- **Shares** – Number of shares  
- **Comments** – Number of comments  
- **Engagement_Level** – Categorized as Low, Medium, or High  
- **Anomaly Detection Columns** – IsoForest_Anomaly, LOF_Anomaly, Autoencoder_Anomaly, Anomaly_Agreement  

## Project Steps

### 1. Data Preprocessing
- Checked for missing values and handled inconsistencies.  
- Encoded categorical features for model compatibility.  
- Scaled numerical features for better model performance.  

### 2. Exploratory Data Analysis (EDA)
- Visualized engagement distribution across platforms and content types.  
- Identified trends in likes, shares, and comments.  
- Examined correlations between features.  

### 3. Trend Analysis
- Analyzed viral trends by studying engagement levels.  
- Identified the most effective content types and hashtags.  
- Explored region-based variations in social media engagement.  

### 4. Anomaly Detection
- Applied **Isolation Forest, Local Outlier Factor (LOF), and Autoencoders**.  
- Detected outliers in social media engagement data.  
- Compared anomalies identified by different models.  

## Use Cases
- Identifying social media trends and engagement patterns.  
- Detecting unusual spikes or drops in engagement.  
- Understanding factors influencing content virality.  
- Optimizing social media strategies based on data insights.  

## Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow, XGBoost, CatBoost)  
- **Machine Learning** (Supervised & Unsupervised Learning, Anomaly Detection)  
- **Data Visualization** (Matplotlib, Seaborn)  

## Conclusion
This project provides valuable insights into **what makes content viral** and helps detect anomalies in social media engagement. **Trend analysis and anomaly detection are effective approaches** for extracting meaningful information from the dataset.

