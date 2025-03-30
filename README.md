# AJL_team13
# Dermatology AI Challenge - Kaggle Competition

## Team Members
- **Supriya** - [supriyasub](#)  

---

## Project Overview

### About the Competition
This project is part of the **Break Through Tech AI Program** in collaboration with the **Algorithmic Justice League (AJL)**. The Kaggle competition challenges participants to develop an inclusive machine learning model capable of classifying **21 different skin conditions** across a diverse range of skin tones.

### Objective
The primary goal of this challenge is to design an AI system that can accurately diagnose skin conditions while ensuring fairness and inclusivity across different demographic groups. The final model is evaluated using the **weighted average F1 score**, considering both precision and recall.

### Real-World Significance
Skin disease diagnosis is often subject to biases, particularly due to the underrepresentation of darker skin tones in dermatological datasets. An AI-powered solution that is both **accurate and equitable** can:
- Improve accessibility to dermatological care
- Reduce disparities in medical diagnosis for marginalized communities
- Support dermatologists with more robust AI-assisted tools

---

## Data Exploration

### Dataset Overview
The dataset consists of images and metadata related to **21 different dermatological conditions**. The images are stored with filenames matching the `md5hash` column, and the full image paths follow the structure:
```
/kaggle/input/bttai-ajl-2025/test/test/<md5hash>.jpg
```
**Sources:**
- **Kaggle-provided dataset** containing labeled training images and unlabeled test images
- **Potential additional sources** (TBD, if applicable)

### Data Preprocessing
To ensure data quality and improve model performance, we conducted the following preprocessing steps:
- **Image resizing & normalization** to standardize input dimensions
- **Data augmentation** (rotation, flipping, color adjustments) to enhance generalization
- **Handling class imbalance** using oversampling and weighted loss functions
- **Metadata analysis** to understand distribution biases in skin tones and conditions

### Exploratory Data Analysis (EDA)
Below are some key visualizations from our EDA:

#### 1. Class Distribution of Skin Conditions
(Insert a bar plot showing the frequency of each skin condition in the dataset)
![image](https://github.com/user-attachments/assets/59f7a83b-52ec-4371-a314-a249a694568d)
![image](https://github.com/user-attachments/assets/0fe66897-4eb9-44fe-8f4e-f8723dafcb99)


---

## Next Steps
- Implement initial baseline models (CNN, EfficientNet, etc.)
- Evaluate model fairness using performance metrics across different skin tones
- Conduct hyperparameter tuning and interpretability analysis
- Finalize the report and GitHub documentation


