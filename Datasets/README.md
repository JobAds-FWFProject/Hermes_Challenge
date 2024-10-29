# Datasets for the Hermes Challenge

- newspapers_ger_1914_part_1_only_ads.csv is a dataset consisting of 101 pages conatining at least 1 job ad 
- newspapers_ger_1914_part_1_only_ads_REGIONS.csv is the expanded version of newspapers_ger_1914_part_1_only_ads.csv where each row corresponds to a region in the page.
  - New columns to this dataframe are `ID	HEIGHT	WIDTH	VPOS	HPOS	text`
  - The values in the columns `classification probability true_ad` should be updated for the regions as at the moment these metrics are for the whole page.
- regions_error_report.md contains the broke ALTO URLs in the newspapers_ger_1914_part_1_only_ads.csv 


