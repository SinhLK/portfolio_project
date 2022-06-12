### Clean Data From Google BigQuery Public Dataset:
SELECT
  *
FROM (SELECT DISTINCT * FROM `bigquery-public-data.world_bank_intl_debt.international_debt`) ### to remove duplicates from raw dataset
WHERE country_code NOT IN ('LMY','MIC','UMC','LAC','LMC','ECA','EAP','SAS','SSA','LDC','MNA','IDX','LIC') ### to remove sensitive cases, which are not countries

### Visualize Report via Google Datastudio: https://datastudio.google.com/reporting/e0a29c3c-ba9e-4978-835e-18d9854b0435/page/pl8uC
