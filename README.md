# Inventory Performance Dashboard | Excel Portfolio

Excel-based inventory and sales reporting using **365 records** across 12 month labels, four categories, seven products and five suppliers.

## Business problem
Inventory teams need a consistent way to compare revenue, profit, costs and product stock movements across months, categories and suppliers. This workbook combines source records, pivot summaries and an inventory dashboard to support repeatable monitoring.

## Dashboard KPIs
| Measure | Result | Definition |
|---|---:|---|
| Revenue | 4,536,842 | Sum of Revenue |
| Profit | 2,949,228 | Sum of Profit |
| Expenses | 1,587,614 | Sum of Expenses |
| Units sold (dashboard label) | 15,040 | Sum of Stock Out |
| Stock in | 25,834 | Sum of Stock In |
| Profit margin | 65.01% | Profit / Revenue |

*Currency is unspecified in the workbook.*

## Dataset terminology
| Field | Definition |
|---|---|
| `Month` | Three-letter reporting month; the workbook does not specify a calendar year. |
| `Category` | Merchandise grouping: Clothing, Electronics, Footwear or Accessories. |
| `Product` | Product name associated with a sales and stock record. |
| `Supplier` | Supplier name assigned to the record; supplier contracts and costs are not provided. |
| `Revenue` | Recorded sales value for the row; currency unspecified. |
| `Profit` | Recorded profit; in the dataset it equals Revenue minus Expenses. |
| `Expenses` | Recorded costs associated with the row; no detailed cost breakdown supplied. |
| `Stock In` | Units received or added to inventory in the record. |
| `Stock Out` | Units removed from inventory; the dashboard labels the sum Units Sold, though other stock movements are not separately identified. |

## Workbook structure
- **Data:** 365 records with nine source fields.
- **Pivot:** monthly, category and product summary tables.
- **Dashboard:** headline metrics and visual reporting.

## Analysis opportunities
- Compare revenue and profit by month and category.
- Identify high-performing products and supplier-linked revenue.
- Examine stock received and stock issued by product.
- Compare expense burden and profitability across segments.

## Data quality and interpretation
- No missing values were observed in the source records.
- Revenue equals Profit plus Expenses in the records.
- The source does not specify year, currency, transaction identifiers, opening inventory or adjustment reasons.
- `Stock Out` is labelled `Units Sold` on the dashboard; this does not independently establish that all stock-out movements were sales.
- The difference between Stock In and Stock Out is **not** a validated closing inventory balance.
- The workbook is macro-enabled (`.xlsm`); review embedded macros and confirm redistribution permission before publishing.

## Repository files
- `Inventory Dashboard.xlsm` — original Excel dashboard
- `Inventory_Project_Documentation.pdf` — problem statement, glossary and KPI documentation
- `README.md` — repository overview

## Portfolio description
Developed an Excel inventory performance dashboard using 365 records to report revenue, profitability, expenses and product stock movement. Organized monthly, category and product analysis using pivot summaries and dashboard KPIs.

## Dashboard Preview

### 1. Summary Dashboard

##[Bank Loan Summary Dashboard]<img width="999" height="473" alt="Inventory_Performance_dashboard" src="https://github.com/user-attachments/assets/f197d857-f78f-4f32-a245-b6a9865eadff" />

