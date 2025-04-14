# **Overview**

Our project investigates the relationship between work-life balance (WLB) and employee performance in competitive industries like information technology. Using the CRISP-DM (Cross Industry Standard Process for Data Mining) framework, we analyzed two large datasets with over 100,000 employee records to explore whether WLB directly impacts performance metrics such as productivity and task quality, with a focus on the mediating role of psychological empowerment.

The study combines statistical analysis and machine learning to uncover patterns in WLB policies (e.g., remote work, overtime) and their effects on performance. Our findings challenge the assumption that WLB directly enhances performance, offering insights for organizations on how to approach WLB initiatives and performance evaluations.

## **Key Findings**
1. **Limited Direct Impact of WLB on Performance:**
   - WLB features like remote work, overtime, and satisfaction scores had a weaker influence on employee performance than anticipated.
   - Structural factors such as salary, tenure, and job role were stronger predictors of performance outcomes across both datasets.
2. **WLB Enhances Well-Being, Not Productivity:**
   - Statistical tests (e.g., ANOVA, chi-square) and machine learning models (Logistic Regression, Random Forest, XGBoost) showed that WLB significantly boosts job satisfaction and retention but does not directly translate to higher performance scores.
   - This aligns with the Job Demands-Resources (JD-R) Model, which suggests WLB acts as a resource for employee well-being rather than a direct driver of measurable productivity.
3. **Challenges in Data Modeling:**
   - Both datasets suffered from class imbalance in performance ratings, with most records clustered around "Average" (class 3), making it hard for models to predict minority classes (Low, Below Average, High).
   - Techniques like SMOTE, class weighting, and feature engineering (e.g., WLB_Composite score) were used to address these issues, but limitations persisted due to inherent data constraints.
4. **Implications for Organizations:**
   - WLB programs should be viewed as long-term investments for improving engagement, morale, and retention rather than expecting immediate performance gains.

## **Future Work**
- **Improved Data Collection:** Gather datasets with more granular WLB metrics and balanced performance ratings to reduce modeling challenges.
- **Alternative Metrics:** Explore non-traditional performance indicators (e.g., collaboration, innovation) to capture WLB’s broader impact.
- **Longitudinal Analysis:** Study WLB’s effects over time to better understand its role in retention and engagement.
