# Acme Solar Technologies
## Three-Statement Financial Model and Scenario Analysis

**Independent portfolio project by Ignacio Said**

An integrated financial model examining how policy changes, material-cost inflation and temporary demand weakness affect a fictional solar-energy company’s profitability and liquidity.

**Historical period:** 2021–2023  
**Forecast period:** 2024–2026  
**Currency:** USD millions unless stated otherwise

## Start here

- [Read the six-page management report](AST_Management_Report.pdf)
- [Download the Excel financial model](AST_Master_Financial_Model.xlsx)

The report explains the findings and recommendations. Download the workbook and open it in Excel to explore the formulas, assumptions and scenarios.

## Business question

How would different operating pressures affect AST’s earnings, cash generation and ability to fund investment and scheduled debt repayments?

## Scope and approach

The project develops the supplied historical statements into a linked income statement, balance sheet and cash-flow forecast.

Work included:

- Historical statement reconciliation and disclosure of unresolved differences.
- A driver-based forecast incorporating quarterly seasonality.
- Working-capital, investment, depreciation, debt and interest schedules.
- A baseline and three separate adverse scenarios.
- Financial reconciliation checks and supporting Python calculations.
- Management recommendations supported by charts and tables.

A straightforward forecasting approach was selected given the limited historical observations and the exercise’s focus on transparent operating assumptions.

## Scenarios

| Case | Main assumptions |
|---|---|
| Base | Revenue growth of 10%, 9% and 8%; gross margin of 40%. |
| Policy shift | Sales volumes 10% below base, selling prices 2% lower, and slower working-capital conversion. |
| Cost volatility | Material prices increase 20%; selling prices recover 40% of the incremental cost; inventory days increase. |
| Temporary demand weakness | Volumes fall 20% in 2024 and 10% in 2025 before recovering to base in 2026; temporary pricing and working-capital pressures also unwind. |

The adverse cases are evaluated separately. They are not probability-weighted or combined into a joint stress case.

## Key findings

| Case | 2024 operating profit | 2026 closing cash |
|---|---:|---:|
| Base | 198.0 | 323.2 |
| Policy shift | 142.0 | 183.5 |
| Cost volatility | 160.4 | 179.0 |
| Temporary demand weakness | 98.6 | 206.7 |

Temporary demand weakness creates the deepest initial earnings decline and the lowest forecast quarter-end cash balance: $141.7m in Q4 2025.

Operating performance recovers to base in 2026 under that scenario, but closing cash remains $116.6m below base because earlier earnings losses accumulate.

Persistent cost pressure produces the lowest 2026 cash balance. Profitability alone therefore provides an incomplete view of financial resilience.

## Management recommendations

- Maintain a rolling 13-week cash forecast and define an operating cash buffer.
- Align inventory commitments with orders and delivery requirements.
- Monitor material-cost recovery and repricing delays.
- Reassess discretionary investment as conditions change.
- Reforecast using evidence on demand, prices and working capital.

## Limitations

This is an educational case involving a fictional company. Scenario assumptions are analyst judgements, not statistically estimated outcomes.

Historical opening-balance differences and unavailable depreciation and gross-capex data are disclosed in the report and workbook. Positive quarter-end cash does not establish adequate daily liquidity or covenant compliance.

Numerical checks support model consistency; they do not constitute an independent audit. Native Excel behaviour has not been comprehensively tested.

## Source and independent contribution

Corporate Finance Institute (CFI) supplied the fictional case, historical data and broad scenario framework.

This independent project developed the financial model, quantitative forecasting assumptions, scenario calibration, interpretation and recommendations. It is not an official CFI solution or an endorsed publication.

## Use of AI

AI tools supported language refinement, financial analysis, coding, model construction and numerical checks. The author directed the project scope and assumptions, reviewed the outputs and remains responsible for the final interpretation and publication.
