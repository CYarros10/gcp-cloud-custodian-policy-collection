
mode:
audit = trigger on cloud logging api call
periodic = trigger on cloud scheduler
pull = trigger on CLI command
scc = trigger on Security Command Center finding

action:
notify = identify and send an email about the malformed resource
update = identify and update the malformed resource
delete = identify and delete the malformed resource
report = one-off CLI report of malformed resources



| policy | resource | type | action | description | 
|---|--|---|---|---|
| bigquery_dataset_labels.yml | gcp.bq-dataset | audit | notify | notify on bq dataset create/update if labels are absent | 
| bigquery_job_labels.yml | gcp.bq-job | audit | notify | notify on bq job create/update if labels are absent | 
| bigquery_table_labels.yml | gcp.bq-table | audit | notify | notify on table job create/update if labels are absent | 
| cloud_function_labels.yml | gcp.function | audit | notify | notify on dataset create/update if labels are absent | 
| compute_instance_labels.yml | gcp.instance | audit | notify | notify on dataset create/update if labels are absent | 
| dataflow_job_labels.yml | gcp.dataflow-job | audit | notify | notify on dataset create/update if labels are absent | 
| gcs_bucket_labels.yml | gcp.bucket | audit | notify | notify on dataset create/update if labels are absent | 
| persistent_disk_labels.yml | gcp.disk | audit | notify | notify on dataset create/update if labels are absent | 
| pubsub_subscription_labels.yml | gcp.pubsub-subscription | audit | notify | notify on dataset create/update if labels are absent | 
