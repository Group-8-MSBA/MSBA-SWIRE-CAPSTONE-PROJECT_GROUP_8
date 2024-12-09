# Swire Coca-Cola Capstone Project (Group 8)

---

## Business Problem and Objective

Swire Coca-Cola, one of the largest Coca-Cola bottlers in the United States, operates across six production plants, producing approximately 192 million cases annually. However, frequent unplanned machine downtimes have led to significant operational inefficiencies and financial losses. These downtimes result in only 94.4% of production demand being met, costing the company an estimated $60 million annually.

The primary objective of this project is to design a predictive maintenance solution that accurately forecasts machine breakdowns, reduces unplanned downtimes, optimizes maintenance workflows, and enhances overall production capacity to meet 100% of demand.

---

## Group’s Solution to the Problem

Our solution follows the **CRISP-DM framework** and combines advanced predictive modeling with strategic business recommendations:

1. **Data Understanding and Preparation:**
   - Analyzed over 1.4 million maintenance records to uncover patterns in downtime frequency, duration, and root causes.
   - Addressed data quality challenges by carefully handling missing values and outliers to ensure analytical accuracy.

2. **Feature Engineering:**
   - Developed critical features such as **median survival days** for equipment, downtime trends, and failure patterns.
   - Focused on granular insights, including breakdown analysis by equipment type, plant location, and maintenance type.
   - **Granular Insights:**
   - Extracted key features, including equipment ID, breakdown count, and functional area, to identify high-risk equipment prone to frequent failures.
   - **MTBF (Mean Time Between Failures):**
   - Calculated MTBF to quantify the reliability of equipment by measuring the average time between breakdowns. 
   - For instance, equipment with ID `300115000` (L1 Filler Rotary Can 72 Valve) had a **MTBF of 0.476 days**, indicating highly frequent breakdowns. This equipment requires prioritized maintenance to minimize        disruptions.
   - **Breakdown Trend Analysis:**
   - Identified seasonal peaks in breakdown frequency and equipment-specific trends to enhance maintenance scheduling.
   - **Functional Area Mapping:**
   - Mapped failures to granular functional areas, such as conveyors and fillers, to pinpoint bottlenecks and allocate resources efficiently.
   - **Median Survival Days:**
   - Used survival analysis to compute the median operational lifespan for equipment and predict potential failures.
   - **Downtime Quantification:**
   - Quantified the financial impact of downtimes by analyzing actual work minutes lost and categorizing planned versus unplanned maintenance events.

3. **Predictive Modeling:**
   - Implemented **Kaplan-Meier survival analysis** and **Cox proportional hazards modeling** to estimate time-to-failure for high-risk equipment.
   - Applied **ARIMA time-series forecasting** to predict maintenance needs based on seasonal and historical trends.

4. **Business Recommendations:**
   - Transitioned from reactive to **proactive maintenance** strategies.
   - Optimized **inventory planning** to ensure availability of critical spare parts.
   - Prioritized **seasonal maintenance** activities to address peak breakdown periods.

5. **Strategic Results:**
   - Identified actionable insights to reduce unplanned breakdowns by 70%.
   - Proposed a downtime reduction goal of 5.6%, potentially saving Swire Coca-Cola approximately **10.7 million cases annually**, translating to substantial cost savings.

---

## Group Member Contributions

| **Name**               | **Contribution's**                                                                                                                                                                                                                              |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Adarsh Fnu**          | - Explored data columns and created insightful visualizations.<br> - Investigated different modeling techniques suitable for the business case.<br> - Performed feature importance analysis and articulated the modeling process.<br> - Analyzed patterns and provided insights into the time between failures.<br> - Interpreted plots and results, deriving actionable insights.<br> - Proofread the document, ensuring accuracy and clarity throughout. |
| **Charith Reddy Gopavaram** | - Broke down the dataset to better understand the data and case objectives.<br> - Created visual analyses to enhance dataset comprehension.<br> - Performed seasonal decomposition on maintenance data to identify trends, seasonal variations, and residual components.<br> - Applied modeling techniques like Kaplan-Meier on key packaging lines.<br> - Designed visualizations and meticulously worked on the document's organization and readability.<br> - Proofread the document, ensuring precision and coherence throughout. |
| **Dheeraj Yata**        | - Conducted data exploration, providing valuable insights into trends and visualizations.<br> - Identified potential factors impacting machine downtime.<br> - Made informed decisions on imputation strategies tailored to variable characteristics.<br> - Conducted feature importance analysis to pinpoint key contributors to downtime.<br> - Worked on time-series models, Kaplan-Meier, and Cox Proportional Models to uncover deeper insights.<br> - Proofread the document, ensuring thoroughness and accuracy. |

---

## The Business Value of the Solution

Our solution delivers measurable business benefits:

1. **Operational Excellence:**
   - Reducing unplanned downtimes boosts production uptime and minimizes operational disruptions.
   - By predicting breakdowns, plants can schedule maintenance efficiently, ensuring steady production flow.

2. **Cost Efficiency:**
   - A 70% reduction in unplanned maintenance can save millions annually, reducing waste and optimizing resources.

3. **Improved Inventory Management:**
   - Accurate predictions ensure critical spare parts are stocked, avoiding delays in repairs and minimizing idle time.

4. **Enhanced Customer Satisfaction:**
   - Meeting 100% of production demand improves delivery timelines, strengthening customer relationships.

5. **Scalable Insights:**
   - The models and recommendations can be applied across plants, creating a unified framework for predictive maintenance.

---

## Challenges Faced

1. **Data Quality:**
   - Over 80% missing data in critical columns posed challenges for modeling. Instead of simplistic imputation, innovative strategies ensured analytical integrity.

2. **Seasonality and Trends:**
   - Accounting for variations in breakdown frequency during peak production periods required advanced temporal analysis.

3. **Complex Relationships:**
   - Interdependencies between equipment type, plant conditions, and maintenance types required sophisticated modeling approaches.

4. **Stakeholder Alignment:**
   - Translating technical insights into actionable recommendations for business stakeholders involved balancing depth and simplicity.

---

## Lessons Learned

1. **Strategic Data Handling:**
   - Gained expertise in managing large, imperfect datasets without compromising model performance or insights.

2. **Advanced Modeling Techniques:**
   - Learned to implement and interpret survival analysis, time-series forecasting, and multivariate models for predictive maintenance.

3. **Importance of Business Alignment:**
   - Ensured that technical solutions were tied directly to Swire Coca-Cola’s operational goals, emphasizing ROI and scalability.

4. **Team Collaboration:**
   - Leveraged diverse strengths within the team to deliver a cohesive and impactful solution.

---

## Key Takeaways

This project underscores the transformative power of predictive analytics in operational efficiency. By leveraging advanced modeling and actionable business recommendations, we enabled Swire Coca-Cola to transition from reactive to proactive maintenance, significantly enhancing productivity and profitability.

**Our vision: A future where Swire Coca-Cola experiences minimal downtime, maximized efficiency, and unparalleled customer satisfaction.**
