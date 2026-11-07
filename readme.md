# 🏢 Executive Project Summary: Employee Retention & Attrition Analysis
**Prepared for:** Salifort Motors Executive Leadership & HR Management  
**Objective:** Understand why employees are leaving and implement a proactive, data-driven system to retain key talent.

---

## 1. 🎯 Why This Project Was Done (The Business Problem)
Replacing talented employees is highly disruptive and expensive. It drains company resources through recruitment costs, onboarding time, and lost productivity. Salifort Motors wanted to transition from being **reactive** (finding out why people left during exit interviews) to being **proactive** (predicting who is at risk of leaving *before* they resign, and fixing the workplace issues driving them out).

---

## 2. 🛠️ What We Did (The Process in Simple Terms)
We analyzed historical records of **14,999 employees** (looking at factors like performance reviews, number of projects, monthly working hours, tenure, promotions, and department). Our process involved:
1. **Data Cleaning:** Standardized all records and eliminated duplicate entries (~3,000 duplicate rows) to ensure our findings were based on unique, high-quality information.
2. **Feature Safeguards (De-biasing):** We intentionally removed "self-reported job satisfaction scores." Why? Because relying on subjective surveys can skew predictions if employees lie out of fear, or if surveys aren't up-to-date. Instead, we created an objective operational metric: **Overworked** (defined as working more than 175 hours/month).
3. **Model Tournament:** We built and trained multiple smart computer models (Logistic Regression, Decision Trees, and a Random Forest) to look at historical patterns and identify which employees are statistically on the verge of quitting.

---

## 3. 🔍 What We Found (The Key Insights)
Our data analysis revealed that **chronic overwork** and **career stagnation** are the root causes of turnover at Salifort Motors:

* **The "Seven-Project" Burnout Limit:** **100% of employees** assigned to 7 projects ended up leaving the company. They were logging an average of 255 to 295 hours per month (equivalent to working over 10 hours a day, including weekends).
* **The Sweet Spot (3–4 Projects):** Employees assigned to exactly 3 or 4 projects had the lowest turnover and the most balanced work-life ratios.
* **The Four-Year Retention Plateau:** Employees reaching 3 to 5 years of tenure are at the highest risk of leaving. This is also when frustration peaks if they have not been promoted.
* **Lack of Career Growth:** Only **2.1%** of all employees received a promotion in the last 5 years. High-performers are leaving because they hit a career ceiling.
* **No Rewards for Extra Effort:** Long working hours were strongly tied to high performance evaluations, yet they almost never led to promotions.

---

## 4. 📈 Our Solution & Its Impact (The Machine Learning Model)
Our final champion model (**Random Forest**) achieved an outstanding **96.2% overall accuracy** on unseen data.

* **How it works:** It looks at an employee's current project load, monthly hours, tenure, and latest review scores, then outputs a risk flag.
* **Catching Churn Early (90.4% Recall):** The model successfully flags **90.4% of all employees** who are genuinely planning to leave, giving HR a valuable window of opportunity to intervene.
* **High Reliability (87% Precision):** When our model flags someone as a flight risk, it is correct **87% of the time**, ensuring HR doesn't waste resources on false alarms.

---

## 5. 💡 Strategic Recommendations for Leadership (Actionable Next Steps)

1. **Cap Project Assignments:** Set a company-wide limit of **maximum 4 to 5 projects** per employee. This immediately eliminates the extreme workloads driving out high-performers.
2. **Target 3-5 Year Tenures:** Initiate career development check-ins and structured milestone reviews for employees reaching their 3rd and 4th years to address stagnation.
3. **Overhaul Performance Evaluations:** Reward quality of output, efficiency, and teamwork, rather than treating raw, excessive working hours as a baseline expectation for a "good" review.
4. **Tie Overwork to Compensation:** Ensure that if overtime is necessary, it is clearly compensated or recognized with formal financial/career growth rewards.
5. **Introduce Cultural Audits:** Have department heads hold regular, psychologically safe check-ins to monitor team-specific workload bottlenecks and cultural pressures.
