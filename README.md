# Excel Project

# 1. Purpose of Project
The purpose of this project was to create an interactive Hospital Emergency Room Analysis Dashboard in Microsoft Excel to enhance operational efficiency
and generate meaningful insights. The dashboard enables stakeholders to monitor performance, analyze patient data, identify trends, and make informed decisions
to improve patient management and overall healthcare services

# 2. Dataset used
- <a href="https://github.com/MonGurung/ExcelProject/blob/main/Dataset.xlsx">Dataset View</a>

# 3. Dashboard
- <a href="https://github.com/MonGurung/ExcelProject/blob/main/Hospital%20ER%20room%20project.xlsx">Dashboard View</a>
## Screenshot of dashboard
<img width="1635" height="882" alt="image" src="https://github.com/user-attachments/assets/7ef19210-683e-4484-a104-6944ccc6f14c" />


# 4. Project Steps

<img width="1294" height="536" alt="image" src="https://github.com/user-attachments/assets/cfd62b29-1e23-40f4-a378-b97ee98dea0a" />

# 5. KPIs Requirement

<img width="1294" height="537" alt="image" src="https://github.com/user-attachments/assets/b6ebab69-1796-45e9-a1c7-1dfb651692d2" />

# 6. Charts to create
<img width="1283" height="573" alt="image" src="https://github.com/user-attachments/assets/ae07f2de-3fcb-4644-b795-442df0f09824" />

## Calender Table Formula used
= List.Dates(#date(2023,01,01),731,#duration(1,0,0,0))

## DAX formulas
DAX Formula for Age Group : 

=IF([Patient Age]>=70,"70-79",IF([Patient Age]>=60,"60-69",IF([Patient Age]>=45,45-59,IF([Patient Age]>=30,"30-44",IF([Patient Age]>=15,"15-29",IF([Patient Age]>=5,"05-14","0-4")))))) 

DAX Formula For Patient Attend Status :

=IF([Patient Waittime]>30,"Delay","Ontime")  


# 7. Findings – January 2024

## Metric	Value

Total patients	        - 513

Avg. wait time      	  - 36.3 min

Satisfaction score	    - 4.96 / 10

Admission rate	        - 52.4%

Patients delayed (>30 min) -	61.6%

Top age group  -	0–9 (76 patients)

Top departments referral - 	General Practice (103), Orthopedics (65)

Gender split -	Male 53% / Female 47%

# 8. Insights

Admission rate too high (52.4%) – Needs observation unit.

Satisfaction very low (4.96) – Poor communication or staff issues.

62% wait >30 min – Staffing mismatch with patient flow.

Children are largest group – Lacks pediatric resources.

GP & Ortho drive volume – Fast-track opportunity.


