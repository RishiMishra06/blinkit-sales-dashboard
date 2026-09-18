# Blinkit Sales Dashboard (Power BI)

This is a Power BI dashboard I built to practice data analysis and dashboard design — analyzing retail sales data across different outlet types, product categories, and locations, styled around the Blinkit grocery delivery theme.



## About this project

I wanted to get hands-on with Power BI beyond just following along with tutorials, so I picked up the Big Mart Sales dataset and rebuilt it as a "Blinkit" themed dashboard — from cleaning the data in Excel to building out the visuals, DAX measures, and the whole layout in Power BI. It covers 8,523 transactions and looks at things like which outlet types perform best, how fat content and item category affect sales, and how location tier plays a role.

## Tools I used

- Power BI Desktop (visuals, data modeling, DAX)
- Excel (source data / cleanup)

## Quick numbers

| Metric | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sale | $141 |
| Total Transactions | 8,523 |
| Average Rating | 3.92 / 5 |

## What I found

- **Supermarket Type1 outlets bring in the most revenue** — $787.55K, which is about 65% of total sales, even though the average sale value is basically the same (~$140–142) across every outlet type. So it's really about how many stores/transactions there are, not how much each one sells per visit.
- **Fruits & Vegetables and Snack Foods** are the best-selling categories, while Seafood, Breakfast, and Starchy Foods barely move.
- **Low Fat products make up 64.6%** of sales vs 35.4% for Regular — this pattern holds across all city tiers.
- **Tier 3 cities actually generate the most sales** ($472K), ahead of Tier 2 and Tier 1 — wasn't expecting that going in.
- **Medium-sized outlets handle the most transactions** (42%), followed by Small (37%) and High (21%).
- I checked if Item Visibility, Weight, or Rating had any real relationship with Sales — turns out none of them do (correlation close to 0). Outlet type/size matters way more than product-level stuff.
- The sales-by-year chart looks spiky (like the jump to $205K around 2018), but that's mostly because more outlets opened that year, not because sales suddenly grew.

## Dataset

Used the Big Mart Sales dataset, re-themed for this project. It has:
- Item details: type, fat content, weight, visibility
- Outlet details: establishment year, size, location tier, outlet type
- Sales and customer rating per transaction

## What's in this repo

```
├── Blinkit_Dashboard.pbix     # the Power BI file
├── Blinkit_Excel_Data.xlsx    # dataset
├── Blinkit_Dashboard.pdf      # exported view of the dashboard
├── Blinkit_Dashboard_1.png    # screenshot
├── Blinkit_Dashboard_2.png    # screenshot (home page)
└── README.md
```

## How to open it

1. Download `Blinkit_Dashboard.pbix`
2. Open it in [Power BI Desktop](https://www.microsoft.com/power-bi/desktop) — it's free
3. Play around with the filters and slicers on the dashboard

## Author

Rishi Mishra
