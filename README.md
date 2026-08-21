# Geldium AI-Powered Collections Strategy

## About the Project

This project looks at how data and AI can help Geldium identify customers who may be at risk of delinquency and make Collections outreach more targeted.

The project follows the journey from **exploring the customer data → planning a predictive model → turning the findings into business recommendations → designing an AI-powered Collections strategy**.

## What I Worked On

### 1. Exploratory Data Analysis

I analyzed the customer dataset to understand its quality, identify important patterns, and find factors that could be linked to delinquency.

Some of the key risk indicators identified were:

- Credit Utilization
- Missed Payments
- Debt-to-Income Ratio
- Credit Score
- Income

The analysis also highlighted some customer groups with higher observed delinquency rates, including unemployed customers and certain credit-card segments.

### 2. Predictive Model Plan

For the delinquency prediction problem, I selected **Logistic Regression** as the primary modeling approach.

The model would predict:

- `0` → Non-delinquent
- `1` → Delinquent

The main features considered were:

- Credit Utilization
- Missed Payments
- Income
- Debt-to-Income Ratio
- Account Tenure

Logistic Regression was selected because it works well for binary outcomes, is relatively easy to interpret, and provides a practical approach for financial risk prediction.

### 3. Business Recommendation

One of the key findings was that customers with higher Credit Utilization showed slightly higher delinquency risk.

Based on this insight, I proposed a **6-week pilot of targeted early-payment reminders** for customers with high Credit Utilization.

The target was to achieve a **10% reduction in late or missed payments** among the targeted customers during the pilot.

The idea was to start with a relatively simple and supportive intervention, measure the results, and expand it only if the pilot proves effective.

### 4. AI-Powered Collections Strategy

The final stage focused on designing a high-level AI-powered Collections system.

The proposed workflow is:

**Customer Data → Risk Assessment → Decision → Action → Learning**

The system would use customer and payment information to assess risk, select appropriate interventions, personalize outreach, and monitor the results.

Agentic AI could help automate routine activities and adapt strategies based on outcomes, while human staff would remain involved in complex, disputed, or high-impact cases.

## Responsible AI

Because this involves financial decisions, fairness and transparency are important parts of the proposed system.

The strategy includes:

- **Fairness:** Checking whether certain customer groups are treated differently.
- **Explainability:** Making risk predictions understandable to stakeholders.
- **Human Oversight:** Keeping people involved in complex and high-impact decisions.
- **Compliance:** Maintaining appropriate records and aligning the system with applicable regulations.
- **Transparency:** Clearly communicating how AI-driven predictions are being used.

## Expected Business Value

The proposed approach could help Geldium:

- Identify potentially high-risk customers earlier.
- Prioritize Collections outreach more effectively.
- Reduce unnecessary customer contact.
- Improve repayment outcomes.
- Scale targeted interventions.
- Support more consistent and transparent decision-making.

## Project Deliverables

This project includes:

- Exploratory Data Analysis Report
- Predictive Model Plan
- Business Summary Report
- AI-Powered Collections Strategy Presentation

## Tools & Skills

- Microsoft Excel
- Exploratory Data Analysis
- Data Analytics
- Predictive Modeling Concepts
- Generative AI
- Responsible AI
- Business Analytics
- Data Storytelling

## Note

This was completed as a **conceptual case-study/job-simulation project**. The predictive model and AI-powered Collections system described here are proposed approaches and are not presented as production-deployed systems.