# 📊 Digital Payment Systems Analysis in India

## Overview

This project looks at the growth of digital payments in India using data from the Reserve Bank of India (RBI) and UPI transaction data.

The main aim was to understand how different digital payment systems have changed over time and how UPI compares with other major payment methods such as NEFT, RTGS, IMPS and AEPS.

The analysis was done using Python and Pandas, with a focus on cleaning the data, finding trends, comparing payment systems and turning the numbers into useful insights.

---

## 🎯 What I Wanted to Find

The project focuses on a few main questions:

* How have digital payment transactions changed over time?
* How does UPI compare with NEFT, RTGS, IMPS and AEPS?
* Which payment systems are seeing faster growth?
* What share of digital payment activity comes from each system?
* Are there noticeable differences in transaction activity across weekdays?
* What does the overall trend tell us about digital payment adoption in India?

---

## 🛠️ Tools Used

* **Python**
* **Pandas** – data cleaning, transformation and analysis
* **NumPy** – numerical calculations
* **Matplotlib** – data visualization
* **Jupyter Notebook**

---

## 📂 Datasets

The project uses two datasets:

### 1. RBI Daily Digital Payments Data

This dataset contains daily information on different payment systems in India.

The analysis includes:

* UPI
* NEFT
* RTGS
* IMPS
* AEPS

### 2. UPI Monthly Transactions Data

A separate UPI dataset was used to look more closely at monthly UPI transaction trends, including transaction volume and value.

---

## 🔎 Analysis Performed

### Data Cleaning

Before starting the analysis, the datasets were cleaned and prepared for use.

This included:

* Removing unnecessary columns
* Standardizing column names
* Converting dates into the correct format
* Converting numerical columns to appropriate data types
* Checking and handling missing values
* Creating useful date-related columns such as year and month

---

### 📅 Time-Series Analysis

The RBI data contains daily observations, so the data was also aggregated to a monthly level to make longer-term trends easier to understand.

Monthly trends were used to compare the movement of different payment systems over time.

---

### 📈 Growth Analysis

Growth rates were calculated to understand how transaction activity changed from one period to another.

This was particularly useful for looking at the growth of UPI and comparing it with other payment systems.

---

### 📊 Payment System Comparison

The major payment systems were compared based on their transaction activity.

The analysis looked at:

* UPI
* NEFT
* RTGS
* IMPS
* AEPS

This helped show how the different systems contribute to India's digital payment ecosystem and how their usage has changed over time.

---

### 🥧 Market Share Analysis

Market share was calculated to understand the relative contribution of different payment systems.

This makes it easier to see the difference between systems with very high transaction volumes and systems that represent a smaller portion of overall digital payment activity.

---

### 📆 Weekday Analysis

The daily RBI data was also used to compare transaction activity across different days of the week.

This was done to check whether payment activity changes depending on the day.

---

### 📉 Rolling Average

A 7-day rolling average was calculated for UPI transactions.

The purpose of this was to smooth out the day-to-day fluctuations and make the underlying trend easier to see.

---

### 🔗 Combining RBI and UPI Data

The RBI analysis and the separate UPI dataset were also brought together for comparison.

This allowed the project to look at UPI both as part of the wider digital payment ecosystem and separately through its monthly transaction data.

---

## 💡 Key Insights

Some of the main findings from the analysis were:

* **UPI has become the dominant payment system by transaction volume** among the systems examined.
* Traditional digital payment systems such as **NEFT and RTGS show a different growth pattern compared with UPI**.
* **UPI transaction activity has increased significantly over the period covered by the data.**
* Digital payment activity is not evenly distributed across all days of the week, with **higher activity observed on weekdays**.
* Looking at a rolling average makes the overall UPI trend easier to identify by reducing daily fluctuations.
* The comparison between payment systems shows how the role of different digital payment methods has changed as UPI adoption has grown.

---

## 📓 Notebooks

The project is divided into two notebooks:

### `rbi_payment_analysis.ipynb`

Contains the analysis of RBI's daily digital payment data, including:

* Data cleaning
* Time-series analysis
* Payment system comparison
* Growth analysis
* Market share
* Yearly analysis
* Weekday analysis
* UPI rolling average

### `upi_transaction_analysis.ipynb`

Contains the dedicated UPI analysis, including:

* Data cleaning
* Monthly transaction analysis
* Transaction volume trends
* Transaction value trends
* Growth calculations

---

## Conclusion

The analysis shows the rapid growth of digital payments in India and, in particular, the increasing importance of UPI in terms of transaction volume.

At the same time, the comparison with NEFT, RTGS, IMPS and AEPS shows that each payment system has a different pattern of usage and growth.

Overall, this project was an exercise in taking raw payment data, cleaning it, analyzing it from different angles and presenting the results in a way that is easier to understand.
