# US National Debt Tracker — Excel Analysis

## Overview
This project analyzes historical US public debt data (1993-2023) to answer three core business questions, framed as a scenario for a debt agency advising the US government on public and intragovernmental debt trends. The project demonstrates data cleaning, pivot table analysis, and forecasting in Excel.

## Scenario
*"You were hired by a small debt agency in Washington DC that specializes in analyzing and forecasting public and private debt. The US Government has requested an analysis of their public and governmental debt."*

The analysis answers three questions:
1. What was the yearly debt percentage increase for each year compared to the previous year?
2. Which months historically have seen the highest/lowest increases in total debt?
3. What is the projected growth of the publicly held debt in the next few years?

## Dataset
Daily US Treasury debt records (1993-2023) with three categories:
- **Debt Held by the Public** — debt held by individuals, corporations, foreign governments, and other entities outside the US government
- **Intragovernmental Holdings** — debt held by other US government agencies
- **Total Public Debt Outstanding** — the sum of the above two categories

## Tools Used
- **Excel** — data cleaning, pivot tables, FORECAST function, year-over-year percentage calculations, charts

## Workbook Structure
- **Scenario** — project brief and data dictionary
- **Raw Data** — original unprocessed dataset
- **Cleaned Data** — cleaned dataset ready for analysis
- **Question 1** — year-over-year percentage increase calculations for all three debt categories (1994-2022)
- **Question 2** — pivot table analyzing average total debt by month to identify seasonal patterns
- **Question 3** — forecast of publicly held debt growth using Excel's FORECAST function

## Key Insights
- **2008 and 2020 stand out as crisis years**: Debt Held by the Public jumped 24.5% in 2008 (financial crisis) and 26.0% in 2020 (COVID-19 pandemic) — by far the two largest single-year increases in the dataset, both roughly 4-5x the typical annual increase of 5-10%.
- **Recent growth has slowed but remains elevated**: Total debt growth was 6.1% in 2022 and 6.7% in 2021, down from the 19.6% spike in 2020 but still above the pre-2008 historical norm of roughly 5-9% per year.
- **Seasonal pattern in debt growth**: the analysis found that the highest average debt increases historically occur in January, February, November, and December, while April, May, June, and July see the lowest increases — likely tied to the US government's fiscal calendar (tax season inflows in spring vs. year-end spending).
- **Long-term trend**: comparing early years (1994-2000, mostly under 3% annual growth) to recent years (2018-2022, averaging 5-9%) shows debt growth has structurally accelerated over the three-decade period, even excluding the 2008 and 2020 outlier years.
- **Forecast (2023-2027)**: using Excel's FORECAST function on historical year-end values, Debt Held by the Public is projected to grow from roughly $24.6 trillion (2022) to about $33.0 trillion by 2027 — an increase of roughly $8.4 trillion, or about 35%, over five years. This implies an average annual growth rate of roughly 6%, broadly consistent with the post-2008 "new normal" rather than a return to pre-2008 growth rates.

## How to Use
Open `US_Debt_Tracker_Project.xlsx` in Excel. Navigate through the sheet tabs (Scenario → Raw Data → Cleaned Data → Question 1/2/3) to follow the full analysis workflow from raw data to final answers.
