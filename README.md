# Injury-Risk-Prediction-in-Football
This project aims to predict the injury risk of professional football players using machine learning techniques. 
The dataset contains player attributes, match statistics, and injury history to train models like Random Forest, Logistic Regression, and SVM.
The dataset includes physical attributes, player performance, injury records (past and current seasons), and match statistics.
This dataset is from Kaggle(https://www.kaggle.com/datasets/kolambekalpesh/football-player-injury-data/data).

### 📘 Dataset Description

| **Column Name**                   | **Description**                                                                 |
|----------------------------------|---------------------------------------------------------------------------------|
| `p_id2`                           | Unique player identifier                                                       |
| `start_year`                      | Start year of current season                                                   |
| `height_cm`                       | Player's height in centimeters (averaged across FIFA 16–21)                    |
| `weight_kg`                       | Player's weight in kilograms (averaged across FIFA 16–21)                      |
| `work_rate_numeric`               | Player's work-rate mode across FIFA 16–21 (range: 2–4 in 0.5 intervals)        |
| `pace`                            | Player's 'pace' rating (averaged across FIFA 16–21)                            |
| `physic`                          | Player's 'physical' rating (averaged across FIFA 16–21)                        |
| `position_numeric`                | Encoded position: Goalkeeper=0, Defender=1, Forward=2, Midfielder=3            |
| `age`                             | Player age in the relevant season                                              |
| `cumulative_minutes_played`       | Total minutes played in all previous seasons                                   |
| `minutes_per_game_prev_seasons`  | Average minutes per game in previous seasons                                   |
| `avg_days_injured_prev_seasons`  | Average calendar days injured in previous seasons                             |
|`significant_injury_prev_season`  | whether player had significant injury in previous season                       |
|`cumulative_days_injured`          | cumulative calendar days player was injured prior to current season           |
|`target_major_injury`              | whether player had major injury in current season; True = yes; False = no     |

### 🔍 Project Highlights
Data Cleaning and Imputation

Exploratory Data Analysis (EDA)

Feature Engineering and Selection

Correlation and Feature Importance Visualization

Model Training and Evaluation

### 🧰 Requirements
Make sure to install the following Python libraries before running the notebook:

pandas 

numpy

sklearn.model_selection 

sklearn.preprocessing 

sklearn.ensemble 

sklearn.metrics 

seaborn  

matplotlib.pyplot 

sklearn.linear_model  

sklearn.svm  


### 📂 Files Included
Injury Risk Prediction in Football.ipynb – Full code notebook

report.html/pdf – Auto-generated project report

README.md – Project overview
