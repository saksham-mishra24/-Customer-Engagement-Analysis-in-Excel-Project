# 📊 **Confidence Intervals: Task 3**

## **Overview**
In this task, we analyze student engagement data to determine **95% confidence intervals** for four groups of students:
1. **Non-paid subscribers** who engaged in Q4 2021.
2. **Non-paid subscribers** who engaged in Q4 2022.
3. **Paid subscribers** who engaged in Q4 2021.
4. **Paid subscribers** who engaged in Q4 2022.

The goal is to identify the range of minutes within which we can be **95% confident** that a randomly selected student from each group will fall. This analysis helps us understand the variability and consistency of engagement levels across different student segments.


---
### **📂 How to Proceed**

1. Open the file **`Engagement project.xlsx`**.  
2. Navigate to the **`Task 3`** sheet.  
3. For each group, calculate:  
   - **Confidence Interval (CI)** using the **Z-statistic**.  

---

### **🧑‍💻 Calculation Steps**  

1. **Identify Key Metrics**:  
   - Mean engagement (minutes).  
   - Standard deviation.  
   - Sample size (n).  

2. **Apply Confidence Interval Formula**:  
   \[
   CI = \mu \pm Z \cdot \left(\frac{\sigma}{\sqrt{n}}\right)
   \]  
   Where:  
   - \( \mu \): Sample mean  
   - \( \sigma \): Standard deviation  
   - \( Z \): Z-statistic for 95% confidence level (\( Z = 1.96 \))  
   - \( n \): Sample size  

3. **Interpret Results**:  
   - Compare engagement intervals across the four groups.  
   - Identify trends and patterns in engagement over Q4 2021 and Q4 2022.  


The table below summarizes the **95% confidence intervals** for each group:

| Group                        | Mean Minutes Watched | Confidence Interval (95%)       |
|------------------------------|----------------------|----------------------------------|
| Non-paid subscribers (2021)  | [X]                 | [X - Y] to [X + Y] minutes       |
| Non-paid subscribers (2022)  | [X]                 | [X - Y] to [X + Y] minutes       |
| Paid subscribers (2021)      | [X]                 | [X - Y] to [X + Y] minutes       |
| Paid subscribers (2022)      | [X]                 | [X - Y] to [X + Y] minutes       |

---

## **🔗 Deliverables**

- 📊 **Confidence Intervals**: For all four groups.  
- 📈 **Engagement Trends**: Insights into how engagement has shifted.  
- 💡 **Conclusions**: Recommendations for boosting student engagement.  

---

## **✨ Key Insights**

- Are **paid-plan subscribers** more engaged than non-paid-plan students?  
- How has engagement evolved from **Q4 2021** to **Q4 2022**?  
- What do the confidence intervals reveal about the consistency of engagement?  
- **Non-paid Subscribers**: Engagement levels showed **[increase/decrease]** from 2021 to 2022, with confidence intervals indicating **[high/low]** variability.
- **Paid Subscribers**: Engagement levels were consistently **[higher/lower]** than non-paid subscribers, with narrower confidence intervals suggesting more consistent behavior.
- **Overall Trend**: The introduction of new platform features in 2022 likely contributed to **[increased/decreased]** engagement, particularly among paid subscribers.
---

## **💡 Why Confidence Intervals?**  
Confidence intervals provide a robust statistical tool to estimate the range within which a population parameter is likely to fall. In this task, they help analyze:  
- Engagement consistency across time and subscription types.  
- Potential areas for enhancing the platform’s value to students.  


## **Conclusion**
- **Non-paid Subscribers**: Represent a key area for improvement. Strategies to increase their engagement could significantly impact overall platform usage.
- **Paid Subscribers**: Demonstrate higher and more consistent engagement, highlighting the value of premium features.
- **Confidence Intervals**: Provide a clear understanding of the range within which student engagement levels fall, helping to identify trends and variability.

---

## **Next Steps**
- Perform **hypothesis testing** to validate the significance of observed differences.
- Use **visualizations** (e.g., bar charts, error bars) to further explore the data.
- Develop actionable recommendations to improve engagement for non-paid subscribers.

---

## **Tools Used**
- **Microsoft Excel**: For data cleaning, analysis, and calculations.
- **z-Statistic**: For calculating confidence intervals.

---

## **How to Use This Repository**
1. Download the `Engagement Project.xlsx` file.
2. Open the file in Microsoft Excel and navigate to the `Task 3` sheet.
3. Follow the steps outlined above to replicate the analysis.

---

Feel free to clone this repository, explore the calculations, and share your findings! 💻📘  

💡 *Let’s collaborate and make data-driven decisions!*  


