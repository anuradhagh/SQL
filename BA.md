#SELECT* FROM [bigquery-public-data:sec_quarterly_financials.quick_summary]
#results displayed all content of table
#SELECT* FROM [bigquery-public-data:sec_quarterly_financials.quick_summary] WHERE company_name='SKYWORKS SOLUTIONS, INC.'
#results displayed content for company SKYWORKS
#SELECT count (distinct(company_name)) FROM [bigquery-public-data:sec_quarterly_financials.quick_summary]
#result 14851
#SELECT AVG(value) FROM [bigquery-public-data:sec_quarterly_financials.quick_summary]
#result 3.0047132431860402E13
#SELECT MAX(value) FROM [bigquery-public-data:sec_quarterly_financials.quick_summary] GROUP BY company_name
#result 4.81790955E14
