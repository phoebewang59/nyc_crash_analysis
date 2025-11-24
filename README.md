# NYC Motor Vehicle Crash Analysis

This repository presents an exploratory analysis of the **NYC OpenData Motor Vehicle Collisions – Crashes** dataset. The objective is to identify the factors most associated with motor vehicle crashes in New York City and examine how these factors vary across **time** and **crash severity**. This project demonstrates skills in exploratory data analysis, data cleaning, visualization, and interpretation of large, real-world datasets (~2.1 million rows).

All analysis is contained in the notebook: [Transportation Data Science Project](notebooks/TDSP_Phoebe_Wang.ipynb)

---

## **Research Goals**

- Identify the most common contributing factors in NYC vehicle crashes  
- Examine hourly and weekly crash patterns, with a focus on driver inattention  
- Compare crash severity (injury/fatality) across the top contributing factors  

The analysis highlights both behavioral patterns (e.g., distracted driving) and system-level trends (time-of-day, day-of-week risks).

---

## **Methods Overview**

This project uses:
- **Python (pandas, seaborn, matplotlib)** for data processing and visualization  
- **Datetime engineering** for temporal pattern analysis  
- **Severity classification logic** to evaluate outcomes  
- **Exploratory analysis** to assess missingness and dataset quality  

Visualizations include:
- Frequency plots of contributing factors  
- Hourly and weekly time-series patterns  
- Pie charts comparing severity distributions  

---

## **Key Findings**

- **Top contributing factors:**  
  **Driver inattention/distraction**, **failure to yield right-of-way**, and **following too closely**.
  
- **Time patterns:**  
  Distracted-driving crashes peak between **3–5 PM**, consistent with afternoon congestion.

- **Day patterns:**  
  **Fridays** experience the highest number of distracted-driving collisions.

- **Crash severity:**  
  Most crashes cause no injuries, but among major factors, **failure to yield** has the highest injury proportion (~41%).

These results highlight how human behavior, traffic volume, and temporal factors interact to shape crash risk in NYC.

---

## **Repository Contents**

- `notebooks/` — Main Jupyter notebook containing the full crash analysis  
- `figures/` — Exported plots generated from the analysis  
- `writeup/` — Research poster summarizing the key results from the full notebook

---

## **Acknowledgements**
This project was completed as part of the NEBDHub/NSDC transportation data program, with support from Emily Rothenberg and the U.S. DOT FHWA.
