## Healthcare Excel Dashboard Analysis
## Introduction
In my project, i aim to optimize data quality by employing data cleaning techniques in Excel, ensuring accuracy and reliability. Additionally, i plan to enhance data insights through effective visualization, utilizing Excel robust charting and graphing features for clearer representaton and interpretation of patterns within the Healthcare dataset.

## Data sourcing 
This dataset was downloaded from kaggle website. it contains the details patients infomation, Doctor's name, blood type, Billing amount, Date of Admission and discharge e.t.c, Updated up till 2018 to 2023 and there are 10001 rows and 16 column present in the Healthcare Dashboard.

## Data Analysis Process
To carry out this project a series of steps must be carried out in order to interpret this information. Finding these procedures is crucial because each step is important in ensuring that the data is processed correctly in order to provide relevant and useful information. the steps in this projects are listed below:

- Excel concept applied
- Problem Statement 
- Data Cleaning Process
- Data Visualization
- Communications and insights

## Excel concept applied are:

- Tables
- Pivot tables 
- Power Query

## problem statement
In my project, i encountered chaallenges with inconsistent data formatting in the "Billing Amount" column, which prompted me to standardize the representation by adding dollar signs.
Additionally, i introduced a "Duration" column to capture time-related aspects. However the dataset suffered from duplications in the new values, necessitating a thorough data cleaning process to refine and streamline the information.
Addressing these issues is pivotal to ensure data uniformity and eliminate redundancy, paving the way for accurate analysis and meaningful visualization.

## Data cleaning process
Data Cleaning also known as data cleansing or scrubbing, is the process of identifying and correcting errors, inconsistencies, and inaccuracies within a dataset. This dataset which contains 10001 observations(rows) with 16 variables(columnns), some column like "Biliing amount" i added dollar signs. I identified and removed duplicate values within the dataset. 
I introduce a new column named "Duration". This involved a calculated transformation where i substracted the "Date od Admission" from the "Discharge Date" providing a clear and standardized measured of the Duration for each entry.

![Screenshot (28)](https://github.com/olaanalyst/Excel_project/assets/141564936/6ebf0f1e-50f3-4705-af32-1330f3aa5fb5)
![Screenshot (29)](https://github.com/olaanalyst/Excel_project/assets/141564936/118dca6c-a498-429f-ac4d-c88abda9786d)

## Data Visualization
Data Visualization involves representing data visually through charts, graphs, maps, or other graphical elements to facilitate understanding and interpretation.
For visualization, i exported the csv file to Excel Power Query and i created a pivot table to better display my findings and communicate the analysis.

![Screenshot (25)](https://github.com/olaanalyst/Excel_project/assets/141564936/20fa75e8-a5de-41d6-8723-6d3ef1a09d30)

## Insights
# Timeline and slicer
I incorporated a dynamic timeline showcasing the date of admission and discharge date, offering a chronological perpective on patient records.
To enhance user interaction, i've implemented a slicer feature enabling the segmentation of data based on age range and gender. This intuitive interface allows for precise exploration of the dataset. 

![Screenshot (27)](https://github.com/olaanalyst/Excel_project/assets/141564936/d5cb0e2b-384a-45b9-9158-b01e8c76bd5d)

# Total Revenue from year 2018 to 2023
The Healthcare services managed to generate a Total Revenue of $255,168,068 for SIX (6) years. Starting at $5,422,484 in 2018, there was a substantial increase in 2019, reaching $49,756,616. However, subsequent years witnessed a fluctuation, with revenues of $52,750,866 in 2020, $52,612,046 in 2021, and $52,106,931 in 2022. Notably, there was a significant decrease in 2023 with $42,519,126. these trends indicate potential shifts in the healthcare industry during the period.

![Screenshot (26)](https://github.com/olaanalyst/Excel_project/assets/141564936/3181aa9e-a3af-4f54-b957-c65f99642059)

# Distribution of Admission type by Duration and Average Billing Amount
Examining the distribution of admission types reveals distinct patterns in both duration and average billing amounts. Elective admissions exhibit a cumulative duration of 50,579 with an average billing amount of $25,892. Meanwhile, Emergency admissions, totaling a duration of 52,558 show a slightly lower average billing amount at $24,709. Urgent admissions with a summed duration of 52,481 have an average billing amount of $25,961. These insights underscore the interplay between admission types, duration, and billing amounts, providing valuable information for strategic considerations in healthcare management.  

![Screenshot (30)](https://github.com/olaanalyst/Excel_project/assets/141564936/0a02cc11-9b3e-4886-b024-36a1ccebdf1b)

# Duration of Medical Condition
Analyzing the summed duration of medical conditions reveals interesting insights. Asthma leads with a total duration of 26,442, closely followed by Arthritis at 26,384 and Cancer at 26,362. Hypertension and Diabates exhibits durations of 26,046 and 25,277. Obesity with a total duration of 25,107 rounds out the list. These figures shed light on the varying impact and resource utilization associated with different medical condition, offering valuable information for healthcare resource allocation.

![Screenshot (32)](https://github.com/olaanalyst/Excel_project/assets/141564936/79184fd1-08b0-435e-b034-7ac78ce131a3)

# Blood Type for both Gender
Examining blood types distribution across genders reveals interesting patterns. For A-, females lead with 633, surpassing males at 605. A similar trend is observed in A+ where females with 629 exceed males with 612. AB- shows a notable difference with 671 in females compared to 604 in males, while AB+ displays a narrower gap with 637 in females and 621 in males. B- exhibits 635 in females and 617 in males. and B+ shows 640 in females against 604 in males. O- indicates a higher count in females 655 than male 589, while O+ has 641 in females and 607 in males. These insights into blood type distribution among genders can inform healthcare considerations and may be relevant for medical research and planning.

![Screenshot (31)](https://github.com/olaanalyst/Excel_project/assets/141564936/20ff46c6-c35f-4bce-b681-130066618a72)

## Conclusion
- The visual exploration of the dataset has provided valuable insights into various aspects of the healthcare records.
- The timelines, double bar charts, and double line charts effectively portrayed the distribution of medical conditions, admission types, duration, and blood types across different dimensions.
- These visualizations not only enhance the understanding of the dataset but also offer a foundation for more in-depth analyses.
- The combination of data cleaning, column additions, and strategic visualizations has transformed the raw dataset into a rich source of information, empowering informed decision-making in the Healthcare context.

