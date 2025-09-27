# TikTok Claim Classification Analysis

## About
Analysis of a TikTok dataset to classify videos as **claims** (unverified info) or **opinions**.  
Focus on cleaning, exploring, and preparing data for predictive modeling to improve content moderation.

## Goals
- Clean and inspect raw data  
- Explore engagement trends by claim status  
- Identify correlations with user attributes (verification, ban status)  
- Prepare features for machine learning classification

## Dataset
- **File**: `tiktok_dataset.csv`  
- **Size**: 19,383 rows × 12 columns  
- **Key Columns**:  
  - `claim_status` – claim vs. opinion  
  - `verified_status` – user verification flag  
  - `author_ban_status` – account state  
  - `video_view_count`, `video_like_count`, `video_share_count`, `video_comment_count` – engagement metrics

## Installation  
To get started, clone this repository to your local machine: 
```bash
git clone https://github.com/yourusername/TikTok-Claim-Classification-Analysis.git
```

Ensure you have the necessary dependencies installed:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Results
- Claim videos show distinct engagement patterns compared to opinions
- User verification and ban status influence classification outcomes
- Likes and shares are strong indicators for distinguishing claims
