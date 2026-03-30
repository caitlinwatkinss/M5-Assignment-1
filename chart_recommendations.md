# Chart Recommendations (Verified Data Only)

## 1) Cash and Receivables Trend (June vs December)
- **Chart type:** Clustered column
- **Fields:**
  - `as_of_date` (06/30/2023, 12/31/2023)
  - `Operating Cash`
  - `Accounts Receivable`
  - optional: `Reserve Cash`
- **Source fields:** Balance sheets from Packet 1 p.1 and Packet 2 p.1.

## 2) Monthly Operating Result Comparison (June vs December)
- **Chart type:** Waterfall or clustered columns
- **Fields:**
  - `month` (June 2023, December 2023)
  - `Total Revenue`
  - `Total Expense`
  - `Net Income (Loss)`
- **Source fields:** Monthly Revenues & Expenses statements (Packet 1 p.2; Packet 2 p.2).

## 3) 2023 YTD Actual vs Budget (Total)
- **Chart type:** Side-by-side bar chart
- **Fields:**
  - `metric` (Total Revenue, Total Expense, Net Income)
  - `YTD Actual`
  - `YTD Budget`
  - optional computed `Variance`
- **Source fields:** Comparative statement Packet 2 p.3.

## 4) Expense Over-Budget Drivers (YTD)
- **Chart type:** Sorted horizontal bar chart
- **Fields:**
  - `expense_category`
  - `YTD variance amount` (positive = over budget)
- **Suggested categories:** Irrigation Repairs, Water, Landscape Maintenance, Common Area Maintenance, Professional Services.
- **Source fields:** Comparative statement Packet 2 p.3.

## 5) December Expense Mix
- **Chart type:** Donut or stacked bar
- **Fields:**
  - `expense_category`
  - `december_amount`
- **Source fields:** December Revenues & Expenses statement Packet 2 p.2; optionally cross-check with GL p.27-p.28.
