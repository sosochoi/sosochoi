# The Learning Journey: From Assignment 1 to Assignment 5

This repository reflects my learning progress from **Assignment 1** to **Assignment 5**, showcasing the development of my skills in **data cleaning**, **merging datasets**, and applying what I have learned across multiple assignments.

You can view the full project write-up here:  
[View the Write-Up](https://sosochoi.github.io/sosochoi/writeup.html)

---

## Project Overview

In this project, I merged a **cleaned dataset** with a **fake dataset** and documented the merging process, including the handling of any **NA values** created.

After merging **Assignment 5** into the **main branch** (which initially contained **Assignment 1**), the **main branch** now includes all relevant files for the entire project.

---

## Project Structure

The project contains the following files and folders:

1. **BABI4005Assign1.md**  
   The first assignment of the project, containing the initial exploration and setup for the project.

2. **Data Folder:**
   - `2024_salarybyagegroup_data.csv`: A fake dataset generated to merge with the cleaned survey dataset.
   - `clean_survey_2025-02-06_assign4_sosochoi.csv`: The cleaned dataset from **Assignment 4**, which will be merged with the fake dataset.

3. **Clean_Data Folder:**
   - This folder stores the cleaned dataset `clean_survey_2025-02-06_assign4_sosochoi.csv`, which is merged with the raw data `2024_salarybyagegroup_data.csv`.

4. **Scripts Folder:**
   - `gen_fake_data.ipynb`: A script that generates a CSV file containing average salary data based on age groups for the year 2024.
   - `Assign5_Merge_dataset.ipynb`: This script performs the merging of the cleaned dataset `clean_survey_2025-02-06_assign4_sosochoi.csv` with the fake dataset `2024_salarybyagegroup_data.csv`. It also explains the merge type used and documents any NA values created during the process.

5. **Documents Folder:**
   - Contains a Word document with a screenshot of the local version of the project.

6. **Results Folder:**
   - Contains the output file `merged_student_data.csv`, which is generated after executing the **Assign5_Merge_dataset.ipynb** script.

---

## Important Instructions for Forking

After forking this project, please note the following:

- **Data Folder**: This folder should be created to store the raw dataset `2024_salarybyagegroup_data.csv`. Users will need to manually add this file after forking the project.
- **Clean_Data Folder**: This folder should be created to store the cleaned dataset `clean_survey_2025-02-06_assign4_sosochoi.csv`. Users will need to manually add this file after forking the project.
- **Results Folder**: This folder should be created for the output of the merged file, named `merged_student_data.csv`.

---

## Conclusion

Throughout these assignments, I have built upon my knowledge and skills:

- **Assignment 1** introduced me to **GitHub** and **Jupyter notebooks**, which are essential tools for managing projects and coding.
- **Assignment 4** taught me how to clean and preprocess data using **Python** and **Jupyter notebooks**.
- **Assignment 5** gave me the opportunity to apply data cleaning techniques to merge datasets and handle real-world issues like missing data.