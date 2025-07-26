# hr-analytics-dashboard-power-bi
This project presents an in-depth analysis of employee attrition using a comprehensive HR analytics dashboard. By dissecting key demographic, job role, and tenure-related factors, this dashboard provides actionable insights to understand the drivers of employee turnover,  optimize retention strategies, and enhance overall workforce stability. 

# HR Analytics Dashboard: Understanding and Mitigating Employee Attrition

## Executive Summary:
This project conducts a comprehensive analysis of an HR analytics dashboard to dissect employee attrition patterns, evaluate key HR metrics, and uncover critical insights into workforce stability. The goal is to provide data-driven recommendations that prioritize retention strategies, enhance employee engagement, and inform targeted HR interventions. 

## Problem Statement:

The primary objective was to transform raw HR data into actionable intelligence across key workforce areas:

- **Attrition Identification**: To precisely identify the most significant contributors to employee attrition across job roles, demographic segments (age, gender, education), and tenure.
  
- **HR Metric Evaluation**: To delve into crucial metrics such as overall attrition rate, average age, average salary, and average years at the company to guide strategic HR resource allocation.
  
- **Employee Behavioral Insights**: To understand the patterns of employee turnover based on various attributes, informing personalized retention strategies and tailored HR programs.

## Data Sources and Engineering:

This project utilized a publicly available HR transactional dataset, HR_Analytics.csv, obtained from Kaggle, as depicted in the provided HR Analytics Dashboard. The dataset contains comprehensive employee information, including demographics, job roles, and employment history. Key metrics and breakdowns are derived from this underlying dataset.

My data engineering process (as implemented within Power BI or a preceding data preparation step) involved:

- **Data Acquisition**: Sourcing the publicly available HR dataset from Kaggle.
  
- **Data Cleaning and Preprocessing**: Handled missing values, identified and removed duplicate entries, and addressed potential outliers in numerical fields (e.g., salary, years at company) to ensure data integrity. Ensured consistent data types.
  
- **Feature Engineering**: Created new meaningful features and calculated key performance metrics from the raw HR data to support deeper analysis, including:
  - Attrition Status (derived from employee records)
  - Age Groups
  - Salary Bands
  - Tenure (Years at Company)
  - Attrition Rate
  - Count of Employees

## Methodology:

The analytical approach for this project was multi-faceted, focusing on turning HR data into actionable business intelligence through the Power BI dashboard:

- **Exploratory Data Analysis (EDA)**: Performed initial data inspection and summarization within Power BI to understand the dataset's structure and quality.
  
- **Overall Attrition Analysis**: Calculated and visualized the total count of employees, the number of attritions, and the overall attrition rate. Summarized average age, salary, and years at company for the workforce.
  
- **Segmented Attrition Analysis**: Analyzed attrition distribution across different employee segments using Power BI's visualization capabilities:
  
  - **Attrition by Job Role**: Identified job roles with the highest attrition numbers.
    
  - **Attrition by Years at Company**: Examined attrition trends based on employee tenure, highlighting critical periods of turnover.
    
  - **Attrition by Demographics**: Analyzed attrition based on Education Field, Age Groups, Salary Bands, and Gender to pinpoint vulnerable segments.
    
- **Identification of High-Risk Groups**: Pinpointed specific employee groups exhibiting higher attrition rates based on the segmented analysis presented in the dashboard.

## Key Findings and Impact:

- **Overall Attrition**: The company faces a significant attrition rate of 16.1%, with 237 employees having left out of 1470. The average employee age is 37, average salary is 6.5K, and average tenure is 7.0 years.
  
- **Job Role Hotspots**: Laboratory Technicians (62) and Sales Executives (57) exhibit the highest numbers of attrition, indicating potential challenges specific to these roles. Research Scientists (47) and Sales Representatives (33) also show notable attrition.
  
- **Early Tenure Attrition**: Attrition is highest in the first year of employment (59 employees), followed by year 3 (43 employees), year 4 (26 employees) and year 2 (44 employees), suggesting potential issues with onboarding, initial role fit, or early career development. There's also a smaller peak around 10 years (18 employees).
  
- **Age Group Vulnerability**: The 26-35 age group (44 employees) shows the highest attrition, followed by the 36-45 age group (43 employees), potentially indicating mid-career dissatisfaction or external opportunities.
  
- **Education Field Impact**: Life Sciences (38%) and Medical (27%) account for a significant portion of attrition by education, followed by Marketing (15%) and Technical Degree (14%).
  
- **Salary Band Analysis**: Attrition is most prominent in the 'Upto 5k' salary band (116 employees), suggesting that compensation might be a factor for employees in lower salary brackets.
  
- **Gender Distribution**: Male attrition (150) is higher than female attrition (87) in absolute numbers.

## Strategic Recommendations:

- **Targeted Retention for High-Attrition Job Roles**:

  - Develop specific retention programs for Laboratory Technicians and Sales Executives, focusing on career progression opportunities, workload management, recognition programs, and skill development relevant to their roles.

- **Enhance Onboarding and Early Career Support**:

  - Implement robust onboarding programs and mentorship initiatives for new hires, particularly during their first year, to improve integration and reduce early turnover.
  - Conduct early-tenure check-ins to address challenges and provide support.

- **Address Mid-Career and Compensation Concerns**:

  - Investigate the underlying reasons for attrition in the 26-35 age group and the 'Upto 5k' salary band. This may involve reviewing compensation competitiveness, offering professional development, and promoting work-life balance initiatives.

- **Education-Specific Interventions**:

  - Explore the specific drivers of attrition within Life Sciences and Medical education fields. Tailor retention efforts, such as specialized training, research opportunities, or competitive benefits packages, to address their unique needs.

- **Further Gender-Based Analysis**:

  - While male attrition is higher, conduct qualitative analysis (e.g., exit interviews, surveys) to understand specific reasons for attrition across both genders to develop more nuanced retention strategies.

## Tools and Technologies:

- **Data Visualization & Analysis**: Power BI

- **Data Source**: HR_Analytics.csv from Kaggle

## Visualisations:

- HR Analytics Dashboard Overview (Key Metrics)

- Attrition by Job Role

- Attrition by Years at Company

- Attrition by Education

- Attrition by Age

- Attrition by Salary

- Attrition by Gender
