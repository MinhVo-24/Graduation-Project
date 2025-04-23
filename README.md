**Enhancing IT Helpdesk Efficiency through Data-Driven Analysis of Support Tickets based on Customer Satisfaction**

**1. Project Goals**
The objective of this project is to analyze IT helpdesk support ticket data to enhance operational efficiency and customer satisfaction. The key goals include:
•	Identifying factors affecting customer satisfaction
•	Understanding correlations between ticket severity, priority, requestor seniority, and satisfaction.
•	Detecting inefficiencies and anomalies in ticket handling.
•	Building predictive models for ticket resolution time and customer satisfaction.
•	Providing data-driven recommendations to optimize IT helpdesk processes.
________________________________________
**2. Data Sources Used**
The dataset used in this project is historical IT helpdesk support ticket data. 
Source: Public dataset from Kaggle (Analyze Helpdesk Tickets Dataset: Analyze Helpdesk tickets)
https://www.kaggle.com/datasets/sudhanshu746/analyze-helpdesk-tickets

File’s name: WA_Fn-UseC_-IT-Help-Desk.csv

It includes information on ticket severity, priority, requestor seniority, resolution time (daysOpen), and customer satisfaction scores. The dataset is structured and cleaned for analysis.
________________________________________
**3. Data Overview**
     **3.1 Data Description**
This dataset contains records of IT help desk support tickets. It is typically used for analyzing support ticket handling, predicting ticket escalation, response time, and customer satisfaction, among other use cases.
    **3.2 Columns Description**
•	Ticket ID: Unique identifier for each support request.
•	Requestor: Anonymized ID of the person who raised the ticket
•	IT Owners: Anonymized ID of the IT staff member responsible. 
•	FiledAgainst:  The department or system the issue is related to.
•	Priority: Numerical representation of ticket priority (1 - Low, 2 - Medium, 3 - High).
•	Severity: Numerical representation of issue severity (1-Minor, 2-Normal, 3-Major, 4- Critical)
•	RequestorSeniority: Seniority level of the requestor (e.g., 1-Junior, 2- Regular, 3-Senior, 4-Management).
•	Satisfaction: Customer satisfaction score (e.g., scale from 1-Unsatisfied, 2-Neutral,3-Satisfied, 4-Highly satisfied).
•	daysOpen: Number of days taken to resolve the ticket.
•	Other categorical and numerical attributes related to ticket details.
________________________________________
**4. Tools and Technologies Applied**
•	Programming Language: Python (pandas, numpy, seaborn, matplotlib, scikit-learn)
•	Data Processing: Pandas, NumPy
•	Exploratory Data Analysis (EDA): Seaborn, Matplotlib
•	Machine Learning Models: Linear Regression, Decision Trees, Random Forest, Logistic Regression
•	Data Visualization: Correlation heatmaps, boxplots, scatter plots
•	Anomaly Detection: IQR
________________________________________
**5. Key Insights Discovered**
•	Higher severity and priority tickets tend to be resolved faster.
•	Tickets with longer resolution times correlate with lower customer satisfaction.
•	The requestor’s seniority impacts ticket priority but not necessarily resolution time.
•	Certain outliers in daysOpen indicate potential inefficiencies in ticket handling.
________________________________________
**6. Hypotheses Based on the Insights**
•	H1: High-priority tickets are resolved faster than low-priority tickets.
•	H2: Increased resolution time negatively impacts customer satisfaction.
•	H3: Senior employees' tickets are handled faster due to priority assignment.
•	H4: Outliers in ticket resolution indicate inefficiencies in workflow management.
________________________________________

**7. Recommendations Based on Analysis Results**
•	Optimize Ticket Prioritization: Implement an AI-driven ticket triaging system.
•	Improve SLA Compliance: Set clear benchmarks to ensure quick resolutions.
•	Enhance Customer Communication: Listen to Customers. Proactively follow up on unresolved tickets.
•	Monitor Outliers: Identify and investigate delayed tickets to improve efficiency.
•	Workforce Optimization: Assign tickets dynamically based on real-time workload.
________________________________________
This project provides a data-driven approach to enhancing IT helpdesk efficiency, reducing resolution time, and improving customer satisfaction.
