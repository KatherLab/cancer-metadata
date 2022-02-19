# cancer-metadata
machine-readable information for the TCGA and CPTAC datasets, mirrored from other sources. The aim of this repo is to 
1. provide standardized and slightly cleaned data
2. ease the load on the original servers

# TCGA, general data

| file name | changes made | retrieved from |
| --------- | ------------ | -------------- |
| tcga/tcga-tumor-types.csv | none | https://gdc.cancer.gov/resources-tcga-users/tcga-code-tables/tcga-study-abbreviations |
| tcga/immune.xlsx | none | https://www.cell.com/cms/10.1016/j.immuni.2018.03.023/attachment/1b63d4bc-af31-4a23-99bb-7ca23c7b4e0a/mmc2.xlsx |
| tcga/outcome.xlsx | reordered sheets, removed index | https://api.gdc.cancer.gov/data/1b5f413e-a8d1-4d10-92eb-7c4ae739ed81 |
| tcga/tissue-sites.csv | none | https://gdc.cancer.gov/resources-tcga-users/tcga-code-tables/tissue-source-site-codes |
| tcga/cbio_clinical.xlsx | none | https://www.cbioportal.org/study/summary?id=laml_tcga_pan_can_atlas_2018 |
| tcga/tcga-institution-sites.csv | none | https://gdc.cancer.gov/resources-tcga-users/tcga-code-tables/tissue-source-site-codes |
| tcga/liu.xlsx | none | https://www.cell.com/cancer-cell/fulltext/S1535-6108(18)30114-4#supplementaryMaterial |

# TCGA, molecular data

| file name | changes made | retrieved from |
| --------- | ------------ | -------------- |
| tcga/tcga-cna-part1.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part10.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part11.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part12.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part13.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part14.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part2.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part3.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part4.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part5.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part6.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part7.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part8.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-cna-part9.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part1.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part10.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part11.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part12.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part13.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part14.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part2.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part3.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part4.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part5.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part6.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part7.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part8.txt | none | cbioportal.org (1066 gene list) |
| tcga/tcga-mutations-part9.txt | none | cbioportal.org (1066 gene list) |


# CPTAC, molecular data

| file name | changes made | retrieved from |
| --------- | ------------ | -------------- |
| cptac/CPTAC_CLINI_Data.xlsx| none | ??? |
| cptac/CPTAC_CLINI_Data.xlsx | none | cbioportal.org |
| cptac/CPTAC_CNA_part1.txt | none | cbioportal.org |
| cptac/CPTAC_CNA_part2.txt | none | cbioportal.org |
| cptac/CPTAC_Mutations_part1.txt | none | cbioportal.org |
| cptac/CPTAC_Mutations_part2.txt | none | cbioportal.org |
| cptac/CPTAC_RNA expression z-scores_part1.txt | none | cbioportal.org |
| cptac/CPTAC_RNA expression z-scores_part2.txt | none | cbioportal.org |
| cptac/CPTAC_sample_matrix_part1.txt | none | cbioportal.org |
| cptac/CPTAC_sample_matrix_part2.txt | none | cbioportal.org |



