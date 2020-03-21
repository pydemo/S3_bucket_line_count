# S3_bucket_line_count
Gives total line count of for all files in S3 bucket.

## Bucket
    tables/
        FACT_IMPRESSIONS_APPENDED/
            B_0/
              FACT_IMPRESSIONS_APPENDED.B_0.campaign_00.campaign.csv.gz
              FACT_IMPRESSIONS_APPENDED.B_0.campaign_01.campaign.csv.gz
              ...
              FACT_IMPRESSIONS_APPENDED.B_0.campaign_09.campaign.csv.gz



## Exec log
```
tables/FACT_IMPRESSIONS_UPDATED/
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_0/FACT_IMPRESSIONS_UPDATED.B_0.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_1/FACT_IMPRESSIONS_UPDATED.B_1.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_2/FACT_IMPRESSIONS_UPDATED.B_2.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_3/FACT_IMPRESSIONS_UPDATED.B_3.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_4/FACT_IMPRESSIONS_UPDATED.B_4.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_5/FACT_IMPRESSIONS_UPDATED.B_5.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_6/FACT_IMPRESSIONS_UPDATED.B_6.campaign_00.updated_fact_from_dim.csv.gz
S3 key:  tables/FACT_IMPRESSIONS_UPDATED/B_7/FACT_IMPRESSIONS_UPDATED.B_7.campaign_00.updated_fact_from_dim.csv.gz
File line count: 2
File line count: 2
File line count: 2
File line count: 2
File line count: 2
File line count: 2
File line count: 2
File line count: 2
Total rows: 16
s3count.py executed in 0.86 seconds.
```

