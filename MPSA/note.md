"South Sudanese Refugees" and "Mai-Mai NDC\\RÃ©novÃ©" labeled as 1 in the labeled data are not included in the filtered data due to a processing error in Python. 
Contagious events happened within one month.

################################

1. Reorganize UCDP GED data to include events from 2008/09 to 2011/12, and 2021. Now the coverage is 2008/9-2021/12.

- If no restriction, the total number of events between 2008 to 2011 are N = 4657.

- Refine: side_a limited to "Government of DR Congo (Zaire)": N = 1554.

- Refine: put death threashold: death >= 25: N = 85

2. Steps to work on variables in DRC_coding_040223

- Find 15 new events `original_UCDP_DRC_08_21_gov_d25` in 2008,2009,2021. Add them on the spreadsheet (notice the columns don't match).
- Then we need to go back to the `original_UCDP_DRC_08_21_gov` to find contagious events.

