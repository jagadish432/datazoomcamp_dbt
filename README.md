# datazoomcamp_dbt

This repo is for dbt-cloud practice.

DBT cloud will have permissions to write to non-main/non-master branch, so we created a new dbt-cloud branch for our practice.

we have an ssh key in dbt-cloud which we add in our github repository under security -> Deploy keys section

we also created a service account in gcp with almost admin access for bigquery, and we downloaded its json file and we used that same json file as creds in dbt cloud for connection to the bigquery
