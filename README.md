The Learning Journey: From Assignment 1 to Assignment 5

This repository reflects my learning progress, including Assignment 1 and the final project (Assignment 5). The goal is to showcase the development of skills in data cleaning, merging datasets, and applying what I have learned across multiple assignments. 

In this project, I have merged a cleaned dataset with a new fake dataset and documented the merge process, including any NA values created.

Initially:
-Main branch (Assignment 1) contains: BABI4005Assign1.md
-A New Branch (Assignment 5) contains: Documents Folder with screen_grab.docx, Scripts Folder with Assign5_Merge_dataset.ipynb and gen_fake_data.ipynb.


After Merged, main branch contains all the files:
1. Data Folder: 
-2024_salarybyagegroup_data.csv: A fake dataset created to merge with the cleaned survey dataset.
-clean_survey_2025-02-06_assign4_sosochoi.csv: The cleaned dataset from Assignment 4, which will be merged with the fake dataset.


2. Clean_Data Folder: This folder will store the cleaned dataset, clean_survey_2025-02-06_assign4_sosochoi, which will be merged with the 2024_salarybyagegroup_data.csv dataset.

3. Scripts Folder: This folder contains two Python scripts:
-gen_fake_data.ipynb: This script generates a CSV file containing average salary data based on age groups for the year 2024.
-Assign5_Merge_dataset.ipynb: This script performs the merging of the clean_survey_2025-02-06_assign4_sosochoi dataset with the fake dataset 2024_salarybyagegroup_data.csv. It will also explain the type of merge chosen and the types of NA values created.

4. Documents Folder: This folder contains a Word document with a screenshot of the local version of the project.

5. Results Folder: This folder includes the output file "merged_student_data.csv," which is generated after executing the "Assign5_Merge_dataset.ipynb" script.


## Important Instructions for Forking

After forking this project, please note the following:

- **Data Folder**: This folder should be created to store the raw dataset `2024_salarybyagegroup_data.csv`. Users will need to manually add this file after forking the project.

- **Clean_Data Folder**: This folder should be created to store the cleaned dataset `clean_survey_2025-02-06_assign4_sosochoi.csv`. Users will need to manually add this file after forking the project.

- **Results Folder**: This folder should be created for the output of the merged file "named merged_student_data.csv".



