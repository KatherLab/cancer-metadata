# tcga-info
machine-readable information for the TCGA dataset, mirrored from other sources. The aim of this repo is to 
1. provide standardized and slightly cleaned data
2. ease the load on the original servers

| file name | changes made | retrieved from |
| --------- | ------------ | -------------- |
| tcga-tumor-types.csv | none | https://gdc.cancer.gov/resources-tcga-users/tcga-code-tables/tcga-study-abbreviations |
| immune.xlsx | none | https://www.cell.com/cms/10.1016/j.immuni.2018.03.023/attachment/1b63d4bc-af31-4a23-99bb-7ca23c7b4e0a/mmc2.xlsx |
| outcome.xlsx | reordered sheets, removed index | https://api.gdc.cancer.gov/data/1b5f413e-a8d1-4d10-92eb-7c4ae739ed81 |
| sites.csv | none | https://gdc.cancer.gov/resources-tcga-users/tcga-code-tables/tissue-source-site-codes