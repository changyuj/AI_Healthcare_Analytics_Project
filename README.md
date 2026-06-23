# AI Healthcare Analytics: Measuring the Impact of AI-Assisted Diagnostics in Healthcare Operations

## Executive Summary

Artificial Intelligence (AI) is transforming healthcare by improving clinical workflows, reducing operational delays, and supporting healthcare professionals in decision-making. 

This project analyzes the impact of implementing an AI-assisted diagnostic system within a healthcare environment. The goal is to evaluate whether AI improves operational efficiency, diagnostic quality, and clinician productivity.

Because real-world healthcare AI performance data is restricted due to patient privacy regulations and proprietary healthcare systems, a synthetic dataset was created to simulate a realistic healthcare AI implementation scenario.

The analysis compares healthcare performance before and after AI adoption using key performance indicators (KPIs), including:

- Turnaround Time (TAT)
- Diagnostic Amendment Rate
- AI Agreement Rate
- Department Performance
- Clinical Workload Impact

The project was first developed using Microsoft Excel dashboards and will later be expanded into Power BI, Tableau, and Python analytics workflows.

---

# Business Problem

Healthcare organizations continuously face challenges including:

- Increasing patient volume
- Long diagnostic turnaround times
- Clinical staff workload pressures
- Need for improved accuracy and consistency

Healthcare leaders need data-driven insights to determine whether AI investments create measurable improvements.

This project addresses the following business questions:

1. Does AI reduce diagnostic turnaround time?

2. Does AI improve diagnostic accuracy by reducing report amendments?

3. How does AI adoption impact healthcare department performance?

4. Can AI help clinicians process more cases efficiently?

---
# Methodology

## 1. Data Generation

A synthetic healthcare dataset was created to represent a healthcare organization before and after AI implementation.

Dataset characteristics:

- 3,000 simulated healthcare cases
- Time period: July 2024 - June 2026
- AI implementation date: January 1, 2025

Dataset fields include:

| Column | Description |
|---|---|
| Case_ID | Unique patient case identifier |
| Date_Received | Date case entered workflow |
| Department | Healthcare department |
| Complexity_Score | Case difficulty rating (1-5) |
| AI_Assisted | Whether AI support was used |
| Turnaround_Time_Hours | Time required to complete diagnosis |
| Amendment_Required | Whether report correction was needed |
| Clinician_ID | Healthcare provider identifier |
| AI_Concordance | Agreement between AI recommendation and clinician decision |

---

## 2. Data Preparation

The dataset was prepared and cleaned using Microsoft Excel.

Steps performed:

- Generated healthcare workflow data
- Created AI adoption logic based on implementation date
- Simulated realistic turnaround times
- Simulated diagnostic error reduction
- Converted dynamic formulas into static values
- Created calculated fields for analysis

---

## 3. Data Analysis

Excel Pivot Tables were used to analyze:

### Operational Efficiency

Compared average turnaround time:

- Before AI implementation
- After AI implementation

### Quality Improvement

Measured:

- Diagnostic amendment rates
- AI-assisted accuracy

### Department Performance

Analyzed:

- Radiology
- Pathology
- Cardiology
- Oncology

---

## 4. Dashboard Development

An interactive Excel dashboard was created containing:

- KPI summary cards
- AI vs Non-AI comparison charts
- Department performance analysis
- AI agreement visualization
- Interactive filtering using slicers

---

# Skills Demonstrated

## Data Analytics

- Data Cleaning
- Data Transformation
- KPI Development
- Business Analysis
- Performance Measurement

## Microsoft Excel

- Advanced Excel Formulas
- Pivot Tables
- Pivot Charts
- Dashboard Design
- Data Visualization

## Healthcare Analytics

- Healthcare workflow analysis
- Clinical operations metrics
- AI adoption evaluation
- Healthcare performance improvement

## Future Expansion

This project will continue into:

- Power BI
- Tableau
- Python
- Machine Learning

---

# Results & Business Recommendation

## Key Findings

The analysis evaluated the impact of AI-assisted diagnostics by comparing healthcare workflow performance between AI-assisted and non-AI-assisted cases.

The analysis focused on three main areas:

- Turnaround time improvement
- Error reduction
- Department-level workflow performance

--

## 1. AI Improved Diagnostic Turnaround Time

The analysis showed that AI-assisted cases had a significantly lower average turnaround time compared to non-AI-assisted cases.

### Average Turnaround Time Comparison

|  Workflow Type  | Average Turnaround Time |
|-----------------|-------------------------|
| Non-AI Assisted | 19.05 hours             |
| AI Assisted     | 9.66 hours              |

AI-assisted workflows reduced average turnaround time by:

**9.39 hours per case**

This represents approximately:

**49.3% reduction in turnaround time**

The results suggest that AI support can help healthcare teams complete diagnostic workflows faster and improve operational efficiency.

---

## 2. AI Adoption and Diagnostic Amendment Analysis

The dataset included 3,000 simulated healthcare cases to evaluate report amendment requirements.

### Amendment Distribution

|  Amendment Required   | Number of Cases |
|-----------------------|-----------------|
| No Amendment Required | 1,192           |
| Amendment Required    | 1,808		  |

The analysis identified a higher number of amendment cases within the dataset.

Further investigation is recommended to analyze amendment rates by:

- AI-assisted vs non-AI-assisted cases
- Department
- Case complexity
- Clinician workflow patterns

This highlights the importance of monitoring AI performance using quality-focused metrics in addition to efficiency metrics.

---

## 3. Department Performance Analysis

AI-assisted workflows improved turnaround time across all healthcare departments.

| Department | Non-AI Average TAT | AI Average TAT |
|------------|--------------------|----------------|
| Cardiology | 19.21 hrs          | 9.56 hrs       |
| Oncology   | 18.28 hrs          | 9.18 hrs       |
| Pathology  | 19.58 hrs          | 9.74 hrs       |
| Radiology  | 19.22 hrs          | 10.12 hrs      |

Key observations:

- Oncology showed the lowest AI-assisted turnaround time at **9.18 hours**
- Cardiology achieved a reduction of approximately **50%**
- Pathology and Radiology also showed significant workflow improvement

The consistent reduction across departments suggests AI assistance can improve efficiency regardless of clinical specialty.

---

# Business Recommendation

Based on the analysis, AI-assisted diagnostic technology shows potential to improve healthcare operational performance.

Recommended actions:

1. Expand AI adoption in departments with high diagnostic volume and longer processing times.

2. Continue tracking turnaround time improvements after AI implementation.

3. Monitor quality metrics such as amendment rates, diagnostic accuracy, and clinician agreement.

4. Evaluate AI impact by department and case complexity to identify areas where AI provides the greatest benefit.

5. Use continuous analytics dashboards to measure AI effectiveness and support future technology investments.

---

# Key Business Insight

The analysis demonstrates that AI can provide measurable improvements in healthcare workflow efficiency.

While AI reduced turnaround time by nearly 50%, additional quality analysis is needed to determine its long-term impact on diagnostic accuracy and reporting improvements.

---

# Next Steps

## Power BI Development

The next phase will rebuild this dashboard using Power BI.

Planned improvements:

- Interactive executive dashboard
- DAX calculations
- Drill-through analysis
- Automated KPI reporting

---

## Tableau Development

The Tableau version will focus on:

- Advanced storytelling
- Interactive visual analytics
- Healthcare leadership reporting

---

## Python Analytics

The Python version will include:

- Data loading with Pandas
- Data cleaning automation
- Statistical analysis
- Visualization using Matplotlib
- Machine Learning models

Potential ML questions:

- Predict turnaround time
- Identify factors affecting delays
- Predict likelihood of report amendments

---

# Project Author

YU JU CHANG

Data Analytics | Healthcare Technology | AI Applications
