# 🌡️ Heat's Toll on Health

⁠An exploratory data analysis investigating the relationship between extreme heat events and health outcomes across the United States from 2000 to 2022.

*📊 [View Live Project](https://ishmeen-11.github.io/EDAV-Project/)*

---

## 🎯 Project Overview

Climate change is making extreme heat events more frequent and more severe. This project examines the human cost of rising temperatures by analyzing how heat waves affect hospitalizations, emergency department visits, and mortality rates across different U.S. regions and demographic groups.

### Research Questions

1.⁠ ⁠*Temporal Trends*: How have extreme heat events evolved across U.S. regions from 2000 to 2023?

2.⁠ ⁠*Health Impact*: Is there a measurable relationship between heat events and adverse health outcomes?

3.⁠ ⁠*Vulnerable Populations*: Which age groups and demographic groups face the highest risk from extreme heat?

---
## 📊 Datasets

All data is sourced from the *[CDC Environmental Public Health Tracking Network](https://ephtracking.cdc.gov/DataExplorer/)*. We utilize four interconnected datasets covering heat and health-related illness metrics.

### Table 1: Extreme Heat Events
*Focus*: Historical temperature extremes at county level

*Configuration*:

•⁠  ⁠*Measure*: Annual Number of Extreme Heat Events (Full Year)

•⁠  ⁠*Geography*: National by County

•⁠  ⁠*Time Period*: 2000-2023

•⁠  ⁠*Heat Metric*: Daily Maximum Temperature

•⁠  ⁠*Parameters*:
  - Minimum Duration: 2 Days
  - Absolute Threshold: 100°F

<details>
<summary><b>Download Instructions</b></summary>

1.⁠ ⁠Navigate to [CDC EPH Tracking Data Explorer](https://ephtracking.cdc.gov/DataExplorer/)

2.⁠ ⁠Select *"Heat and Health Related Illness"*

3.⁠ ⁠Select *"Historical Temperature and Heat Index"*

4.⁠ ⁠Choose *"Annual Number of Extreme Heat Events (Full Year)"*

5.⁠ ⁠Set Geography to *"National by County"*

6.⁠ ⁠Select years *2000-2023*

7.⁠ ⁠In Advanced Options:
   - Heat Metric: Daily Maximum Temperature
   - Minimum Duration Days: 2 Days
   - Absolute Threshold: 100 degrees F
</details>

---

### Table 2: Hospitalizations for Heat-Related Illness
*Focus*: Hospital admissions due to heat stress

*Configuration*:

•⁠  ⁠*Measure*: Annual Number of Hospitalizations for HRI 

•⁠  ⁠*Geography*: National by State

•⁠  ⁠*Time Period*: 2000-2023

•⁠  ⁠*Advanced Options*: All selected

<details>
<summary><b>Download Instructions</b></summary>

1.⁠ ⁠Navigate to [CDC EPH Tracking Data Explorer](https://ephtracking.cdc.gov/DataExplorer/)

2.⁠ ⁠Select *"Heat and Health Related Illness"
*
3.⁠ ⁠Select *"Hospitalizations for HRI"*

4.⁠ ⁠Choose *"Annual Number of Hospitalizations for HRI"*

5.⁠ ⁠Set Geography to *"National by State"*

6.⁠ ⁠Select years *2000-2023*

7.⁠ ⁠In Advanced Options: Select all available filters

</details>

---

### Table 3: Emergency Department Visits
*Focus*: ER visits for heat-related conditions

*Configuration*:

•⁠  ⁠*Measure*: Annual Number of Emergency Department Visits for HRI

•⁠  ⁠*Geography*: National by State

•⁠  ⁠*Time Period*: 2000-2023

•⁠  ⁠*Advanced Options*: All selected

<details>
<summary><b>Download Instructions</b></summary>

1.⁠ ⁠Navigate to [CDC EPH Tracking Data Explorer](https://ephtracking.cdc.gov/DataExplorer/)

2.⁠ ⁠Select *"Heat and Health Related Illness"*

3.⁠ ⁠Select *"Emergency Department Visits for HRI"*

4.⁠ ⁠Choose *"Annual Number of Emergency Department Visits for HRI"
*
5.⁠ ⁠Set Geography to *"National by State"*

6.⁠ ⁠Select years *2000-2023*

7.⁠ ⁠In Advanced Options: Select all available filters

</details>

---

### Table 4: Heat-Related Mortality
*Focus*: Deaths attributed to extreme heat

*Configuration*:

•⁠  ⁠*Measure*: Annual Number of Heat-Related Deaths

•⁠  ⁠*Geography*: National by State

•⁠  ⁠*Time Period*: 2000-2023

•⁠  ⁠*Advanced Options*: None

<details>
<summary><b>Download Instructions</b></summary>

1.⁠ ⁠Navigate to [CDC EPH Tracking Data Explorer](https://ephtracking.cdc.gov/DataExplorer/)

2.⁠ ⁠Select *"Heat and Health Related Illness"*

3.⁠ ⁠Select *"Mortality from HRI"*

4.⁠ ⁠Choose *"Annual Number of Heat-Related Deaths"*

5.⁠ ⁠Set Geography to *"National by State"*

6.⁠ ⁠Select years *2000-2023*

7.⁠ ⁠Advanced Options: None
</details>

---

## 🛠️ Technologies Used

•⁠  ⁠*R* - Statistical analysis and data manipulatio
n
•⁠  ⁠*Quarto* - Document generation and website publishing

•⁠  ⁠*ggplot2* - Data visualization

•⁠  ⁠*dplyr/tidyr* - Data wrangling

•⁠  ⁠*GitHub Pages* - Project hosting

---

## 👥 Contributors

  - **Ishmeen Garewal**
  - **Khushi Advani**

---

## 📝 Course Information

This project was completed as part of the *Exploratory Data Analysis and Visualization (EDAV)* course at Columbia University.

*Institution*: Columbia University  

*Program*: Master of Science in Data Science  

*Semester*: Fall 2025

---


##  ⭐ Acknowledgments

•⁠  ⁠*CDC Environmental Public Health Tracking Network* for providing comprehensive public health data

•⁠  ⁠*Prof. Joyce Robbins* for her amazing template and guidance throughout the course and this project.

•⁠  ⁠*Columbia University* for academic resources

---

<div align="center">

*⭐ If you find this project interesting, please consider giving it a star!*

Made with ❤️ for public health and data science

</div>
