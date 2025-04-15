
# 🏘️ Tenant Retention Optimization  
**Building an Interactive Power BI Dashboard for Residential Real Estate Excellence**

> End-to-end data analytics solution leveraging Power BI for optimizing tenant retention in the real estate industry.

---

## 📊 Project Overview

This project offers hands-on experience in designing a full-scale data analytics pipeline tailored for residential real estate. Using Power BI, it covers:

- 🔗 Data Integration
- 🔄 Data Transformation
- 📈 Data Analysis and Modeling
- 📊 Dashboard Development
- 📤 Deployment & Reporting
- 🔁 Continuous Improvement

---

## 🏢 Business Context

**HomeVibe Properties** is a well-established name in the residential real estate industry, managing a wide range of apartment complexes and single-family rentals across multiple cities. With a focus on exceptional tenant experiences, they aim to strengthen community living.

Despite their success, HomeVibe faces increasing **tenant churn**, threatening profitability and community cohesion. This project demonstrates how I used **Power BI** to build an interactive dashboard to:

- Understand tenant behavior  
- Identify churn patterns  
- Improve lease renewal processes  
- Enhance tenant satisfaction  
- Make data-driven decisions

---

## ❗ Business Problem

Key challenges identified by HomeVibe:

- ⚠ **High Tenant Churn Rates** – Increased turnover leads to higher operational costs and revenue loss  
- 📉 **Limited Tenant Insights** – Lack of data visibility hampers proactive issue resolution  
- 📝 **Inefficient Lease Renewals** – Tedious processes lower satisfaction and retention  
- 📊 **No Trend Identification** – Difficulty spotting patterns limits strategy development

---

## 💡 Project Rationale

Why this project matters in real estate:

- 💰 **Enhanced Revenue** – Retaining tenants reduces vacancy loss  
- 🗣️ **Stronger Brand Reputation** – Happy tenants = free marketing  
- 🧾 **Operational Efficiency** – Streamlined workflows save resources  
- 🧠 **Data-Driven Strategy** – Gain a competitive edge with insights  
- 🌍 **Sustainable Growth** – Fewer turnovers = less environmental impact

---

## 🎯 Project Objectives

- ✅ **Design Interactive Dashboard** in Power BI focused on tenant retention  
- ✅ **Analyze Historical Data** to uncover churn patterns and tenant behavior  
- ✅ **Optimize Lease Renewals** with data-driven strategies

---

## 🗃️ Data Description

The project uses **4 interconnected datasets**:

### 1. Tenant Information  
| Column | Description |
|--------|-------------|
| Tenant ID | Unique identifier |
| Tenant Name | Full name |
| Contact Details | Email or phone |
| Lease Start/End Date | Duration of lease |

### 2. Lease Details  
| Column | Description |
|--------|-------------|
| Lease ID | Unique lease identifier |
| Lease Term | Duration in months |
| Rent Amount | Monthly rent |
| Payment History | Total payments made |

### 3. Tenant Feedback  
| Column | Description |
|--------|-------------|
| Feedback ID | Feedback entry ID |
| Survey Response | Satisfaction level |
| Comments | Open-ended feedback |

### 4. Property Information  
| Column | Description |
|--------|-------------|
| Property ID | Unique property ID |
| Location & Type | Address, type (e.g. apartment) |
| Amenities | Listed features |
| Historical Occupancy | % occupancy rate |

#### erDiagram
    TENANT ||--o{ LEASE : "1:N"
    TENANT ||--o{ FEEDBACK : "1:N"
    PROPERTY ||--o{ LEASE : "1:N"
---

## 🛠️ Tech Stack

**Component** | **Tool**
------------ | ------
ETL | Power Query
Data Modeling | Power BI Desktop
Visualization | Custom Power BI themes
Deployment | Power BI Service + Teams integration


---

## 🔍 Project Scope

- 🧪 **Exploratory Data Analysis** – Identify data patterns  
- 🔧 **Data Transformation** – Clean, encode, normalize  
- 📊 **Visualization** – Interactive charts and graphs  
- 🧠 **Insight Generation** – Extract and interpret key findings  
- 📤 **Reporting** – Share dashboards for strategic decisions

---
## Success Metrics
| KPI | Baseline | Target |
|-----|---------|--------|
| Annual Churn | 76.6% | ≤30% |
| Renewal Rate | 23.4% | ≥75% |
| Satisfaction | 3.01| 4.5 |

---

## 📈 Insights Uncovered

- 📅 **Seasonal Churn Trends** – The line chart of churn rate by month reveals seasonal patterns or specific times of the year when churn rates spike, indicating that **April** and **August** are the two months where targeted retention efforts could be most beneficial  
- 📃 **Lease Term Preferences** – The frequency distribution of lease terms highlights tenant preferences, showing whether shorter or longer leases correlate with higher retention rates, suggesting adjustments to lease offerings.
- 😌 **Tenant Satisfaction Matters** – Analysis from the bar chart showing satisfaction scores and the combo chart correlating churn status with satisfaction scores by property type provide concrete evidence that higher satisfaction levels are crucial for reducing churn rates.
- 💸 **Financial Efficiency** – Rent collection performance insights highlight operational efficiencies or issues affecting the company’s financial health and its ability to invest in property improvements and tenant services. 
- 📆 **Renewal Strategy Effectiveness** – The comparison of renewed versus expired leases over time can indicate the success of recent retention strategies or highlight the need for new approaches.

---

## 🧭 Recommendations

- 🎯 **Targeted Retention Programs** – Implement Targeted Retention Programs: Based on identified churn patterns, develop targeted retention programs during high-risk periods, such as personalized communication, special offers, or community events to engage tenants.  
- 📑 **Lease Term Adjustments** – Offer more flexible or preferred lease terms to new and renewing tenants to encourage longer stays terms that align with high retention for lease lengths that correlate with higher retention, 
- 🌟 **Boost Satisfaction** – Prioritize improvements in areas directly impacting tenant satisfaction, as identified through survey responses. This could include property amenities, maintenance responsiveness, and community-building efforts. 
- 💳 **Optimize Payments** – Simplify rent collection; reward on-time payers
- 🌱 **Sustainability perks** (e-bike discounts for renewals)
---


---

## 📎 Resources

- 📄 [Case Study PDF](#)
- 📊 [Live Dashboard (Power BI Service)](#) 
- 📁 [Raw Datasets (CSV)](#)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
