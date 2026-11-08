# E-commerce Sales Dashboard \| Power BI

An interactive Power BI dashboard for exploring e-commerce sales,
quantity, profit, customer activity, product categories, payment
methods, and regional performance.

> **Project note:** This README describes the dashboard shown in the
> supplied screenshot. If you used or adapted an existing project,
> retain the original creator's attribution and clearly state which
> parts you personally changed or analysed. Do not claim another
> person's work as your own.

## Dashboard Preview

Add your Power BI dashboard screenshot to the repository, for example at
`images/dashboard.png`, then uncomment the image line below.

```{=html}
<!-- ![E-commerce Sales Dashboard](images/dashboard.png) -->
```
## Dashboard Overview

The report contains KPI cards and charts that help users explore sales
performance from different perspectives.

### Key metrics displayed

The screenshot shows these KPI cards:

-   **Sum of Amount:** 438K
-   **Sum of Quantity:** 5,615
-   **Sum of Profit:** 37K
-   **Sum of AOV:** 121K

These are the values displayed in the supplied dashboard screenshot.
Confirm the underlying measures, currency, units, and aggregation before
using them in a business report. In particular, average order value is
normally calculated as revenue divided by the number of orders, rather
than summed.

### Visualisations

-   **Amount by State:** compares sales amount across states, including
    Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi, and Rajasthan.
-   **Quantity by Category:** shows the share of quantity across
    categories such as Clothing, Electronics, and Furniture.
-   **Profit by Month:** compares monthly profit and highlights months
    with positive or negative profit.
-   **Amount by Customer:** compares sales amount across customers.
-   **Quantity by Payment Mode:** shows the distribution of quantity by
    payment method, including COD, UPI, debit card, credit card, and
    EMI.
-   **Profit by Sub-Category:** compares profit across sub-categories
    such as Printers, Bookcases, Saree, Accessories, and Tables.

### Interactive controls

The screenshot includes quarter selection buttons (Qtr 1 to Qtr 4) and a
dropdown filter. These controls allow the report viewer to filter the
displayed analysis.

## Tools

-   Microsoft Power BI Desktop
-   Power Query (if used for data preparation)
-   DAX (if used to create calculated measures)

Only list tools and techniques that you personally used or can explain.

## Data

The Power BI Fields pane in the screenshot shows two tables:

-   `Details`
-   `Orders`

Add the dataset source, licence or attribution, date range, row counts,
and column descriptions here. Do not describe the data as real company
data unless that is verified.

## How to View

1.  Install Microsoft Power BI Desktop.
2.  Clone or download this repository.
3.  Open the `.pbix` report file in Power BI Desktop.
4.  Use the quarter buttons and dropdown filter to explore the report.

If the `.pbix` file is not included in this repository, add it or
provide clear instructions for obtaining the report file.

## Analysis Questions

This dashboard can be used to investigate questions such as:

1.  Which states contribute the most sales amount?
2.  Which product category has the highest quantity?
3.  In which months is profit highest or lowest?
4.  Which customers contribute the most sales?
5.  Which payment methods are most commonly used?
6.  Which product sub-categories generate the most profit?

## What I Learned

Complete this section with your own experience after reviewing or
building the report. For example:

-   Creating and formatting visuals in Power BI.
-   Using slicers or buttons to filter a report.
-   Comparing sales and profit across different business dimensions.
-   Interpreting dashboard KPIs and identifying trends.

## Author and Attribution

-   **Repository owner:** \[Your name or GitHub username\]
-   **Project status:** \[Learning reference / adapted project /
    independently created project\]
-   **Original source (if applicable):** \[Add the original repository
    or creator's link\]

If this dashboard is adapted from another creator's work, preserve their
copyright and licence terms, provide attribution, and explain your own
contribution here.

## Future Improvements

-   Add a clear data-source and data-dictionary section.
-   Verify KPI calculations and format currency consistently.
-   Add a date-range slicer and year-over-year comparisons.
-   Include written business insights supported by the data.
-   Add screenshots and the Power BI `.pbix` file, subject to dataset
    and licence permissions.
