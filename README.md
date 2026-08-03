# Fake-job-posting-detection-
Fake job posting detection using only traditional Machine Learning relies on extracted text and metadata features passed through tabular or statistical classifiers. Unlike deep learning, this approach uses structured feature engineering (like TF-IDF for text and flag counts for metadata) to train lightweight algorithms like Random Forest and etc.
# Fake Job Posting Detection using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AkhilGummadi7/Fake-job-posting-detection/blob/main/fake_job_detection.ipynb)

A machine learning solution designed to detect and classify fraudulent job postings using data preprocessing, feature engineering, and predictive modeling techniques.

---

## 📌 Overview
This project aims to analyze job listing metadata (such as salary range, company type, employment type, and job titles) to identify deceptive listings and safeguard job seekers.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Environment:** Google Colab / Jupyter Notebook
* **Data Manipulation & Viz:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## 📁 Dataset Details
The dataset consists of **2,000 entries** featuring both numerical and categorical attributes:
* `Job_Title`: Target position title.
* `Salary_INR`: Offered salary amount in INR.
* `Company_Type`: Recruiter profile (e.g., Startup, SME, Recruitment Agency).
* `Employment_Type`: Role type (e.g., Internship, Part-time, Contract).
* `Label`: Target classification (`Real` vs. `Fake`).

## 🚀 How to Run
1. Click the **Open in Colab** badge above to launch the notebook directly in Google Colab.
2. Upload the `Fake_Job_Posting_Detection_Dataset.csv` file to your Colab runtime environment.
3. Run all cells sequentially to execute data loading, exploratory data analysis (EDA), and model evaluation.
