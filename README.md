# Income Analysis by Gender and Education Level | Excel

**Data Analytics Portfolio Project**

## Project Overview

This project explores income patterns in a dataset of **99,569 records** using Microsoft Excel. The analysis focuses on descriptive statistics and comparisons of average income across gender and coded education levels. It demonstrates working with a large Excel dataset, summary formulas, Pivot Tables, and a PivotChart.

## Dataset

The workbook contains two worksheets:

- **`salary_data2`** — the main formatted and filterable data table, with statistical summaries.
- **`PIVOT`** — a Pivot Table and an embedded chart comparing average income by gender and education level.

The source data contains **five variables**:

| Column | Description |
| --- | --- |
| `ID` | Record identifier |
| `income` | Income amount |
| `age` | Age |
| `gender` | Gender category (`F` or `M`) |
| `education_level` | Education-level code (`0` to `3`) |

**Important:** The workbook does not specify the currency, income time period, or the meanings of education codes `0`–`3`. These values are therefore reported without adding unsupported interpretations.

## Project Objectives

1. Examine age and income using common descriptive statistics.
2. Compare average income between the two gender categories.
3. Compare average income across coded education levels within each gender category.
4. Present the comparisons through a Pivot Table and a chart.

## Excel Methods and Tools

- **Excel table and filtering:** Organized the main dataset as a structured, filterable table.
- **`AVERAGE`:** Calculated mean age and income.
- **`MEDIAN`:** Calculated median age and income.
- **`MAX` / `MIN`:** Identified the upper and lower values for age and income.
- **`SUBTOTAL`:** Counted numeric records in the ID column.
- **Pivot Table:** Grouped records by `gender` and `education_level`, using **Average of income** as the value calculation.
- **PivotChart:** Created a horizontal bar chart to compare average income across gender and education groups.

## Descriptive Statistics

| Metric | Age | Income |
| --- | ---: | ---: |
| Average | 32.98 | 40,417.47 |
| Median | 32 | 40,101.62 |
| Minimum | 18 | 15,000.00 |
| Maximum | 69 | 285,342.49 |

**Number of records:** 99,569.

## Average Income by Gender and Education Level

The Pivot Table provides the following results (rounded to two decimal places):

| Education level | F | M |
| --- | ---: | ---: |
| 0 | 33,873.17 | 34,478.43 |
| 1 | 39,273.64 | 39,466.32 |
| 2 | 40,668.18 | 40,411.51 |
| 3 | 44,855.32 | 44,863.85 |
| **Overall average by gender** | **40,410.87** | **40,424.06** |

## Key Findings

- **Average income increases from education code 0 to code 3** within both gender categories in this dataset.
- **Gender differences are relatively small at the overall-average level**: approximately 40,410.87 for `F` and 40,424.06 for `M`.
- At **education level 2**, the average income is higher for `F` than for `M`; this pattern is not the same at every education level.
- The overall income average (**40,417.47**) is slightly above its median (**40,101.62**).

These findings are **descriptive**, not evidence that education level or gender causes differences in income.

## Files

- [`1. projekat.xlsx`](./1.%20projekat.xlsx) — original Excel workbook containing the dataset, formulas, Pivot Table, and PivotChart.

**No screenshots are required:** the chart and analysis are embedded in the Excel workbook.

## Skills Demonstrated

`Microsoft Excel` · `Descriptive Statistics` · `Data Aggregation` · `Pivot Tables` · `PivotCharts` · `Comparative Analysis`

---

*Completed as part of the Coders Lab Data Analytics learning program.*
