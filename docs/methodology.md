# Methodology and ratio definitions

## Workbook structure

| Worksheet | Purpose |
|---|---|
| Cover Page | Project topic and scope |
| Appendix 1(Chosen Company) | Beximco consolidated statements and supplementary inputs |
| Appendix 2(Competitor Company) | Renata consolidated statements and supplementary inputs |
| Appendix 3(Calculated Ratio's) | Linked ratios and growth calculations |
| Appendix 4( Fin Ratio Charts) | Chart data and financial ratio charts |

## Definitions used in the workbook

| Measure | Formula | Interpretation |
|---|---|---|
| Net profit margin | Consolidated profit after tax / revenue | Profit retained per unit of revenue |
| ROCE | Operating profit / (total assets − current liabilities) | Return on closing capital employed |
| Asset turnover | Revenue / total assets | Revenue generated per unit of closing assets |
| Current ratio | Current assets / current liabilities | Coverage of short-term obligations by current assets |
| Operating cash flow ratio | Operating cash flow / current liabilities | Cash flow coverage of closing short-term liabilities |
| Total liabilities / total equity | (Current + non-current liabilities) / total equity | Liabilities relative to the equity base |
| Total liabilities / total assets | (Current + non-current liabilities) / total assets | Share of assets financed by liabilities |
| Price / earnings | Market price per share / restated EPS | Price relative to annual earnings per share |
| Restated EPS | Profit attributable to owners / workbook share count | Earnings per share using the workbook's restated share base |

Asset-based ratios use closing balances rather than average balances. The liabilities-based measures differ from ratios limited to interest-bearing debt. EPS uses the share counts recorded in the workbook; the restatement basis has not been independently verified.

## Reading the CSV

`data/key-ratios.csv` contains one row per metric, company and year. Percentage values use decimals: `0.175148` means approximately `17.51%`. Ratios in times use ordinary numeric values. Source worksheet names and cell addresses identify where each value came from.

The CSV is a snapshot of saved calculation results, not a live link. Changes to the Excel workbook do not automatically update the CSV, chart or README.
