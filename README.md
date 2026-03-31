<img width="1865" height="882" alt="image" src="https://github.com/user-attachments/assets/a7af0245-d2ef-4188-b376-287cd8db0a62" />

<img width="1905" height="876" alt="image" src="https://github.com/user-attachments/assets/def0bcd2-659c-4a10-8961-9edddb266b7e" />

<img width="1894" height="1307" alt="image" src="https://github.com/user-attachments/assets/38fef785-5c40-4e37-a914-afff9857af8f" />

🏥 MedCare Analytics — Healthcare Dashboard

A 3-page interactive hospital analytics dashboard built to demonstrate real-world Power BI skills across KPI reporting, department analysis, and doctor performance tracking.

Built with: Power BI Desktop · DAX · Power Query (M) · HTML/CSS prototype


📸 Dashboard Preview
Page 1 — OverviewPage 2 — DepartmentsPage 3 — DoctorsKPI cards, trend line, bed occupancy gaugeHeatmap, scatter plot, MoM trendsDoctor profiles, drill-through table

📊 Pages & Features
Page 1 — Hospital Overview

5 KPI cards with month-over-month % badges (Patient Count, Bed Nights, Average Age, DAP, IP%)
Patient count trend line with area fill and peak annotation
Bed occupancy rate gauge with 85% critical threshold marker
DAP by department — horizontal bar chart with conditional colouring
Gender split — donut chart (M / F / Other / Unknown)
Age distribution histogram — patient count by age bins

Page 2 — Department Performance

Department × Month heatmap — patient count matrix with conditional background formatting
IP% vs DAP bubble scatter — identifies high-pressure departments (top-right quadrant = resource risk)
Month-over-month multi-line trend — Oct 2023 → Jan 2024 across all departments
4 department-level KPI cards — top DAP dept, highest volume, avg IP%, total departments

Page 3 — Doctor Performance (Drill-through)

Featured doctor profile card — name, department, patient count, DAP, IP%, vs-dept comparison bar
Full doctor table — sortable by patient count, with DAP, IP%, profit % bar, and status indicator
Drill-through enabled — click any doctor in the table to load their individual profile


🗂️ Dataset
TableFieldsdoctorsdoctor, doctor_id, department, patient_count, DAP, IP%, gender, age_binscalendarDate, Day, DayNameShort, DayOfWeekNumber, IsWeekend, MonthName, MonthNumber, Quarter, Year

💡 Key Insights from the Data

Neurology has the highest DAP (11.2) — indicating longer patient stays and potentially higher resource consumption
Bed occupancy at 78% is within optimal range (60–85%) — no critical pressure currently
Patient count grew 8.3% MoM in January 2024, but bed nights dropped 10.8% — suggesting faster patient turnover
Dr. Deepak Iyer handles the most patients (231) with the highest DAP (3.73) in Neurology — a potential workload concern
The 55–60 age band is the largest patient cohort, relevant for resource and treatment planning
