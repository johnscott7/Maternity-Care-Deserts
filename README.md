<h1 align="center">
  <img src="https://raw.githubusercontent.com/johnscott7/Maternity-Care-Deserts/main/docs/MaternalHealthcareDeserts_Illustration_MollyFerguson.jpg" 
  alt="MaternityHealthCareDesert_Illustration_MollyFerguson" 
  width="800">
  <br>
</h1>

# Maternity Care Deserts: Declining Perinatal and Maternal Health Outcomes in the United States

## Table of Contents
- [1. Business Issue](#1-business-issue)
- [2. Business Use Case](#2-business-use-case)
- [3. Data Sources](#3-data-sources)
- [4. Project Structure](#4-project-structure)
- [5. Methodology](#5-methodology)
- [6. Results and Insights](#6-results-and-insights)

---

## 1. Business Issue
The United States has maternal mortality rates two to three times higher than those of other high-income nations. Several factors contribute to this crisis, including hospital closures, Medicaid coverage gaps, abortion restrictions, and the growing number of “maternal care deserts.”  
The steady decline in maternity care access across the country remains poorly understood yet well-documented, making it a strong topic for data-driven analysis.

This project explores the following questions:  
- How has the erosion of maternity care access over the past 10–15 years affected maternal and perinatal health outcomes across U.S. counties and states?  
- What associations exist between declining access and key health indicators such as maternal morbidity, prenatal care timing, and infant outcomes?  
- Which counties and socioeconomic groups are most affected by access loss?

Understanding these patterns is critical for healthcare systems and policymakers aiming to reduce inequities in maternal care. This project seeks to identify high-risk communities and quantify the correlations between declining access and negative maternal and perinatal outcomes.

> **Note:** While this topic leans toward research-style analysis, the project focuses on building a data-driven framework using accessible public datasets. Some data limitations exist at the county level compared to more readily available state-level data.

---

## 2. Business Use Case
This analysis can help:
- Health systems and policymakers identify geographic areas where declining maternity care access poses the highest risk  
- Researchers and advocacy groups prioritize interventions and resource allocation  
- Public health agencies design strategies to mitigate disparities in maternal and perinatal outcomes  

---

## 3. Data Sources
### Primary Dataset
- [2010–2022 County-Level Hospital-Based Obstetric Care Status](https://rhrc.umn.edu/publication/2010-2022-county-level-hospital-based-obstetric-care-status/)  
  (Rural Health Research Center, University of Minnesota)

### Related Datasets
- [CDC WONDER Natality Data (2007–2024)](https://wonder.cdc.gov/natality.htm)  
- [HRSA Infant Health Data](https://data.hrsa.gov/topics/maternal-child-health/mchb-mapping)  
- [County Health Rankings: Low Birth Weight (2011–2025)](https://www.countyhealthrankings.org/health-data/population-health-and-well-being/quality-of-life/physical-health/low-birth-weight?year=2025)  
- [HRSA Data Downloads (County-Level Health Data)](https://data.hrsa.gov/data/download)  
- [JAMA Network Open – U.S. Maternal Morbidity Report](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2794738)  

---

## 4. Project Structure
```bash
data/           # raw and cleaned datasets
notebooks/      # Jupyter notebooks for analysis and visualization
scripts/        # Python scripts for data processing
visuals/        # static charts, figures, and maps
docs/           # documentation and banner image
```
## 5. Methodology
- Compile county- and state-level maternity care access data  
- Join with maternal and infant outcome metrics (e.g., low birth weight, morbidity)  
- Perform exploratory data analysis and correlation testing  
- Visualize trends in maternity care access over time  
- Identify high-risk counties through quantitative and geographic analysis  

## 6. Results and Insights
- To be completed following completion of exploratory and statistical analysis.