# E-Commerce Growth & Customer Analytics

An interactive **Power BI e-commerce analytics dashboard** built to analyze business performance across sales, customers, conversion, products, and marketing channels.

The project focuses on turning transactional and clickstream data into **actionable business insights** rather than simply presenting charts.

---

## 📌 Business Problem

E-commerce businesses generate large amounts of data across customer visits, product interactions, orders, reviews, and traffic sources.

The key challenge is:

> **How can an e-commerce business use its data to understand revenue performance, customer behavior, conversion drop-offs, product performance, and traffic-source effectiveness to identify opportunities for growth?**

This project addresses that problem through an interactive Power BI dashboard.

---

## 🎯 Objectives

* Monitor overall **sales and revenue performance**
* Compare current performance with **previous-year performance**
* Understand **customer behavior and engagement**
* Analyze the **customer conversion funnel**
* Identify **product and category performance**
* Evaluate **marketing / traffic-source effectiveness**
* Identify business opportunities through data-driven insights

---

## 📊 Dashboard Pages

### 1. Executive Overview & Sales Performance
<img width="667" height="376" alt="image" src="https://github.com/user-attachments/assets/1e8060fa-a9ca-451a-b33a-5f239d63c926" />

Analyzes overall business performance.

**KPIs:**

* Total Revenue
* Total Revenue PY
* Revenue Growth YOY %
* Total Profit
* Total Orders
* Order Growth %
* AOV

**Analysis includes:**

* Revenue vs Previous Year trend
* Profit vs Previous Year trend
* Orders by category
* Revenue by category
* Top-performing products/categories

---

### 2. Customer Behavior, Engagement & Reviews
<img width="665" height="376" alt="image" src="https://github.com/user-attachments/assets/b1f3bf60-1ae2-4fae-a534-a80174eed291" />

Analyzes how customers interact with the e-commerce platform.

**Analysis includes:**

* Customer activity
* New vs repeat customers
* Device behavior
* Traffic-source behavior
* Purchase frequency
* Spending level
* Review sentiment

Review categories were generalized into:

* **Positive** → Excellent, Good
* **Neutral** → Okay Overall
* **Negative** → Not Buy Again, Very Poor

---

### 3. Conversion Funnel Analysis
<img width="668" height="377" alt="image" src="https://github.com/user-attachments/assets/d4af89e8-7b90-48d6-8cee-0e170a10e11d" />


Analyzes the customer journey from browsing to purchase.

**Funnel:**

`Product View → Add to Cart → Purchase`

**KPIs:**

* Total Sessions
* Unique Visitors
* Product Views
* Add-to-Cart Sessions
* Completed Orders
* Conversion Rate
* Cart Abandonment Rate

The page identifies where customers drop out of the purchasing journey and compares conversion across categories, devices, and traffic sources.

---

### 4. Product & Category Performance
<img width="670" height="372" alt="image" src="https://github.com/user-attachments/assets/e9f7e101-308e-46f9-b193-3c2bb4a7ecb7" />

Analyzes product-level and category-level contribution.

**Analysis includes:**

* Revenue
* Profit
* Units Sold
* Orders
* Product rankings
* Category performance
* Product/category matrix
* Top-performing products

Interactive **field parameters and bookmarks** allow different analytical views without creating separate dashboards for every metric.

---

### 5. Marketing / Traffic Source Performance
<img width="669" height="374" alt="image" src="https://github.com/user-attachments/assets/e140007f-f960-49ed-ae66-5e4a145997da" />

Evaluates the effectiveness of customer acquisition sources.

**KPIs:**

* Marketing Sessions
* Marketing Conversion Rate
* Marketing Revenue
* Revenue per Session
* Marketing Orders
* Traffic Share %
* Revenue Share %

The analysis focuses on identifying traffic sources that generate **valuable customers and revenue**, rather than simply generating visits.

---

## 🧩 Data

The project uses an **E-commerce Transactions & Clickstream** dataset containing information related to:

* Customers
* Sessions
* Events
* Orders
* Products
* Order items
* Reviews
* Traffic sources

A dedicated **Date table** was created for time-based analysis and year-over-year comparisons.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **DAX**
* **Power Query**
* Data Modeling
* Time Intelligence
* Bookmarks
* Buttons
* Field Parameters
* Interactive Slicers
* Dashboard Storytelling

---

## 🔍 Business Questions Answered

The dashboard is designed to answer questions such as:

* Is revenue growing or declining?
* How does current performance compare with the previous year?
* Are orders and AOV improving?
* Who are the most valuable customer segments?
* How do customers behave across devices and traffic sources?
* Where do customers drop out of the conversion funnel?
* Which categories and products contribute most to revenue?
* Which traffic sources generate the best conversion?
* Which acquisition sources generate the most valuable revenue?
* Where are the biggest opportunities for business improvement?

---

## 📈 Business Analytics Approach

The dashboard follows a decision-oriented flow:

```text
Overall Business Performance
          ↓
Customer Behavior
          ↓
Conversion Funnel
          ↓
Product Performance
          ↓
Marketing Performance
          ↓
Business Insights & Opportunities
```

This structure allows a business user to move from **"What is happening?"** to **"Why might it be happening?"** and finally to **"Where should we focus?"**

---

## 🎨 Dashboard Features

* Interactive landing page
* Page navigation using buttons
* Bookmarks for alternate dashboard views
* Field parameters for dynamic analysis
* Drill/filter interactions
* Time-based analysis
* Previous-year comparison
* KPI cards
* Interactive slicers
* Funnel analysis
* Customer segmentation

---

## 📁 Repository Structure

```text
E-Commerce-Growth-Customer-Analytics/
│
├── README.md
│
│
├── Documentation/
│   ├── Project_Report.pdf
│  
├── Screenshots/
│   ├── Landing_Page.png
│   ├── Sales_Revenue.png
│   ├── Customer_Behavior.png
│   ├── Conversion_Funnel.png
│   ├── Product_Category.png
│   └── Marketing_Traffic.png
│
└── Video/
    └── Dashboard_Walkthrough.mp4
```

---

## 🚀 Key Learning Outcomes

Through this project, I practiced:

* Building a relational Power BI data model
* Creating business-focused DAX measures
* Implementing time intelligence
* Designing interactive dashboards
* Creating customer segmentation
* Building conversion funnel analysis
* Using bookmarks and buttons
* Using field parameters
* Translating business questions into analytical visuals
* Presenting data as a coherent business story

---

## 📌 Project Outcome

The final dashboard provides a centralized analytical view of an e-commerce business, helping stakeholders understand **sales growth, customer behavior, conversion performance, product contribution, and marketing effectiveness**.

The main objective was to demonstrate not only Power BI visualization skills, but also the ability to approach an analytics problem from a **business perspective and convert raw data into decision-oriented insights**.

---

## 👩‍💻 Author

**Harshita Rajoria | 9654424376 **

**Focus:** Data Analytics | Business Analytics | Power BI | SQL | Python | AI
