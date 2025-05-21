# Analyzing No-Show Appointments: Uncovering Patient Demographics and Influential Factors





## Description:
This project investigates the factors contributing to patients missing their scheduled medical appointments using the "No-Show Appointments" dataset from Kaggle. The analysis aims to address two key questions: first, to determine the percentage of male and female patients who do not show up for their appointments and identify the primary age groups within these no-show populations. Second, the project explores various features within the dataset to understand which factors significantly influence a patient's likelihood of missing their medical appointment. By identifying these demographic trends and influential factors, this analysis seeks to provide insights that could potentially help healthcare providers develop strategies to reduce no-show rates and improve appointment adherence.


## Dataset:
The dataset used in this project is the "No-Show Appointments" dataset, obtained from Kaggle [(Healthcare No Shows Appointments Dataset - Kaggle)](https://www.kaggle.com/datasets/joniarroba/noshowappointments). This dataset comprises information on over 100,000 medical appointments in Brazil, focusing on the characteristics of patients and their attendance (or non-attendance) at scheduled appointments. Key features include patient demographics (age, gender), appointment details (scheduled day, appointment day, neighbourhood), and various factors potentially influencing attendance, such as scholarship status (Bolsa Família participation), health conditions (hypertension, diabetes, alcoholism, handicap), and SMS reminders. The dataset aims to help predict whether a patient will show up for a medical appointment or not.



## Analysis:
Question 1: What percentage of males and females don't show up to the appointments & which age group do they mostly fall into? 


Question 2: How do the following factors influence patients' medical appointment attendance?




Question 3: Does sending an SMS reminder reduce the likelihood of a no-show?
Surprisingly, the most frequent occurrence in the data is patients showing up for appointments without receiving an SMS reminder. While SMS reminders did correlate with some patients showing up, a significant number of those who received reminders still missed their appointments. This suggests that SMS reminders alone do not guarantee higher attendance in this dataset.



## How to Run:

Question 1:


Question 2:


Question 3: For the 3rd question, 5 steps were used to answer the question.

1- Loading the Dataset: First, the dataset was loaded into a pandas DataFrame, named app_df. 

2-Grouping and Counting Data: The SMS_received and No_show columns were then grouped, and the occurrences of each combination were counted. The result was stored in a DataFrame called sms_app.

3-Calculating Percentages: To understand the proportion of each group, the total number of appointments was calculated, and then the percentage of each combination within sms_app was determined.

4-Installing and Importing Matplotlib: To visualize the results, the matplotlib library was installed  using %pip install matplotlib

5-Generating Bar Chart: Finally, a bar chart was created to display the percentages, facilitating easier comparison of the different categories.



## Dependencies:
This project relies on the following Python library for data analysis:

pandas: A powerful and flexible library for data analysis in Python. It provides data structures like DataFrames, which are essential for working with structured data.

matplotlib: An important and useful library for creating different types of charts in Python.
