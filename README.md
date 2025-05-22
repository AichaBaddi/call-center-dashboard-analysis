# 📞 Sales & Marketing Call Center Dashboard Analysis

## Overview

This repository contains a performance dashboard for a Sales & Marketing Call Center. The dashboard enables dynamic analysis of individual **call agents**, allowing stakeholders to evaluate productivity, customer engagement, and service quality across multiple dimensions.

Users can select an agent to filter the visualized metrics accordingly. The dashboard supports actionable insights related to successful/failed calls, abandonment reasons, customer demographics, call sources, and product-specific performance.



## 📁 Repository Structure

**📦 call-center-dashboard-analysis/**
 - **📊 dashboard/**
   - [dashboard-screenshot:](dashboard-screenshot.PNG)      Exported image of the Excel dashboard
- **📂 excel-files/**
   - [Sales_Marketing_Call_Center:](Sales_Marketing_Call_Center.xlsm)   Main Excel workbook with analysis and dashboard
- **📄 README.md**                Project overview and usage



## Data Sources

Sales and Marketing Call Center Data: The primary dataset used in this analysis is the "[Sales_Marketing_Call_Center](Sales_Marketing_Call_Center.xlsm)" file, which contains detailed information about all sales and marketing calls made by the agent.



## Tools

 **Excel:**
  - **Data Validation**:                           Create drop-downs for clean data entry or filtering.                             
  - **Formulas** (`IF`, `MATCH`, `OFFSET`, etc.): Calculate metrics like success rates, averages, and call durations.              
  - **Conditional Formatting**:                      Highlight performance issues or trends in tables.                                
  - **Pivot Tables**:                               Summarize total calls, status, and performance by agent, product, and geography. 
  - **Slicers**:                                     Filter your dashboard easily by agent, month, or product type.
  - **Pivot Charts**:                                Visualize top agents, state-level calls, and abandonment reasons.                
                   

## 📊 Key Dashboard Metrics

### 🔢 Call Statistics (All Agents)
- **Total Calls**: 200,000
- **Successful Calls**: 83,519 (41.76%)
- **Failed Calls**: 71,837 (35.91%)
- **Abandoned Calls**: 44,644 (22.32%)



### 👩‍💼 Agent Call Volume
- Dashboard displays call totals for each agent.
- Top 5 agents are visualized with color distinction.
- Remaining agents are grouped under "Others".



### 📈 Agent-Specific Insights (via filter)

Each selected agent displays:
- **Total Calls**
- **Call Success Rate**
- **Average Customer Rating**
- **Average Call Duration (min)**
- **Product-wise Success vs. Failure**
- **Call Trends by Month**
- **Abandonment Reasons**
- **Geographic Distribution of Calls**



### 🚫 Common Call Abandonment Reasons
- Technical Issues
- Long Wait Times
- Customer Hangups
- Agent Unavailability



### 🌍 Customer Call Origin (by State)
- The dashboard maps inbound calls geographically.
- Bar and map charts show top 5 states and others.
- Helps identify where agents are engaging most effectively.



### 🕒 Monthly Call Trends
- Trends tracked across all 12 months.
- Highlights minimum and maximum monthly calls per agent.
- Useful for identifying seasonality or peak times.



## ✅ Recommendations for Use

- Use the agent filter to compare individual performance.
- Address top abandonment issues through system or staffing improvements.
- Focus on underperforming products to improve success ratios.
- Expand into states with high call engagement for better regional support.


  

                        


