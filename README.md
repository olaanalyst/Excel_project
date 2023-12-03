## Healthcare Excel Dashboard Analysis
## Introduction
In my project, i aim to optimize data quality by employing data cleaning techniques in Excel, ensuring accuracy and reliability. Additionally, i plan to enhance data insights through effective visualization, utilizing Excel robust charting and graphing features for clearer representaton and interpretation of patterns within the Healthcare dataset.

## Data sourcing 
This dataset was downloaded from kaggle website. it contains the details patients infomation, Doctor's name, blood type, Billing amount, Date of Admission and discharge e.t.c, Updated up till 2018 to 2023 and there are 10001 rows and 16 column present in the Healthcare Dashboard.

## Data Analysis Process
To carry out this project a series of steps must be carried out in order to interpret this information. Finding these procedures is crucial because each step is important in ensuring that the data is processed correctly in order to provide relevant and useful information. the steps in this projects are listed below:

--Excel concept applied
--Problem Statement 
--Data Cleaning Process
--Data Visualization
--Communications and insights

## Excel concept applied are:

--Tables
--Pivot tables 
--Power Query

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
In the visual presentation of total revenue spanning from 2018 to 2023, i've employed a pie chart to succinctly depict the proportional contribution of each year to the overall revenue. This visual representation offers a quick and intuitive understanding of the revenue distribution across specified timeline, facilitating insightful analysis of revenue trends over the past six years.

![Screenshot (26)](https://github.com/olaanalyst/Excel_project/assets/141564936/3181aa9e-a3af-4f54-b957-c65f99642059)

# Distribution of Admission type by Duration and Average Billing Amount
I've delved into the distribution of admission types, dissecting them by duration and presenting the associated average billing amounts. 
This dual-axis visualization provides a comprehensive understanding of how admission types vary in duration and  corresponding billing, offering valuable insights into the dynamics of healthcare service utilization within different time frames.

![Screenshot (30)](https://github.com/olaanalyst/Excel_project/assets/141564936/0a02cc11-9b3e-4886-b024-36a1ccebdf1b)

# Duration of Medical Condition
I've depicted the duration of medical conditions, each bar on the chart represents a specific medical condition with the length of the bars corresponding to the duration associated with each condition. This visualization provides a straight forward and insightful representation of the varrying duration across different medical conditions within the dataset.

![Screenshot (32)](https://github.com/olaanalyst/Excel_project/assets/141564936/79184fd1-08b0-435e-b034-7ac78ce131a3)

# Blood Type for both Gender
I employed a double line chart to illustrate the distribution of blood types across genders. This visualization effectively compares the prevalance of different blood types for both males and females patients over the dataset. The dual lines offer a clear and concise representation, allowing for easy insights into the distribution patterns across genders. 

![Screenshot (31)](https://github.com/olaanalyst/Excel_project/assets/141564936/20ff46c6-c35f-4bce-b681-130066618a72)

## Conclusion
--The visual exploration of the dataset has provided valuable insights into various aspects of the healthcare records.
--The timelines, double bar charts, and double line charts effectively portrayed the distribution of medical conditions, admission types, duration, and blood types across different dimensions.
--These visualizations not only enhance the understanding of the dataset but also offer a foundation for more in-depth analyses.
--The combination of data cleaning, column additions, and strategic visualizations has transformed the raw dataset into a rich source of information, empowering informed decision-making in the Healthcare context.

