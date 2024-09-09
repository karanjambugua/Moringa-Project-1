Aircraft Accident Analysis: Identifying Low-Risk Aircraft
Overview
This project analyzes aviation accident data from 1962 to 2023 to help a company expanding into the aviation industry make informed decisions regarding aircraft purchases. The goal of the project is to identify aircraft models with lower accident risks to minimize operational risks.

Business Understanding
Stakeholder: The company’s aviation division head, who needs to decide which aircraft to purchase based on accident risk.

Key Business Questions:

Which aircraft models are involved in the highest and lowest number of accidents?
Are specific phases of flight more prone to accidents, and which aircraft models are involved?
How do geographical regions and weather conditions influence accident rates?
Data Understanding and Analysis
Source of Data:
The dataset used in this analysis comes from the National Transportation Safety Board (NTSB), which includes aviation accidents and selected incidents in the United States and international waters from 1962 to 2023.

Description of Data:

Number of Records: Over 80,000 rows of accident data
Key Columns:
Event.Id, Make, Model, Total.Fatal.Injuries, Total.Serious.Injuries, Weather.Condition, Broad.phase.of.flight
Visualizations
Accidents by Aircraft Make and Model:
Bar chart comparing the top 20 and bottom 20 aircraft models by accident count.
Accidents by Flight Phase:
A comparative visualization of accidents during flight phases such as takeoff, landing, and approach, highlighting models with the most and least accidents.
Geographical Impact on Accidents:
A heatmap or geographical map showing accident distribution across various countries and regions, emphasizing areas with higher accident rates.
Conclusion
Key Findings:
Aircraft Make and Model: Certain aircraft models like Cessna had a higher number of accidents, while models like Piper PA-28 had significantly lower risks.
Flight Phases: The approach and landing phases were found to have the highest accident rates, with some aircraft models being particularly accident-prone during these phases.
Geographical and Weather Impact: The United States had the highest concentration of accidents, especially in states like California and Florida. Clear weather was involved in many accidents, but adverse weather increased the severity.
Commit History
The project was consistently updated over the course of the analysis, with clear commit messages to ensure transparency.

Key Commits:
Initial Data Cleaning and Exploration: Focused on missing values and initial data structure.
Analysis and Visualizations: Generated key insights, graphs, and models for the presentation.
Final Edits and README: Documented the project and polished the final version.
Organization
/notebooks: Contains all Jupyter notebooks used for data exploration and analysis.
/presentation: PowerPoint slides summarizing the findings and recommendations.
AviationData.csv: Original dataset used for analysis.
cleaned_aviation_data.csv: Cleaned version of the dataset after handling missing values.
.gitignore
We used .gitignore to exclude files that are unnecessary or too large, including:

*.ipynb_checkpoints
*.csv (after the cleaned data is pushed)
*.DS_Store
.idea/
Large files like the notebook exceeding 50MB were managed with Git Large File Storage (LFS).# Moringa-Project-1
