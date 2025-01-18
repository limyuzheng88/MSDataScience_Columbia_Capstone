[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/m5cwIV43)
# Generative Tabular Learning (GTL) for Predicting Credit Approvals and Analyzing Customer Behavior in Financial Institutions 
### Columbia University Data Science Capstone & Ethics (ENGI E4800)

## Project Overview
Financial institutions, like our industry partner TD Bank, are increasingly harnessing data science to enhance customer service, manage risks, and optimize operational efficiency. A major challenge lies in understanding and predicting customer behaviors and characteristics. This project aims to leverage a tabular foundational model (TabFM) or a Large Tabular Model (LTM) for bank customers by using a publicly available Kaggle dataset, to predict if a customer will get approved for a credit product

Currently, this can be achieved by traditional models like logistic regression and decision trees which have been supplemented by advanced techniques such as gradient boosting and deep learning. However, they often require extensive retraining for new tasks. On the other hand, GTL leverages zero-shot and in-context learning, enabling it to adapt to new tasks with minimal retraining, thus improving model efficiency and effectiveness.
Unlike traditional approaches that require preprocessing steps such as feature engineering, imputation, and retraining, Generative Tabular Learning (GTL) models harness their pretrained architectures to achieve competitive results on tabular data tasks. We examine their performance against baseline TradML models—Logistic Regression, Decision Trees, Random Forests, and XGBoost—under similar constraints of limited data and features to ensure a fair evaluation.



## Team Structure

1. Varun Agarwal, va2515 (Team Lead)
2. Yu Zheng Lim, yl5451
3. Atharva Kulkarni, aak2226
4. Nicolas Cogorna, nac2216
5. Minh Dang, nd2802
6. Ryu Sonoda, rs4492


## Project Methodology

1. Data preparation: Gather, explore, and preprocess the dataset. Split it into training and test sets.
2. Model Development: Build baseline models. Apply traditional ML models such as logistic regression and XGBoost.
3. GTL Implementation:
    - Use zero-shot learning for initial predictions.
    - Apply in-context learning with example prompts for task adaptation. 
4. Evaluation: Compare GTL model's performance with baseline models using sensible metrics. 
5. Documentation and Knowledge Transfer

## Repository Structure

```plaintext
.
├── CourseInforForStudents/   # Contains course-related materials and resources
├── Reports/                  # Includes progress reports and the final course report
├── Weekly Check-Ins/         # Weekly updates or check-in notes
├── code/                     # Main codebase, including scripts and implementations
│   ├── EDA/                  # Exploratory Data Analysis scripts and preprocessing notebooks
│   ├── GTL Experiments/      # Code for GTL-related experiments
│   └── Result Analysis/      # Scripts for analyzing experimental results
├── dataset/                  # Datasets used for modeling and experiments
├── papers/                   # Reference papers
├── result/                   # Output and results of GTL experiments and ML baseline
└── README.md                 # Documentation for the repository
