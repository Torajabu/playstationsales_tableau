## **📊 Worksheets **

1. **console**
2. **date sales**
3. **genre by metacritic**
4. **genre rating**
5. **genre sales**
6. **publisher by total sale**
7. **reg_sales**
8. **update sales**
9. **genre rating**

---

## **📈 Dashboards**

The combined dashboards within the project:

1. **Story 1**
2. **pub_cons_dash**
3. **sales_dash**

---

## **🗄️ Data Sources **

CSV file is loaded as a **federated connection** (normal for Tableau Desktop).

---
# 🎮 PlayStation Sales & Metadata — Tableau Visualization Project

This project analyzes **PlayStation 3, PlayStation 4, and PlayStation 5** game performance using a curated dataset of sales and metadata.
The goal is to identify patterns in sales, ratings, genres, publishers, and regional performance using **interactive Tableau dashboards**.

---

## 📁 Repository Contents

| File                                                          | Description                                                                    |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **PlayStation Sales and Metadata (PS3PS4PS5) (Oct 2025).csv** | Main dataset containing game-level sales, release info, ratings, and metadata. |
| **games.twb**                                                 | Tableau workbook containing worksheets, dashboards, and stories.               |
| **/screenshots**                                              | PNG images showing dashboards and visual insights.                             |

---

## 📊 Tableau Workbook Structure

### **Worksheets**

The workbook includes multiple analyses:

* **console** – Platform-level comparison across PS3, PS4, PS5
* **date sales** – Trend of sales over time
* **genre by metacritic** – Genre-wise critic score breakdown
* **genre rating** – Rating distribution per game genre
* **genre sales** – Total sales per genre
* **publisher by total sale** – Publisher-wise sales comparison
* **reg_sales** – Regional sales analysis
* **update sales** – Updated sales trend sheet
* *(duplicate)* **genre rating**

---

### **Dashboards**

* **sales_dash** – Combined visualization of sales trends, genres, and regions
* **pub_cons_dash** – Publishers vs console performance dashboard
* **Story 1** – Story-format walkthrough of insights

---

## 🧵 Dataset Overview

The dataset includes information such as:

* Game title
* Platform (PS3 / PS4 / PS5)
* Genre
* Publisher
* Global & regional sales
* Release year
* Metacritic critic score
* User rating
* Game metadata fields

Use cases:

* Trend analysis
* Genre performance
* Publisher comparison
* Critic score impact on sales
* Region-wise sales visualization

---

## 📈 Insights & Questions Explored

The dashboards aim to answer:

* Which PlayStation platform had the strongest game sales period?
* How do genres differ in global and regional performance?
* Do higher Metacritic ratings correlate with higher sales?
* Which publishers dominate PlayStation platforms?
* How do sales evolve across years for PS3, PS4, and PS5?

---

## 🚀 How to Use

1. Download or clone the repository:

   ```bash
   git clone https://github.com/Torajabu/playstationsales_tableau
   ```
2. Open **games.twb** in Tableau Desktop.
3. Place the CSV file in the same directory (Tableau will auto-link).
4. Explore dashboards & worksheets interactively.

---

## 🖼️ Dashboards (Screenshots)

Screenshots are included in the repository under `/screenshots/` showing:

* Sales dashboard
* Publisher + console dashboard
* Genre and rating charts
* Story view
# Dashboards
![dashboard](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20095929.png)
![filter applied](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20100002.png)
![sales_dashboard](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20095920.png)
## Worksheet
![worksheet](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20095937.png)
## Story
![story](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20103431.png)
![story](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20103425.png)
![story](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20103420.png)
![story](https://github.com/Torajabu/playstationsales_tableau/blob/main/Screenshot%202025-11-06%20103415.png)

---

## 🛠️ Tools Used

* **Tableau Desktop**
* **CSV dataset (cleaned and structured)**
* **GitHub for version control**

---

## 📌 Future Improvements

* Add preprocessing script (Python/SQL)
* Add a data dictionary for all columns
* Publish Tableau Public version
* Include summary insights or PDF report

---

## 👤 Author

**Rajabudeen Ahamed (Rajab)**

* GitHub: [https://github.com/Torajabu](https://github.com/Torajabu)
* Kaggle: [https://kaggle.com/rajabudeenahamedm](https://kaggle.com/rajabudeenahamedm)
