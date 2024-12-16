# **Employee Data Analysis Project**

## **Project Overview**
This project analyzes employee data from ABC Company, consisting of **458 rows** and **9 columns**. The main objectives are to preprocess the dataset, perform analysis tasks to extract meaningful insights, and visually present findings to understand workforce distribution, salary patterns, and correlations.

---

## **Dataset**
The dataset provided contains the following columns:
- `Name` - Name of the employee
- `Team` - Team to which the employee belongs
- `Position` - Position or role of the employee
- `Age` - Age of the employee
- `Height` - Height of the employee (preprocessed)
- `Salary` - Salary of the employee

**Number of Records**: 458  
**Number of Features**: 9

---

## **Preprocessing Steps**
1. **Height Correction**: The `Height` column was corrected by replacing existing data with random values between **150** and **180** using the `random` function to ensure consistency.
2. **Data Integrity Check**: The dataset was scanned for missing or duplicate values. No null values were found, ensuring clean and reliable data for analysis.

---

## **Analysis Tasks and Findings**
The following tasks were performed on the dataset:

### **1. Team Distribution**
- **Objective**: Determine the distribution of employees across each team and calculate their percentage split relative to the total number of employees.
- **Method**: Value counts were computed for the `Team` column, and percentages were calculated using the total dataset length.
- **Visualization**: A **pie chart** was used to represent the team-wise distribution of employees.

**Key Insight**: The workforce is evenly distributed across most teams, with the **New Orleans Pelicans** having a slightly higher employee count.

### **2. Segregation by Position**
- **Objective**: Group employees based on their roles within the company.
- **Method**: Value counts were applied to the `Position` column to identify the most common roles.
- **Visualization**: A **bar chart** was used to display the frequency of each position.

**Key Insight**: **Shooting Guards (SG)** and **Power Forwards (PF)** are the most common roles, reflecting their strategic importance.

### **3. Predominant Age Group**
- **Objective**: Identify the predominant age group of employees.
- **Method**: Age values were grouped into bins (18-25, 26-35, and 36-45) and analyzed.
- **Visualization**: A **histogram** was used to display the age distribution.

**Key Insight**: Over **51%** of employees fall in the **26-35** age group, indicating a focus on experienced yet youthful talent.

### **4. Salary Expenditure by Team and Position**
- **Objective**: Identify which team and position contribute the most to salary expenditure.
- **Method**: Grouping by `Team` and `Position` while summing the `Salary` column.
- **Visualization**: 
   - **Bar chart** for team-wise salary expenditure
   - **Horizontal bar chart** for position-wise salary allocation

**Key Insight**: The **Cleveland Cavaliers** lead in salary expenditure. Positionally, **Centers (C)** and **Point Guards (PG)** command the highest salaries.

### **5. Correlation between Age and Salary**
- **Objective**: Investigate whether there is a correlation between `Age` and `Salary`.
- **Method**: A correlation coefficient was calculated, and a regression plot was created.
- **Visualization**: A **scatter plot** with a regression line was used.

**Key Insight**: A **slight positive correlation** (0.21) exists between age and salary. While experience leads to higher pay, younger employees with exceptional talent also earn competitive salaries.

---

## **Graphical Representations**
To present the findings effectively, the following visualizations were created:
1. **Pie Chart**: Team distribution
2. **Bar Chart**: Employee count by position
3. **Histogram**: Age group distribution
4. **Bar Chart**: Salary expenditure by team
5. **Scatter Plot with Regression Line**: Correlation between age and salary

Each graph was designed to highlight trends, patterns, and relationships within the dataset.

---

## **Insights Gained**
The analysis yielded the following key insights:
1. **Balanced Workforce**: Teams have an even distribution of employees, with minor variations.
2. **Role Importance**: Positions such as **Shooting Guards**, **Power Forwards**, and **Point Guards** are critical to game strategies.
3. **Youth Focus**: The majority of employees fall in the **26-35** and **18-25** age groups, reflecting the sport's physical demands.
4. **Salary Priorities**: High salaries are concentrated in teams like the **Cleveland Cavaliers** and roles like **Centers** and **Point Guards**.
5. **Performance vs. Experience**: While age correlates with salary, younger players with exceptional talent receive competitive compensation.

These insights can help organizations make strategic decisions regarding **talent acquisition**, **salary planning**, and **role prioritization**.

---

## **Technologies and Libraries Used**
- **Python**: Core programming language
- **Pandas**: Data preprocessing and analysis
- **Matplotlib** and **Seaborn**: Data visualization
- **NumPy**: Numerical operations

---

## **Conclusion**
This project successfully analyzed employee data, uncovering trends in team distribution, role importance, age dynamics, and salary allocation. The visualizations effectively communicated the insights, providing a data-driven perspective on workforce strategies.

---

## **How to Run the Code**
1. Ensure you have **Python 3.x** installed.
2. Install required libraries using the following command:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
3. Run the script in any Python IDE or Jupyter Notebook.

---

