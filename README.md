# 🚀 Bus Pricing Analysis (Data Analytics Assignment)

## 📌 Objective
The goal of this project was to analyze bus pricing data and identify whether listings are overpriced, underpriced, or fairly priced compared to similar buses.

---

## 🔍 Problem Statement
Given a dataset of bus listings, determine pricing efficiency by comparing each listing with similar buses based on:
- Route
- Bus Type

---

## ⚙️ Approach

### 1. Defining Similar Buses
- Grouped data using:
  - Route
  - Bus Type

### 2. Price Benchmarking
- Calculated **Average Similar Price** using Excel:
  - `AVERAGEIFS` function

### 3. Price Comparison
- Price Difference = Price - Avg Similar Price  
- % Price Difference = (Price Difference / Avg Similar Price) * 100  

### 4. Flag Logic
Used conditional logic:

- "Too High" → if % difference > 15  
- "Too Low" → if % difference < -15  
- "OK" → otherwise  

---

## 📊 Output Columns

- Route Number  
- Bus Type  
- Operator  
- SRP Rank  
- Price  
- Avg Similar Price  
- Price Difference  
- % Price Difference  
- Flag (Too High / Too Low / OK)

---

## 🛠 Tools Used

- Microsoft Excel
  - AVERAGEIFS
  - IF logic
  - Percentage calculations
- AI Tools (ChatGPT):
  - Helped structure the approach
  - Assisted in formula validation
  - Helped debug errors (#REF, incorrect outputs)

---

## 🤖 Use of AI (As Required)

As mentioned in the assignment, AI tools were used intentionally:

- Designed the step-by-step analytical approach
- Validated Excel formulas
- Helped troubleshoot calculation errors
- Assisted in improving logic clarity and efficiency

---

## 📈 Key Insights

- A large number of listings were **underpriced**
- Significant price variation exists across operators
- Weighted/average benchmarking helped identify anomalies clearly

---

## ⚡ Automation & Scalability

- The solution is **fully formula-driven**
- Can be directly applied to the full dataset
- No manual intervention required after setup
- Easily scalable for larger datasets

---

## 📌 Note

- Initial analysis was performed on a **sample dataset**
- Logic was then applied to the **full dataset**
- Sheet 3 contains working calculations
- Final output is presented in Sheet 1

---

## 📎 Files Included

- Excel file with:
  - Raw Data
  - Working Sheet (calculations)
  - Final Output Sheet

---

## 💡 Outcome

This project helped strengthen:
- Data analysis thinking
- Excel skills
- Real-world problem solving using structured logic

---

## 🔗 Connect With Me
Feel free to connect or reach out for opportunities!
