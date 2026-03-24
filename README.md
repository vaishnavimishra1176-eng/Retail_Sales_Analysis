# Vrinda Store Data Analysis (Interactive Dasboard creating using Ms Excel
# Projective Objective 
 This project analyzes store sales data to generate a Sales Annual Report, highlighting key trends, customer demographics, and business performance over a given period. The report is built by following a structured data analysis workflow, including data cleaning, processing, analysis, and visualization.
# Report Preview
Below is a preview of the dashboard
<img width="707" height="286" alt="Report_Dashboard" src="https://github.com/user-attachments/assets/1498ac53-c9e0-4a16-9b79-a0bd9400c931" />


# Steps Involved
# 1. Data Cleaning
Before analysis, we ensured data consistency and accuracy:
- **Checked for null values** and handled missing data appropriately.
- **Standardized gender representation:** Converted m to Men and w to Women.
**Converted categorical numerical values** in the quantity column:
- one → 1
- two → 2

# 2. Data Processing
To enable deeper analysis, new columns were created:
**Age Group Classification:** Grouped customers into categories based on age:
=IF(F2>=50, "Senior", IF(F2>=30, "Adult", "Teenager"))

**Extracting Month from Date:** Created a Month column:
=TEXT(G2, "mmm")

# 3. Data Analysis
We used **Pivot Tables** and aggregations to analyze:
- Sales trends across different time periods.
- Customer demographics and purchasing behaviors.
- The most frequently purchased items and delivery trends.

  # Key Insights from the Report
- **1 Monthly Sales Trends**
### 1. Monthly Sales Trends
- **March recorded the highest sales**, indicating seasonal demand fluctuations.  
- Understanding these trends helps optimize inventory and marketing strategies.  

### 2. Customer Demographics
- **Women made up the majority of purchases**, showing they are the dominant customer segment.  
- **Most sales were from adult women**, emphasizing a key target audience for marketing.  

### 3. Delivery Insights
- **Most of the items were delivered successfully**, indicating an efficient logistics process.  

### 4. Regional Performance
- **Top 5 states contributed the most to sales**, highlighting key regional markets.  
- These states should be the focus for future expansion and targeted promotions.
### 5. Sales Channels
- **35% of sales were made through Amazon**, showcasing its importance as a key sales channel.  
- This suggests the need to enhance digital marketing efforts on e-commerce platforms.  
## Business Recommendations
- **Focus on women customers**, especially the adult segment  
- **Increase marketing on Amazon** to boost online sales  
- **Prepare inventory for March**, considering peak demand  
- **Target top-performing states** like Maharashtra for growth  
- **Maintain strong delivery performance** for customer satisfaction  


