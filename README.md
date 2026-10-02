# Safaricom Commercial Performance Analysis (FY2022–FY2026)

**An end-to-end commercial performance analysis of Safaricom PLC using Microsoft Excel and Power BI.**

[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat\&logo=microsoftexcel\&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat\&logo=powerbi\&logoColor=black)](https://powerbi.microsoft.com/)
[![Data Analysis](https://img.shields.io/badge/Focus-Commercial%20Analytics-087C43?style=flat)](#business-problem)
[![Period](https://img.shields.io/badge/Period-FY2022--FY2026-1685D5?style=flat)](#project-overview)

## Executive Summary

This project analyses Safaricom PLC's commercial performance over five financial years, from FY2022 to FY2026, using publicly reported financial and customer performance data.

The analysis examines revenue growth, business-area contributions, revenue composition, long-term growth and selected customer performance indicators. The objective is to turn historical financial and operational figures into an interactive business intelligence dashboard that makes commercial trends easier to explore and interpret.

The project follows an analytical workflow encompassing data organisation, calculation, validation, visualisation and business interpretation. Microsoft Excel was used for data preparation and calculations, while Power BI was used to develop an interactive dashboard for exploring performance across financial years and business areas.

**The central business question is:**

*How has Safaricom's commercial performance evolved between FY2022 and FY2026, which business areas have contributed to revenue, and what do the reported customer indicators reveal about performance trends?*

---

## 1. Business Problem

Organisations need reliable ways to monitor financial performance, identify revenue drivers and understand changes in customer-related indicators. However, financial reports often present these measures across separate tables and reporting sections, making it difficult to examine them together.

This project addresses that analytical challenge by consolidating selected publicly reported Safaricom performance indicators into a structured dataset and interactive dashboard.

The analysis focuses on three principal revenue areas:

* **M-PESA**
* **Connectivity**
* **Fixed Service & IoT**

It also examines selected customer performance indicators, including active customers, average revenue per user (ARPU) and data-related metrics where reported in the source data.

The resulting dashboard provides a consolidated view of historical commercial performance, allowing users to explore trends, compare business areas and examine changes in selected KPIs.

### Business questions

The project addresses the following questions:

1. How has Safaricom's total revenue changed between FY2022 and FY2026?
2. How have the three selected business areas contributed to overall revenue?
3. Which business areas have experienced the greatest annualised revenue growth over the analysis period?
4. How has year-on-year revenue growth changed over time?
5. How has the composition of revenue evolved across financial years?
6. How have selected customer performance indicators changed over the same period?
7. What patterns emerge when revenue performance and customer indicators are examined together?

---

## 2. Project Objectives

The project was designed to:

* Analyse Safaricom's reported revenue across FY2022–FY2026.
* Compare the financial performance of M-PESA, Connectivity and Fixed Service & IoT.
* Calculate year-on-year (YoY) revenue growth.
* Calculate revenue mix to examine the relative contribution of each business area.
* Calculate compound annual growth rate (CAGR) to assess longer-term revenue growth.
* Examine selected customer performance indicators over time.
* Develop an interactive Power BI dashboard for business performance monitoring.
* Present analytical findings in a format accessible to business stakeholders.

---

## 3. Project Scope

| Component         | Description                                                              |
| ----------------- | ------------------------------------------------------------------------ |
| Organisation      | Safaricom PLC                                                            |
| Analysis period   | FY2022–FY2026                                                            |
| Analysis type     | Historical commercial and business performance analysis                  |
| Revenue coverage  | M-PESA, Connectivity, Fixed Service & IoT                                |
| Customer analysis | Selected publicly reported customer and usage KPIs                       |
| Financial unit    | KSh billions, unless otherwise stated                                    |
| Primary tools     | Microsoft Excel and Power BI                                             |
| Dashboard         | Interactive, with financial-year, business-area and customer-KPI filters |
| Intended audience | Business analysts, commercial teams, management and other stakeholders   |

The project focuses on the indicators included in the prepared dataset.

---

## 4. Tools and Technologies

| Tool               | Application                                                                          |
| ------------------ | ------------------------------------------------------------------------------------ |
| Microsoft Excel    | Data organisation, calculations, validation and analytical preparation               |
| Microsoft Power BI | Interactive dashboard development, data modelling and visualisation                  |
| DAX                | Measures and context-sensitive calculations in Power BI                              |
| GitHub             | Project versioning, documentation and portfolio presentation                         |
| Generative AI      | Formula explanations, troubleshooting and documentation assistance |


---

## 5. Data Sources

The analysis 
The source material consists of the company's published annual financial results and associated results booklets. The selected figures were organised into structured tables for analysis.

### Data categories

| Data category        | Description                                           |
| -------------------- | ----------------------------------------------------- |
| Revenue              | Revenue figures for the three selected business areas |
| Revenue growth       | Annual changes in revenue                             |
| Revenue composition  | Each business area's contribution to total revenue    |
| Customer performance | Selected customer, usage and ARPU indicators          |
| Long-term growth     | CAGR calculated over FY2022–FY2026                    |

**Source organisation:** Safaricom PLC
**Source type:** Publicly available corporate financial and performance reports
**Reporting period:** FY2022–FY2026

The original reports should be consulted when interpreting individual metrics, particularly where reporting definitions or segment classifications may have changed.

---

## 6. Methodology

The project followed a structured analytical workflow.

### Stage 1: Data collection

Selected revenue and customer performance indicators were obtained from Safaricom's published financial results and supporting reports.

The figures were organised by financial year, business area and metric to support consistent comparisons.

### Stage 2: Data organisation and preparation

The selected figures were structured into separate analytical tables in Excel, including:

* Revenue
* Connectivity
* M-PESA
* Fixed Service & IoT
* Customer KPIs
* Source Log
* CAGR

The tables were organised to distinguish financial measures from customer indicators and retain the relevant units and reporting periods.

### Stage 3: Data validation and calculations

The prepared figures were used to calculate key performance measures.

**Year-on-year revenue growth**

Measures the percentage change in revenue relative to the previous financial year.

$$
\text{YoY Growth} =
\frac{\text{Current Revenue}-\text{Previous Revenue}}
{\text{Previous Revenue}}\times100
$$

**Revenue mix**

Measures the percentage of total revenue contributed by each business area.

$$
\text{Revenue Mix} =
\frac{\text{Business Area Revenue}}
{\text{Total Revenue}}\times100
$$

**Compound annual growth rate (CAGR)**

Measures the annualised growth rate between the beginning and ending values over the four-year interval.

$$
\text{CAGR} =
\left(\frac{\text{Ending Value}}{\text{Beginning Value}}\right)^{1/4}-1
$$

The calculations provide complementary perspectives: YoY growth captures annual changes, revenue mix measures relative contribution, and CAGR summarises longer-term growth.

### Stage 4: Exploratory analysis

The prepared data was examined to identify:

* Changes in total revenue over time.
* Differences in the revenue trajectories of the three business areas.
* Changes in the relative contribution of each area.
* Differences between annual growth and long-term growth.
* Trends in selected customer performance indicators.

### Stage 5: Dashboard development

Power BI was used to transform the prepared data into an interactive dashboard.

The dashboard combines financial performance, revenue composition and customer performance visualisations. DAX measures support key calculations and selected filter behaviours.

### Stage 6: Interpretation and reporting

The resulting dashboard and calculations were used to identify historical patterns and develop business-oriented observations.

The findings are descriptive. They explain patterns visible in the historical data rather than establishing causal relationships or predicting future performance.

---

## 7. Key Performance Indicators

The project uses several financial and customer-related measures.

| KPI                        | Definition                                                 | Analytical purpose                                                 |
| -------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------ |
| Annual Revenue             | Total revenue for the selected financial year              | Monitors overall commercial performance                            |
| Total Revenue Growth (YoY) | Percentage change in consolidated annual revenue           | Tracks annual revenue growth                                       |
| M-PESA Revenue             | Reported revenue from M-PESA                               | Examines the performance of the mobile financial services business |
| Revenue Mix                | Business-area revenue as a proportion of total revenue     | Measures revenue composition                                       |
| Revenue CAGR               | Annualised revenue growth over FY2022–FY2026               | Compares longer-term growth across business areas                  |
| Active Customers           | Reported active-customer count                             | Monitors customer scale                                            |
| ARPU                       | Average revenue per user, according to the reported metric | Examines average revenue indicators                                |
| Data Usage                 | Reported data consumption indicator                        | Examines customer data usage                                       |
| Data Rate                  | Reported rate per MB                                       | Tracks the reported data pricing indicator                         |

Customer KPIs retain their reported units. They should not be directly compared with one another unless their definitions and measurement units permit a meaningful comparison.

---

## 8. Power BI Dashboard

The dashboard is designed to provide a consolidated view of Safaricom's commercial performance.

### Dashboard preview

![Safaricom Commercial Performance Dashboard](dashboard/dashboard-overview.png)

*Replace the image path above if your final screenshot has a different filename or location.*

### Dashboard components

| Visual                              | Purpose                                                            |
| ----------------------------------- | ------------------------------------------------------------------ |
| Year slicer                         | Filters the analysis by financial year                             |
| Business Area slicer                | Allows users to focus on a specific revenue area                   |
| Customer KPI slicer                 | Selects the customer performance metric to examine                 |
| Annual Revenue card                 | Displays revenue for the selected financial year                   |
| Total Revenue Growth card           | Displays consolidated YoY revenue growth                           |
| M-PESA Revenue card                 | Displays M-PESA revenue for the selected context                   |
| One-Month Active Customers card     | Displays the active-customer count for the relevant financial year |
| Revenue Trend by Business Area      | Compares revenue trajectories across the three business areas      |
| Revenue Mix by Business Area        | Visualises the composition of revenue                              |
| Revenue and Growth by Business Area | Combines revenue columns with a YoY growth line                    |
| Customer KPI Trend by Year          | Displays the selected customer metric over time                    |
| Revenue CAGR chart                  | Compares annualised revenue growth across the three business areas |
| Key Findings                        | Summarises selected business observations                          |
| Analysis Scope                      | Explains the purpose and coverage of the dashboard                 |

### Interactive functionality

The dashboard includes three primary filters:

* **Financial year:** Allows users to examine performance in individual reporting years.
* **Business area:** Allows comparisons to be focused on M-PESA, Connectivity or Fixed Service & IoT.
* **Customer KPI:** Allows users to switch between the available customer performance metrics.

The KPI cards and charts respond to the relevant filters according to their configured interactions. Some measures, such as consolidated revenue growth and the active-customer card, are designed to preserve their intended meaning when other filters change.

The dashboard is intended for interactive exploration rather than simply presenting static charts.

---

## 9. Key Findings

The following observations are based on the figures included in the prepared dataset.

### 9.1 Revenue composition

In FY2026, Connectivity contributed approximately **49.37%** of total revenue, while M-PESA contributed approximately **45.59%**. Fixed Service & IoT accounted for approximately **5.04%**.

Together, Connectivity and M-PESA represented approximately **95%** of the revenue covered by these three business areas.

This demonstrates the relative importance of these two areas within the selected revenue categories.

### 9.2 M-PESA revenue growth

M-PESA revenue increased from approximately **KSh107.69 billion in FY2022** to **KSh182.73 billion in FY2026**.

This represents substantial growth over the analysis period and provides a basis for examining the evolution of M-PESA's contribution to overall revenue.

### 9.3 Connectivity revenue

Connectivity revenue increased from approximately **KSh161.70 billion in FY2022** to **KSh197.87 billion in FY2026**.

Connectivity remained a major component of the selected revenue categories throughout the analysis period.

### 9.4 Fixed Service & IoT

Fixed Service & IoT revenue increased from approximately **KSh11.72 billion in FY2022** to **KSh20.20 billion in FY2026**.

Although its revenue contribution is smaller than those of Connectivity and M-PESA, the increase in its reported revenue makes it relevant to the longer-term growth comparison.

### 9.5 Different measures reveal different aspects of performance

Revenue contribution, annual growth and CAGR answer different business questions.

A business area with a smaller revenue base may have a substantial growth rate without contributing as much revenue as a larger business area. Considering these indicators together provides a more complete description of commercial performance.

*The findings above describe the selected historical dataset. They should not be interpreted as explanations of the causes of growth or as forecasts of future performance.*

---

## 10. Business Value

The dashboard demonstrates how publicly reported financial and customer data can be structured into a more accessible performance-monitoring resource.

Its potential business applications include:

* **Performance monitoring:** Reviewing historical revenue and customer KPI trends in one place.
* **Revenue analysis:** Comparing the contribution of different business areas.
* **Growth assessment:** Distinguishing annual growth from longer-term growth.
* **Management reporting:** Presenting selected commercial indicators through a consolidated dashboard.
* **Analytical exploration:** Allowing stakeholders to investigate performance by year, business area and customer metric.
* **Evidence-based discussions:** Providing a consistent historical view to support further commercial investigation.

The dashboard is a historical analytical resource, not a replacement for Safaricom's internal management reporting systems or financial statements.

---

## 11. Limitations and Assumptions

The following limitations should be considered when interpreting the results.

1. **Publicly reported data:** The project uses publicly available information rather than Safaricom's internal operational or transaction-level datasets.

2. **Historical analysis:** The dashboard examines FY2022–FY2026. It is not designed to forecast future performance.

3. **Reporting definitions:** Changes in reporting classifications, metric definitions or segment composition may affect comparisons across financial years.

4. **Rounded figures:** Some published values may be rounded. Calculations based on rounded inputs can differ slightly from figures calculated using unrounded source data.

5. **Selected business areas:** The analysis focuses on the three revenue areas included in the prepared dataset. It should not automatically be interpreted as a complete representation of every Safaricom business activity.

6. **Customer metrics:** Customer indicators have different units and definitions. Their trends should be interpreted according to the original reporting methodology.

7. **No causal inference:** Historical changes in revenue and customer metrics do not, by themselves, establish why those changes occurred.

8. **No predictive modelling:** The project does not include statistical forecasting, machine learning or causal modelling.

These limitations define the appropriate scope of the conclusions and identify areas where additional data or analysis would be needed.

---

## 12. Project Structure

The repository is organised to separate source data, prepared data, analysis files, visual outputs and documentation.

```text
safaricom-commercial-performance/
│
├── ai/
│   └── ai-worklog.md
│
├── dashboard/
│   └── dashboard-overview.png
│
├── data/
│   ├── raw/
│   ├── cleaned/
│   └── sourcenotes/
│
├── excel/
│   └── Safaricom_Sales_Performance_Analysis.xlsx
│
├── power-bi/
│   └── Safaricom_Sales_Performance_Analysis.pbix
│
└── README.md
```

**Folder descriptions**

| Folder              | Contents                                                                       |
| ------------------- | ------------------------------------------------------------------------------ |
| `ai/`               | AI assistance worklog and relevant disclosure                                  |
| `dashboard/`        | Exported Power BI dashboard screenshots                                        |
| `data/raw/`         | Original source data and supporting reports, where redistribution is permitted |
| `data/cleaned/`     | Prepared datasets used in the analysis                                         |
| `data/sourcenotes/` | Source references, metric definitions and data notes                           |
| `excel/`            | Excel workbook containing the prepared data and calculations                   |
| `power-bi/`         | Power BI report file                                                           |
| Root                | Project overview and documentation                                             |

Update the filenames above to match the actual files in the repository. Include only files that are present.

---

## 13. Reproducibility

The project can be examined using the included Excel workbook and Power BI report.

To review the analysis:

1. Clone or download the repository.
2. Review the README and source notes to understand the data coverage and reporting period.
3. Open the Excel workbook to inspect the prepared tables and calculations.
4. Open the Power BI file using Power BI Desktop.
5. Interact with the financial-year, business-area and customer-KPI slicers to examine the reported performance trends.

The Power BI report may require the original workbook or a refresh of its data sources if the local file paths differ from those used during development.

---

## 14. AI Assistance and Project Attribution

Generative AI was used as a learning and development aid during this project. Assistance included:

* Explaining Excel calculations and analytical concepts.
* Providing guidance on Power BI visuals, measures and formatting.
* Troubleshooting dashboard behaviour and filter interactions.
* Structuring the analytical workflow.
* Supporting the development and refinement of project documentation.
* Helping formulate business questions and interpret analytical outputs.

The project author reviewed the calculations, data presentation and final dashboard against the prepared dataset and available source information.

AI assistance is disclosed to provide transparency about the development process. The project should be understood as an AI-assisted analytical learning project rather than work completed entirely without external assistance.

---

## 15. Future Improvements

Potential extensions include:

* Automating data extraction and preparation to reduce manual updates.
* Introducing Python for repeatable data cleaning, validation and analysis.
* Using SQL to manage and query a more extensive commercial dataset.
* Adding additional financial indicators where suitable source data is available.
* Examining relationships between customer performance and revenue trends.
* Developing automated data-quality checks and a repeatable refresh process.
* Introducing forecasting only after sufficient historical data and an appropriate modelling approach are available.

These are potential future enhancements and are not capabilities of the current version.

---

## 16. Conclusion

This project demonstrates an end-to-end application of Excel and Power BI to a real-world commercial performance analysis using publicly reported company data.

By combining revenue trends, revenue composition, annual and long-term growth measures, and selected customer indicators, the project provides a structured view of Safaricom's historical performance between FY2022 and FY2026.

The interactive dashboard brings these indicators together in a format suitable for business exploration and management-oriented reporting. It also demonstrates the use of analytical calculations, data visualisation, KPI design and transparent documentation to turn financial data into interpretable business information.

**Project focus:** Commercial analytics · Financial performance · Business intelligence · KPI analysis · Data visualisation

**Author:** Martin Waiguru
**Tools:** Microsoft Excel · Power BI · DAX · GitHub

