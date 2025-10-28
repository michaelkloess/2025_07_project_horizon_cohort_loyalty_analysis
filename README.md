# 📕 Project_Horizon_Cohort_Loyalty_Analysis

**📌 Project Overview**
This project develops a comprehensive customer segmentation framework for a travel booking platform, to enable personalized marketing strategies and improve customer retention through targeted perk assignment.

## 📕 Business Context

### 📌 Challenge
The Company faces increasing competition in the travel booking market, requiring enhanced customer loyalty and retention strategies. CEO Kevin T. has prioritized strengthening customer relationships through personalized experiences.

### 📌 Solution
Elena T., Head of Marketing, leads the development of a personalized rewards program that highlights specific benefits each customer values most—such as free cancellation or priority check-in—when inviting them to join the program.

### 📌 Objectives
- Identify distinct customer segments with consistent perk preferences
- Assign likely favorite perks to each customer for personalized outreach
- Enable data-driven decision-making for marketing initiatives
- Improve customer lifetime value and retention rates

## 📕 Technology Stack

### 📌 Core Technologies
- **Database:** PostgreSQL with DBeaver
- **Programming:** SQL, Python
- **Development:** Jupyter Notebook, VS Code
- **Libraries:** Pandas, SQLAlchemy, Matplotlib

### 📌 Implementation Approach
- **Data Processing:** SQL aggregations → Python analysis
- **Segmentation:** Rule-based classification 
- **Documentation:** Markdown with Git version control

## 📁 Project Structure

### 📌 Root
- [README.md](./README.md) → Project overview and goals  

---

### 📌 01_docs/ → Business and project documentation
- [00_project_structure.md](./01_docs/00_project_structured.md) → Overview of folders, file purposes, and project organization  
- [01_business_use_case.md](./01_docs/01_business_use_case.md) → Business goals, KPIs, context  
- [02_data_requirements.md](./01_docs/02_data_requirements.md) → Required data sources and fields  
- [03_preparing_data.md](./01_docs/03_preparing_data.md) → Data understanding, cleansing steps  
- [04_data_observations.md](./01_docs/04_data_observations.md) → Observations made during EDA  
- [05_cohort_definition.md](./01_docs/05_cohort_definition.md) → Definition of the agreed cohort segmentation  
- [06_feature_engineering.md](./01_docs/06_feature_engineering.md) → Feature creation methodology and metrics definition  
- [07_customer_segmentation.md](./01_docs/07_segmentation.md) → Customer segments framework and classification logic  
- [08_bias_injection_log.md](./01_docs/08_bias_injection_log.md) → Log of where and how bias was introduced  
- [09_deployment_next_steps.md](./01_docs/09_deployment_next_steps.md) → Recommendations for deployment and validation steps  
- [10_glossary.md](./01_docs/10_glossary.md) → Domain terms and definitions  

---

### 📌 02_data/ → Organized data storage
- [01_interim/](./02_data/01_interim/) → Intermediate cleaned or transformed data  
- [02_processed/](./02_data/02_processed/) → Final datasets ready for analysis/modeling  

---

### 📌 03_notebooks/ → Jupyter notebooks in pipeline order
- [01_exploration.ipynb](./03_notebooks/01_exploration.ipynb) → Initial data exploration and visualization  
- [02_cleansing.ipynb](./03_notebooks/02_cleansing.ipynb) → Data cleansing  
- [03_preprocessing.ipynb](./03_notebooks/03_preprocessing.ipynb) → Preprocessing, feature engineering  
- [04_modeling.ipynb](./03_notebooks/04_modeling.ipynb) → Modeling (rule-based segmentation, perk assignment)  

---

### 📌 04_outputs/ → Outputs generated during analysis
- 01_visuals/ → Plots, charts, heatmaps, segment distributions  
- [02_tables/](./04_outputs/) → Exported results (CSV, Excel, segment assignments)  

---

### 📌 05_reports/ → Final reports and project outcomes
- [01_executive_summary.md](./05_reports/01_executive_summary.pdf) → Executive Summary of results and conclusions  
- [02_detailed_report.pdf](./05_reports/02_detailed_report.pdf) → Detailed report for stakeholders  
- [03_presentation.pdf](./05_reports/03_presentation.pdf) → Presentation slides for stakeholders
- [04_video_presentation.md](./05_reports/04_video_presentation.md) → Presentation video for stakeholders  

## 📕 Customer Segments Identified

### 📌 Seven Distinct Segments

| Segment | Key Characteristics | Business Value |
|---------|-------------------|----------------|
| **Luxury Travelers** | High spending (≥$2000/trip), premium service focus | Highest revenue per customer |
| **Business Travelers** | Short trips, frequent travel, professional focus | High lifetime value, predictable patterns |
| **Family Travelers** | Multiple rooms, extended stays, child-friendly needs | High volume, seasonal predictability |
| **Young Travelers** | Age ≤30, experience-focused, social connectivity | Future high-value, brand advocacy potential |
| **Spontaneous Adventurers** | Last-minute bookings, high conversion rates | Immediate gratification marketing potential |
| **Budget Travelers** | Price-sensitive, discount-driven behavior | Volume-driven revenue through value proposition |
| **Lost Opportunities** | Low conversion, cancellation history | Recovery potential with targeted intervention |

### 📌 Personalized Perk Examples

| Segment | Key Characteristics | Business Value |
|---------|---------------------|----------------|
| **Luxury Travelers** | Concierge service, VIP support, private transfers, exclusive events | Highest revenue per customer through premium offerings |
| **Business Travelers** | Subscription model, lounge access, expense reporting, priority support | High lifetime value and predictable demand |
| **Family Travelers** | Kids stay free, family bundles, child-friendly content, travel insurance | Strong seasonal demand and group-oriented revenue |
| **Young Travelers** | Social sharing bonuses, group discounts, event tickets, gamified badges | Future growth potential and strong brand advocacy |
| **Spontaneous Adventurers** | Last-minute deals, instant bonuses, mystery trips, flash sales | High conversion from urgency-driven offers |
| **Budget Travelers** | Discount cards, price alerts, cashback, upgrade surprises | Large customer base driven by value sensitivity |
| **Lost Opportunities** | Reactivation campaigns, personal vouchers, simplified rebooking | Revenue recovery and churn reduction potential |

## 📕 Technical Implementation

### 📌 Data Processing
- **Cohort:** Users with >7 sessions after January 5, 2023
- **Feature Engineering:** 35+ behavioral and spending metrics
- **Segmentation Logic:** Hierarchical rule-based classification
- **Validation:** A/B testing framework for effectiveness measurement

### 📌 Key Technologies
- **SQL:** Data cleaning, feature engineering, segmentation logic
- **Python:** Data analysis, visualization, modeling pipeline
- **Jupyter Notebooks:** Interactive analysis and documentation

## 📕 Project Timeline

### 📌 Development Phases {09.06.2025 - 11.07.2025 | 33 Tage}

**Week 1 - EDA - Exploring the Data:**
- Familiarize with business context and available data
- Clean and prepare data for analysis
- Create session-level and user-level aggregated tables
- Understand data structure and quality issues

**Week 2 - Feature Engineering - Devising Metrics:**
- Identify key customer characteristics for segmentation
- Create combined metrics that capture customer behavior
- Perform aggregations from session to user level
- Develop meaningful attributes for customer differentiation

**Week 3 - Customer Segmentation - Grouping Customers:**
- Perform customer analysis using engineered metrics
- Identify distinct customer groups and their characteristics
- Assign appropriate perks to each segment
- Validate segment definitions and business relevance

**Week 4 - Presentation:**
- Create executive summary and stakeholder presentations
- Develop data storytelling with compelling visualizations
- Provide recommendations for success measurement
- Document deployment and next steps

## 📕 Current Status

### 📌 Completion Overview
- 🟢 **Documentation:** Complete (11/11 files)
- 🟢 **Data Pipeline:** Complete with processed datasets
- 🟢 **Feature Engineering:** Complete with 35+ metrics
- 🟢 **Segmentation Logic:** Complete with 7 segments and perk assignments
- 🟡 **Validation:** Pending A/B testing implementation
- 🔴 **Production Deployment:** Awaiting validation results

### 📌 Key Deliverables
- Comprehensive customer segmentation framework
- Personalized perk assignment system
- Detailed documentation and implementation guides
- Stakeholder presentation materials
- Deployment and validation roadmap

## 📕 Next Steps

### 📌 Immediate Priorities
1. **A/B Testing:** Implement validation framework to measure segmentation effectiveness
2. **Survey Collection:** Gather customer feedback on perk preferences
3. **Performance Monitoring:** Establish metrics for segment success measurement
4. **Iterative Refinement:** Optimize thresholds and criteria based on validation results

### 📌 Success Metrics
- Increased conversion rates by segment
- Improved customer lifetime value
- Enhanced retention rates
- Positive customer satisfaction with personalized experiences

**Contact:** For questions about this project, please refer to the comprehensive documentation in the `01_docs/` folder or reach out to the project team.
