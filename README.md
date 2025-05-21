# Medical No-Show Appointments: Uncovering Patient Demographics and Influential Factors


## Description:
This project investigates the factors contributing to patients missing their scheduled medical appointments using the "No-Show Appointments" dataset from Kaggle. The analysis aims to address two key questions:
1. Analyze the percentage of male and female patients who do not show up for their appointments and identify the primary age groups within these no-show populations. 
2. Explore various features within the dataset to understand which factors increase a patient's likelihood of missing their medical appointment.
By identifying these demographic trends and influential factors, this analysis seeks to provide insights that could potentially help healthcare providers develop strategies to reduce no-show rates and improve appointment adherence.


## Dataset:
The dataset used in this project is the "No-Show Appointments" dataset, obtained from Kaggle [(Healthcare No Shows Appointments Dataset - Kaggle)](https://www.kaggle.com/datasets/joniarroba/noshowappointments). This dataset contains information of over 100,000 medical appointments in Brazil, focusing on the patient characteristics and their attendance (or non-attendance) at scheduled appointments. 
Key features include patient demographics (age, gender), appointment details (scheduled day, appointment day, neighbourhood), and various factors potentially influencing attendance, such as scholarship status (Bolsa Família participation), health conditions (hypertension, diabetes, alcoholism, handicap), and SMS reminders. The dataset aims to help predict whether a patient will show up for a medical appointment or not.


## Analysis Summary:
**Question 1: What percentage of males and females don't show up to the appointments & which age group do they mostly fall into?**

Key Finding:
1. The analysis shows that around 20% of all the appointments have been missed by patients.
2. Missed appointments across gender and age groups were analyzed and following key observations were made:
3. Women account for majority of missed appointments (around 19%) across all age groups, with most of them falling in the category of age 41-64 and 25-40 (25-64).
4. The higher no-show rates among women could 'possibly' be due to factors such as work, care-giving responsibilities or a sensitive health condition.
5. Men account for only 10% missed appointments which is considerably lower compared to women.

Recommendation:
1. Age & gender are important factors when it comes to appointment attendance. Healthcare providers could investigate the cause of women missing aged 25-65 since they have the higher no-show rates.
2. Flexible appointment schedules could be considered for working women.


**Question 2: How do the following factors influence patients' medical appointment attendance?**





**Question 3: Does sending an SMS reminder reduce the likelihood of a no-show?**

Key Finding:

Surprisingly, the most frequent occurrence in the data is patients showing up for appointments without receiving an SMS reminder. While SMS reminders did correlate with some patients showing up, a significant number of those who received reminders still missed their appointments. This suggests that SMS reminders alone do not guarantee higher attendance in this dataset.


## How to Run:

1. **Import Libraries:** Import Pandas & Matplotlib for data analysis and visualization.
2. **Loading the Dataset:** Load the dataset into a pandas DataFrame and name it as app_df.
3. **Code:** For understanding how the analysis was done, refer to the project notebook attached. All the codes and documentation can be found there. 


## Dependencies:
This project relies on the following Python library for data analysis:

pandas: A powerful and flexible library for data analysis in Python. It provides data structures like DataFrames, which are essential for working with structured data.

matplotlib: An important and useful library for creating different types of charts in Python.
