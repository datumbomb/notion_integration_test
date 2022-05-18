# intercom-analytics
 a prefect flow for pushing analytics data to intercom 

# How to Use

## Register

`prefect register --project "reverse ETL" --path intercom_push.py --label bigquery --label segment`

## Agent

`prefect agent docker start --env EXTRA_PIP_PACKAGES=analytics-python --label bigquery --label segment --show-flow-logs`