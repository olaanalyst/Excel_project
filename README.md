## Healthcare Excel Dashboard Analysis
## Introduction
In my project, i aim to optimize data quality by employing data cleaning techniques in Excel, ensuring accuracy and reliability. Additionally, i plan to enhance data insights through effective visualization, utilizing Excel robust charting and graphing features for clearer representaton and interpretation of patterns within the Healthcare dataset.

## Data sourcing 
This dataset was downloaded from kaggle website. it contains the details patients infomation, Doctor's name, blood type, Billing amount, Date of Admission and discharge e.t.c, Updated up till 2018 to 2023 and there are 10001 rows and 16 column present in the Healthcare Dashboard.

## problem statement
In my healthcare dashboard in Excel, I encountered the challenges of effectively visualizing the distribution of admission types concerning their duration and corresponding average billing amounts. Additionally, there was a need to aggregate the duration of medical conditions for a comprehensive understanding. Furthermore, i aimed to correlate blood type with gender for a more detailed analysis.

## Solution
To overcome these challenges, I implemented a comprehensive approach in the healthcare dashboard. Firstly, i enhanced the visualization of Admission types by introducing a new column, "Duration", calculated as the difference between date of admission and discharge date. This not only provided a clearer representation of the duration associated with each admission type but also facilitated a more granular analysis of patient stay.
Additionally, i incorporated a SUM function to aggregate the duration of medical conditions, contributing to a holistic understanding of the cumulative impact on patients healthcare experiences. Furthermore, I extended the analysis by correlating blood types with gender, creating a multifaceted view that adds depth to demographic insights within the healthcare dashboard.


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

## Data cleaning process
Data Cleaning also known as data cleansing or scrubbing, is the process of identifying and correcting errors, inconsistencies, and inaccuracies within a dataset. This dataset which contains 10001 observations(rows) with 16 variables(columnns), some column like "Biliing amount" i added dollar signs. I identified and removed duplicate values within the dataset. 
I introduce a new column named "Duration". This involved a calculated transformation where i substracted the "Date od Admission" from the "Discharge Date" providing a clear and standardized measured of the Duration for each entry.

![Screenshot (28)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/f03f86e0-70bc-4878-bd10-ca30f5753abb)
![Screenshot (29)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/1e75e590-30e8-4317-93ee-82386ab3b6da)

## Data Visualization
Data Visualization involves representing data visually through charts, graphs, maps, or other graphical elements to facilitate understanding and interpretation.
For visualization, i exported the csv file to Excel Power Query and i created a pivot table to better display my findings and communicate the analysis.

![Screenshot (38)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/573940c1-217f-469b-b47d-e94a2c68b30d)

## Insights
# Timeline and slicer
I incorporated a dynamic timeline showcasing the date of admission and discharge date, offering a chronological perpective on patient records.
To enhance user interaction, i've implemented a slicer feature enabling the segmentation of data based on age range and gender. This intuitive interface allows for precise exploration of the dataset. 

![Screenshot (40)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/cfd85f67-bea0-4c75-a6f8-2a4621fd8c70)


# Total Revenue from year 2018 to 2023
The Healthcare services managed to generate a Total Revenue of $255,168,068 for SIX (6) years. Starting at $5,422,484 in 2018, there was a substantial increase in 2019, reaching $49,756,616. However, subsequent years witnessed a fluctuation, with revenues of $52,750,866 in 2020, $52,612,046 in 2021, and $52,106,931 in 2022. Notably, there was a significant decrease in 2023 with $42,519,126. these trends indicate potential shifts in the healthcare industry during the period.

![Screenshot (26)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/8ec54771-8912-4b1c-bf57-bad29aa86bc7)

# Distribution of Admission type by Duration and Average Billing Amount
Examining the distribution of admission types reveals distinct patterns in both duration and average billing amounts. Elective admissions exhibit a cumulative duration of 50,579 with an average billing amount of $25,892. Meanwhile, Emergency admissions, totaling a duration of 52,558 show a slightly lower average billing amount at $24,709. Urgent admissions with a summed duration of 52,481 have an average billing amount of $25,961. These insights underscore the interplay between admission types, duration, and billing amounts, providing valuable information for strategic considerations in healthcare management.  

![Screenshot (30)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/9f2f8a8a-0c4c-4044-a22f-313734cdd56b)

# Duration of Medical Condition
Analyzing the summed duration of medical conditions reveals interesting insights. Asthma leads with a total duration of 26,442, closely followed by Arthritis at 26,384 and Cancer at 26,362. Hypertension and Diabates exhibits durations of 26,046 and 25,277. Obesity with a total duration of 25,107 rounds out the list. These figures shed light on the varying impact and resource utilization associated with different medical condition, offering valuable information for healthcare resource allocation.

![Screenshot (32)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/cf1a4214-e9aa-499d-953d-e37dc8011712)

# Blood Type for both Gender
Examining blood types distribution across genders reveals interesting patterns. For A-, females lead with 633, surpassing males at 605. A similar trend is observed in A+ where females with 629 exceed males with 612. AB- shows a notable difference with 671 in females compared to 604 in males, while AB+ displays a narrower gap with 637 in females and 621 in males. B- exhibits 635 in females and 617 in males. and B+ shows 640 in females against 604 in males. O- indicates a higher count in females 655 than male 589, while O+ has 641 in females and 607 in males. These insights into blood type distribution among genders can inform healthcare considerations and may be relevant for medical research and planning.

![Screenshot (31)](https://github.com/olaanalyst/Healthcare_Excel_Dashboard_Analysis/assets/141564936/adf3927b-cdc8-4493-91af-6b8081eb5b31)

## Conclusion
- The visual exploration of the dataset has provided valuable insights into various aspects of the healthcare records.
- The timelines, double bar charts, and double line charts effectively portrayed the distribution of medical conditions, admission types, duration, and blood types across different dimensions.
- These visualizations not only enhance the understanding of the dataset but also offer a foundation for more in-depth analyses.
- The combination of data cleaning, column additions, and strategic visualizations has transformed the raw dataset into a rich source of information, empowering informed decision-making in the Healthcare context.

