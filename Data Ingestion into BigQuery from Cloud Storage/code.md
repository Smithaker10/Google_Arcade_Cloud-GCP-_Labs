
# Data Ingestion into BigQuery from Cloud Storage


> **Note:** Establish Hybrid Network Connectivity with NCC


### ⚠️ Disclaimer
- **This script and guide are provided for  the educational purposes to help you understand the lab services and boost your career. Before using the script, please open and review it to familiarize yourself with Google Cloud services. Ensure that you follow 'Qwiklabs' terms of service and YouTube’s community guidelines. The goal is to enhance your learning experience, not to bypass it.**

### ©Credit
- **DM for credit or removal request (no copyright intended) ©All rights and credits for the original content belong to Google Cloud [Google Cloud Skill Boost website](https://www.cloudskillsboost.google/)** 🙏



```bash

bq mk work_day && bq load --source_format=CSV --skip_leading_rows=1 work_day.employee gs://qwiklabs-gcp-04-d6c61a671c00-5xyr-bucket/employees.csv employee_id:INTEGER,device_id:STRING,username:STRING,department:STRING,office:STRING
```
</a>

</div>
