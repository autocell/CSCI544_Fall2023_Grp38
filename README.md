
# Code Execution Guide

This guide explains how to run the code for our project, which consists of two main parts: Dataset Generation and Model & XAI Implementation. This project is developed by a group of USC students pursuing a Master of Science in Computer Science.

## Contributors
- Chaitanya Ramayanam
- Vomini Desai
- Vidit Dave
- Sachin Koti
- Smit Shah

## Part 1: Dataset Generation

### Overview
This part of the code generates a dataset by combining different attributes from multiple files. We aim to create a balanced dataset of 20,000 rows, with 4,000 rows for each star rating from 1 to 5.

### Steps to Run
1. Download the dataset from the following link: https://www.yelp.com/dataset/download.
2. Replace the paths in the code file with the paths of your downloaded files.
3. Run the provided Colab file.
4. The output will be a file named `balanced_dataset.csv`.

### Note
The dataset generation code is time-consuming to execute. Therefore, for convenience, we have provided the generated dataset as `dataset.csv` which can be directly used for Model & XAI Implementation.

## Part 2: Model & XAI Implementation

### Overview
This part involves implementing various Explainable AI (XAI) techniques such as Anchors, SHAP, LIME, and Feature Importance, among others. The input for this section is the CSV file generated from Part 1. Additionally, we perform the calculation of PMI and other statistical measures for the reviews in the dataset.

### Steps to Run
1. Use the `balanced_dataset.csv` from Part 1 or the provided `dataset.csv`.
2. Run the Colab file for this part to obtain the outputs.

---

For any queries or issues, feel free to reach out to any of the contributors.

