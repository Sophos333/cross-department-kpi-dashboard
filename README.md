# 📊 Cross-Department KPI Dashboard

A business-facing dashboard designed for leadership teams to track department performance in real time.

An interactive Power BI dashboard built to track key performance indicators across **Finance**, **HR**, and **Operations** for **January–February 2024**. Designed to showcase strong analytics, clean design, and interactivity for portfolio and recruiter presentations.

---

## 🔍 Features

- **KPI Summary Cards** – Highlights key metrics like Headcount, Turnover Rate, Hires, Efficiency, and Downtime Hours.
- **Budget vs Actual Chart** – Visual comparison by department.
- **Monthly Budget Trend** – Line chart tracking monthly fluctuations.
- **Variance % Bar Chart** – Includes conditional formatting to highlight negative values in red.
- **Interactive Slicer** – Department dropdown to filter the entire dashboard.

---

## 🧠 DAX Measures

Custom DAX calculations used to drive interactivity and visuals:

```DAX
Variance = [Actual] - [Budget]

Variance % = DIVIDE([Variance], [Budget], 0)
``` 

These measures enable performance comparisons and conditional formatting.

## 🛠 Tools Used
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Excel (mock data source)

## 🎨 Design Notes
- Typography and color theme aligned with personal portfolio (Segoe UI, #2980b9 blue accent).
- Visual alignment and spacing optimized for presentation.
- Slicer converted to dropdown for space efficiency.

📸 Screenshots
✅ Full Dashboard View

![Overview](https://github.com/user-attachments/assets/5c506848-5a1d-4fef-9cbb-6e9ee9ab1801)

✅ Full HR View

![HR](https://github.com/user-attachments/assets/e6fd55f1-8ff9-4338-a431-8cf73dda630c)

✅ Full Finance View

![Finance](https://github.com/user-attachments/assets/eb81ecdd-aaa1-40c6-ac6d-32ebcdf62552)


🚀 How to Use
Download or clone the repo.

Open CrossDept_KPI_Dashboard.pbix in Power BI Desktop.

Use the Department dropdown slicer to filter the dashboard.

Hover over visuals for tooltips.

Export as PDF or publish to Power BI Service.

📦 Latest Update (May 2025)
✅ Added full Power BI project file: CrossDept_KPI_Dashboard.pbix

Now anyone can inspect visuals, slicers, and DAX measures directly inside Power BI Desktop.

🤝 Let's Connect
Interested in collaborating or hiring?

LinkedIn - https://www.linkedin.com/in/yashuasspear-oscar-holguin-silva/

Portfolio - https://sophos333.github.io/sophos-chatbot-portfolio/

📂 Project Structure
📁 root
│   README.md
│   CrossDept_KPI_Dashboard.pbix
📁 screenshots
    ├── overview_dashboard.png
    ├── hr_view.png
    └── finance_view.png

Thanks for checking out the project! 🚀



