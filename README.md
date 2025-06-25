# 📊 Facebook Ad Statistical Analysis
**Capstone Project | Meta Marketing Analytics Certificate**  
*Author: Chinelo Lydia Nweke*

![Facebook vs AdWords Capstone Dashboard](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/397bd6bc96998aa6237dfd3f659147dbbe5f5c5c/facebook%20dashboard.png?raw=true)

---

## 📁 Project Repository

- Dataset: Capstone Dataset (AdWords & Facebook Campaigns)
- Presentation Slides: [`Facebook ad analysis.pptx`](./Facebook%20ad%20analysis.pptx)
- Tools: **Microsoft Excel**, **PowerPoint**

---

## 🌟 Project Summary (STAR Method)

**S - Situation:**  
Our team was given a 2023 marketing dataset comparing Facebook and AdWords ad campaigns. The business question was: _Which platform delivers more conversions and why?_

**T - Task:**  
As a Marketing Analyst, I was tasked with using statistical techniques to evaluate ad performance and generate insights that could guide future marketing decisions.

**A - Action:**  
I used Excel to calculate measures of central tendency and spread, visualize relationships with charts, perform hypothesis testing, and run a linear regression model. I presented these insights visually in a PowerPoint deck.

**R - Result:**  
I found that Facebook Ads consistently yielded higher conversions and a stronger correlation between clicks and conversions. The regression model projected conversion outcomes based on ad click volume, allowing for better future planning.

---

## 🎯 Project Objectives <a name="objectives"></a>
Compare clicks vs. conversions for both platforms

Use descriptive statistics to summarize campaign performance

Identify correlations between ad interactions and conversions

Test for statistically significant differences using hypothesis testing

Build a simple regression model to predict conversions

---

## 🧪 Methodology <a name="methodology"></a>
✔️ Descriptive Statistics:

Mean, median, mode, and standard deviation of clicks and conversions

Frequency distribution and histograms to check for normality

✔️ Variable Classification:

Determined variable types (Quantitative, Continuous, Dependent/Independent)

✔️ Hypothesis Testing:

Conducted a two-sample t-test to assess conversion differences

Defined null and alternative hypotheses

✔️ Regression Modeling:

Built a simple linear regression in Excel to predict conversions from clicks

Evaluated model with R² and p-values

✔️ Data Visualization:

Created scatter plots, frequency tables, histograms, and correlation charts

Designed PowerPoint visuals to support business storytelling

---
## 📊 Key Analytical Steps & Visualizations

### 1. 🧮 Measures of Central Tendency

- **Charts Used:** Summary Table
- **Insights:**
  - Mean Clicks: 44 | Median: 43 | Mode: 36  
  - Mean Conversions: 11 | Median: 12 | Mode: 13  
  These statistics show a relatively symmetric distribution, giving us a reliable center point for both clicks and conversions.

---

### 2. 📈 Measures of Spread
![Descriptive Statistics Summary](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/d663f9e8706eddb5fb56d9dd5d4d0779a0a1194c/Screenshot%202025-06-19%20200146.png?raw=true)
- **Charts Used:** Standard Deviation Summary
- **Standard Deviations:**
  - Clicks: 12.14  
  - Conversions: 2.92  
- **Impact:**  
  This low spread in conversion data suggests more consistent performance, making Facebook Ads a predictable option.

---

### 3. 📊 Frequency Table
![Clicks Frequency Table](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/d663f9e8706eddb5fb56d9dd5d4d0779a0a1194c/Screenshot%202025-06-19%20111727.png?raw=true)
![Clicks Frequency Table](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/d663f9e8706eddb5fb56d9dd5d4d0779a0a1194c/Screenshot%202025-06-19%20111727.png?raw=true)
- **Chart Type:** Bar Chart
- **Insight:**  
  By categorizing conversions (e.g. <6, 6–10, 11–15, >15), I observed that most days fall into the 6–15 conversions range, confirming mid-level daily performance.

---

### 4. 📉 Scatter Plot + Correlation Coefficient
![Hypothesis Testing Summary](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/d663f9e8706eddb5fb56d9dd5d4d0779a0a1194c/Screenshot%202025-06-19%20034431.png?raw=true)
- **Correlation Coefficient:** **0.86**  
- **Chart Type:** Scatter Plot with Trendline  
- **Insight:**  
  A very strong positive relationship between Facebook Ad Clicks and Conversions suggests that increased ad clicks significantly influence conversions.

---

### 5. 🧪 Hypothesis Testing (T-Test)
![Regression Analysis Chart](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/98a155bd483b626851f05b9ee279d88fbfb96430/regression%20analysis.png?raw=true)
- **Hypothesis:** Facebook Ads will result in higher conversions than AdWords.
- **Result:** P-value < 0.05 → Statistically significant  
- **Conclusion:** Facebook outperforms AdWords in conversion rates with statistical confidence.

---

### 6. 📉 Simple Linear Regression Model
![Descriptive Statistics Summary](https://github.com/Chinel0/Facebook-vs.-AdWords-Ad-Performance-Marketing-Analytics-Capstone/blob/d663f9e8706eddb5fb56d9dd5d4d0779a0a1194c/Screenshot%202025-06-19%20200146.png?raw=true)
- **Chart Used:** Regression Line Chart  
- **Model:**  
  - **Equation:** Conversions = 0.31 × Clicks + 0.34  
  - **R² Value:** 0.77  
- **Insight:**  
  This model predicts that every 10 additional Facebook clicks yield ~3 more conversions. This is a strong case for scaling Facebook Ads.

---

## 📸 Suggested Visual Enhancements (If You Upload to GitHub)
To make your README more interactive, consider adding:

| Section                    | Suggested Visual                  | File Name Example         |
|---------------------------|-----------------------------------|---------------------------|
| Central Tendency          | Table or Screenshot               | `central_tendency.png`    |
| Standard Deviation        | Summary Chart                     | `std_deviation_chart.png` |
| Frequency Distribution    | Bar Chart                         | `conversion_buckets.png`  |
| Correlation & Scatterplot | Scatter Plot with Trendline       | `scatterplot_clicks.png`  |
| Regression                | Line Chart with Forecast Overlay  | `regression_model.png`    |
| Hypothesis Testing        | Annotated T-Test Output Screenshot| `t_test_output.png`       |

---

## 🧠 Business Impact

- 📈 **Increased ROI Awareness:** Campaign budget can now focus more on Facebook Ads based on evidence.
- 📊 **Predictable Performance:** Regression model gives marketing teams confidence in conversion forecasting.
- 🤝 **Cross-Team Value:** Insights are visualized clearly for both technical and non-technical stakeholders.

---

## 📌 Next Steps & Suggestions

- Create an automated dashboard to update these KPIs monthly.
- Perform similar analysis for other KPIs (CPC, CTR).
- Test ad segmentation by audience demographics.

---

## 📬 Contact
Chinelo Lydia Nweke  
Working Student | Data & Marketing Analytics  
📍 Germany  
📧 [Your Email] | 🌐 [Your LinkedIn]

---

> “Data tells a story. My job is to make sure it’s heard — clearly, confidently, and in a way that drives better decisions.”
