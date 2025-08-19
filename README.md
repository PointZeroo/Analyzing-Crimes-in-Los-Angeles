# Analyzing-Crimes-in-Los-Angeles
---
## Table of Contents
- [Introduction](#introduction)  
- [Dataset Description](#dataset-description)  
- [Objectives](#objectives)   
- [Visualizations and Insights](#visualizations-and-insights)  
- [Results and Findings](#results-and-findings)  
- [Future Work](#future-work)  
- [Technologies Used](#technologies-used)  
- [Setup Instructions](#setup-instructions)  
- [Contact Information](#contact-information) 
---

## Introduction
Los Angeles is famous worldwide for its entertainment industry, but like any major city, it faces challenges with crime. The LAPD has provided crime data to analyze patterns in criminal behavior.

The goal of this project is to uncover insights on when, where, and who crimes affect the most, and provide actionable findings that can help allocate police resources effectively.

---

## Dataset Description
The dataset (`crimes.csv`) is a modified version of the official **Los Angeles Open Data** crime records.  

| Column        | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| DR_NO         | Division of Records Number (unique crime ID)                                |
| Date Rptd     | Date reported (MM/DD/YYYY)                                                  |
| DATE OCC      | Date of occurrence (MM/DD/YYYY)                                             |
| TIME OCC      | Time of occurrence (24-hour format, HHMM)                                   |
| AREA NAME     | LAPD geographic area / patrol division                                      |
| Crm Cd Desc   | Description of the crime committed                                          |
| Vict Age      | Victim's age (years)                                                        |
| Vict Sex      | Victim’s sex (F = Female, M = Male, X = Unknown)                            |
| Vict Descent  | Victim’s descent/ethnicity code                                             |
| Weapon Desc   | Description of the weapon used (if any)                                     |
| Status Desc   | Crime status                                                                |
| LOCATION      | Street address where the crime occurred
---

## Objective
1. **Crime Frequency by Hour** – Identify peak crime hours.  
2. **Night Crime Hotspots** – Find which LAPD area reports the most crimes at night (10 PM – 3 AM).  
3. **Crimes by Victim Age Group** – Categorize crimes by victim age brackets (0–17, 18–25, 26–40, 41–65, 65+).  

---

## Queries Overview
1. **Top 5 Assignments by Total Donations (by Donor Type)**  
   - Aggregates and ranks assignments by donation amount per donor type.  

2. **Highest Impact Assignment per Region**  
   - Finds the top project in each region by impact score, restricted to projects that received donations.  

---

## Visualizations and Insights  

1. **Crimes by Hour of Occurrence**  
   - Peak crimes occur around **evening and late-night hours**.  
   - Suggests higher police presence needed between **6 PM – 2 AM**.  

   *(Example chart to include here from Jupyter Notebook output)*  

2. **Top LAPD Area for Night Crimes**  
   - The **[insert AREA NAME once identified]** had the most reported crimes between **10 PM – 3 AM**.  
   - Indicates resource prioritization during late hours.  

   *(Bar chart grouped by area)*  

3. **Crimes by Victim Age Group**  
   - Highest crime incidents against victims aged **18–25**.  
   - Lower but notable crime counts among minors (**0–17**) and elderly (**65+**).  

   *(Bar chart showing crime counts by age bracket)*

## Results and Findings  
- The **most common crime hour** was `peak_crime_hour`.  
- The **highest-risk area for night crime** was `peak_night_crime_location`.  
- The **18–25 age group** experienced the largest share of crimes.  
- These insights can inform **patrol planning**, **crime prevention strategies**, and **community programs**.  

---

## Future Work
- Expand analysis to include **weapon usage patterns**.  
- Explore **seasonal or monthly crime trends**.  
- Build interactive dashboards.  
- Incorporate **predictive modeling**. 

---

## Technologies Used
- **Programming Language**: Python  
- **Data Analysis**: Pandas, NumPy  
- **Visualization**: Seaborn, Matplotlib  
- **Notebook Environment**: Jupyter Notebook

---

## Setup Instructions
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/la-crime-analysis.git
   cd la-crime-analysis
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn jupyter
3. Run Jupyter Notebook
4. Open and run crime_analysis.ipynb

---

## Contact Information
LinkedIn: [Kian Gabriel Padua](www.linkedin.com/in/kian-gabriel-padua-0863ab1ab)
Email: kianpadua124@gmail.com




