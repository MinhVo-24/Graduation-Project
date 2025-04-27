# Enhancing IT Helpdesk Efficiency through Data-Driven Analysis of Support Tickets based on Customer Satisfaction

## 📄 Overview
In today's digital environment, IT Helpdesk performance is crucial for maintaining user satisfaction and operational efficiency.  
This project explores how analyzing support ticket data can enhance helpdesk services, identify factors impacting customer satisfaction, and propose actionable improvements.

---

## 🎯 Project Purpose and Outcome

### Purpose
- Understand operational performance of the IT Helpdesk team by examining key metrics such as ticket aging (daysOpen), priority handling, and customer satisfaction.
- Identify key drivers influencing customer satisfaction, such as resolution time, ticket priority, issue severity, and requestor seniority.
- Uncover inefficiencies in ticket resolution processes, allowing better resource allocation and service improvements.
- Provide data-driven recommendations to optimize Helpdesk efficiency, reduce response and resolution times, and increase customer satisfaction rates.

### Outcomes
- Clear understanding of how long tickets stay open, which types of tickets cause delays, and how seniority or issue type affects ticket flow.
- Identification of factors that positively or negatively impact customer satisfaction ratings.
- Discovery of relationships between daysOpen, priority, severity, and satisfaction scores — e.g., strong negative correlation between daysOpen and satisfaction.
- Concrete recommendations to streamline Helpdesk processes — like faster assignment of high-priority tickets, or better handling of specific FiledAgainst categories.
- Creation of dashboards and visual reports that track performance over time.

---

## 📊 Data Sources Used

- **Source**: Public dataset from Kaggle: [Analyze Helpdesk Tickets Dataset](https://www.kaggle.com/datasets/sudhanshu746/analyze-helpdesk-tickets)
- **File name**: `WA_Fn-UseC_-IT-Help-Desk.csv`
- **Content**: Ticket severity, priority, requestor seniority, resolution time (daysOpen), and customer satisfaction scores.

---

## 📈 Data Overview

### Data Description
This dataset contains records of IT help desk support tickets, typically used for analyzing support ticket handling, predicting ticket escalation, response time, and customer satisfaction.

- **Ticket ID**: Unique identifier for each support request.
- **Requestor**: Anonymized ID of the person who raised the ticket.
- **IT Owners**: Assigned IT support staff or owner responsible for handling and resolving the ticket.
- **FiledAgainst**: Department, system, or application the ticket is related to (e.g., Network, Software, Hardware).
- **Ticket Type**: Classification of the ticket (e.g., Incident, Request, Problem).
- **Priority**: Level of importance assigned to the ticket (e.g., High, Medium, Low).
- **Severity**: Indicates how critical or urgent the ticket is (e.g., Critical, Major, Minor).
- **RequestorSeniority**: Job level or seniority of the requestor (e.g., Junior, Senior, Manager).
- **Satisfaction**: Customer’s satisfaction rating after ticket resolution (e.g., Satisfied, Unsatisfied).
- **daysOpen**: Number of days the ticket remained open (from creation to closure).

---

## 🛠 Tools and Technologies Applied

- **Programming Language**: Python (pandas, numpy, seaborn, matplotlib, scikit-learn)
- **Data Processing**: Pandas, NumPy
- **Exploratory Data Analysis (EDA)**: Seaborn, Matplotlib
- **Machine Learning Models**: Linear Regression, Decision Trees, Random Forest, Logistic Regression
- **Data Visualization**: Correlation heatmaps, boxplots, scatter plots
- **Anomaly Detection**: IQR method

---

## 🔍 Key Insights Discovered

- Higher severity and priority tickets tend to be resolved faster.
- Tickets with longer resolution times correlate with lower customer satisfaction.
- Requestor’s seniority impacts ticket priority but not necessarily resolution time.
- Certain outliers in daysOpen indicate potential inefficiencies in ticket handling.

---

## 🧪 Hypotheses Based on the Insights

- **H1**: High-priority tickets are resolved faster than low-priority tickets.
- **H2**: Increased resolution time negatively impacts customer satisfaction.
- **H3**: Senior employees' tickets are handled faster due to priority assignment.
- **H4**: Outliers in ticket resolution indicate inefficiencies in workflow management.

---

## 📋 Recommendations Based on Analysis Results

- **Optimize Ticket Prioritization**: Implement an AI-driven ticket triaging system.
- **Improve SLA Compliance**: Set clear benchmarks to ensure quick resolutions.
- **Enhance Customer Communication**: Proactively follow up on unresolved tickets.
- **Monitor Outliers**: Identify and investigate delayed tickets to improve efficiency.
- **Workforce Optimization**: Dynamically assign tickets based on real-time workload.

---

## 🚀 Project Vision Statement

> "Empowering the IT Helpdesk to deliver faster, smarter, and more satisfying support experiences by unlocking the hidden insights within support ticket data.  
Through data-driven analysis, we aim to transform service operations, elevate customer satisfaction, and enable proactive, efficient IT support management."

---

