# Impact of Interest Rates and Inflation on Unemployment (SDG 8)

## Overview
This project analyzes the relationship between unemployment, inflation (CPI), and interest rates (BLR) to inform policies for Sustainable Development Goal 8: Decent Work and Economic Growth.

## Data Sources
- **Inflation (CPI):** [World Bank](https://api.worldbank.org/v2/en/indicator/FP.CPI.TOTL.ZG?downloadformat=excel)
- **Unemployment Rate:** [DOSM Labor Force Survey](https://storage.dosm.gov.my/labour/lfs_year.csv)
- **Interest Rates:** [Malaysia Open Data](https://storage.data.gov.my/finsector/interest_rates_annual.csv)

## Methods
- **Preprocessing:** Data merged and cleaned in Excel using VLOOKUP/INDEX MATCH and statistical imputation for missing data.
- **Analysis:** Descriptive statistics and linear regression to examine the impact of inflation and interest rates on unemployment.
- **Visualization:** Scatter plots, line graphs, and heatmaps to show relationships and trends.

## Findings
- Negative correlation between unemployment and inflation (Phillips Curve).
- Adjusting inflation and interest rates could lower unemployment, supporting SDG 8 goals.

## Conclusion
Preliminary insights suggest that regulating inflation and interest rates may reduce unemployment. Further analysis with advanced models could deepen the understanding of these economic relationships.
