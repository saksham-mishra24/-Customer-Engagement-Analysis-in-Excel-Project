
# **📊 Hypothesis Testing : Task 4 & 5**

Welcome to the **Hypothesis Testing Analysis**! 🎓🔍  
This project focuses on conducting **t-tests** and **f-tests** to evaluate the impact of the platform's new features and regional engagement patterns.

---

## **📌 Task Overview**

### **🚀 Task 4: Do New Features Increase Engagement?**

#### **Objective**
Evaluate whether the platform's new features have contributed to an increase in engagement (minutes watched) for:  
1. **Free-Plan Students** (2021 vs. 2022).  
2. **Paying Students** (2021 vs. 2022).

---

#### **💡 Null Hypotheses**  
- **Free-Plan Students**: \( \mu_{2021} \geq \mu_{2022} \)  
- **Paying Students**: \( \mu_{2021} \geq \mu_{2022} \)

---

#### **🔍 Assumptions & Tests**
1. **Two-Sample T-Test**:  
   - Assume **unequal variances** for both free-plan and paying students.  
2. **Optional**: Perform a **Two-Sample F-Test** to verify variance assumptions.

---

#### **📈 Formulae Used**

**T-Test Formula**:  
\[
T = \frac{(\bar{x} - \bar{y}) - \mu_d}{\sqrt{\frac{s_x^2}{n_x} + \frac{s_y^2}{n_y}}}
\]

Where:  
- \( \bar{x} \): Sample mean of group 1  
- \( \bar{y} \): Sample mean of group 2  
- \( \mu_d \): Hypothesized mean difference (usually 0)  
- \( s_x^2 \), \( s_y^2 \): Sample variances of groups  
- \( n_x \), \( n_y \): Sample sizes of groups  

**Degrees of Freedom (df)**:  
\[
df = \frac{\left(\frac{s_x^2}{n_x} + \frac{s_y^2}{n_y}\right)^2}{\frac{\left(\frac{s_x^2}{n_x}\right)^2}{n_x - 1} + \frac{\left(\frac{s_y^2}{n_y}\right)^2}{n_y - 1}}
\]  

- Assume **df = 8,229** (paid-plan) and **df = 40,836** (free-plan).  

---

#### **📊 Deliverables**
- **T-Test Results**: For free-plan and paying students.  
- **Interpretation**: Identify whether engagement improved from Q4 2021 to Q4 2022.  
- **Error Analysis**: Discuss Type I & II errors and their implications on business decisions.  

---

### **🌍 Task 5: Regional Engagement Patterns (US vs. India)**

#### **Objective**
Analyze whether the **free-plan engagement** in 2022 differs between **US** and **India**.  

---

#### **💡 Null Hypotheses**  
1. \( \mu_{US} \geq \mu_{India} \)  
2. \( \mu_{US} < \mu_{India} \)

---

#### **🔍 Assumptions & Tests**
1. **Two-Sample T-Test**:  
   - Assume **unequal variances** between US and India.  
2. **Optional**: Perform a **Two-Sample F-Test** to verify variance assumptions.

---

#### **📈 Formulae Used**

**T-Test Formula**:  
\[
T = \frac{(\bar{x} - \bar{y}) - \mu_d}{\sqrt{\frac{s_x^2}{n_x} + \frac{s_y^2}{n_y}}}
\]  

**Degrees of Freedom (df)**:  
\[
df = \frac{\left(\frac{s_x^2}{n_x} + \frac{s_y^2}{n_y}\right)^2}{\frac{\left(\frac{s_x^2}{n_x}\right)^2}{n_x - 1} + \frac{\left(\frac{s_y^2}{n_y}\right)^2}{n_y - 1}}
\]  

- Assume **df = 11,001**.  

---

#### **📊 Deliverables**
- **T-Test Results**: Compare US and India engagement levels.  
- **Interpretation**: Identify key differences in regional engagement.  

---

## **✨ Key Insights**

- Did the platform’s new features drive engagement?  
- How does engagement differ between US and India?  
- What are the business implications of potential Type I & II errors?  

---


## **💡 Why Hypothesis Testing?**  
Hypothesis testing empowers data-driven decisions by providing statistical evidence for:  
- **Feature Effectiveness**: Validate the impact of platform updates on engagement.  
- **Regional Insights**: Understand localization needs for tailored experiences.  

---

💡 *Explore the repository, replicate calculations, and contribute your insights!*  

---

