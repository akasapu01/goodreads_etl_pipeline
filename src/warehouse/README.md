# Data Warehouse Configuration

This repository contains the configuration templates and orchestration logic for managing AWS Redshift data warehouse environments.

## warehouse_config.cfg file in warehouse folder contains  

    [AWS]  
    KEY=<AWS-KEY>
    SECRET=<AWS-SECRET-KEY>
      
    [CLUSTER]  
    HOST='<Redshift Cluster Endpoint>'  
    DB_NAME='<db-name>'  
    DB_USER='<db-user-name>'  
    DB_PASSWORD='<db-password>'  
    DB_PORT=<db-port, default 5439>  
      
    [IAM_ROLE]  
    ARN=<Redshift ARN role>
      
      
    [STAGING]  
    SCHEMA=<Warehouse-staging-schema>  
      
    [WAREHOUSE]  
    SCHEMA=<Warehouse-schema>  
      
      
    [BUCKET]  
    LANDING_ZONE=<landing-zone-bucket>  
    WORKING_ZONE=<working-zone-bucket>
    PROCESSED_ZONE=<processed-zone-bucket>

## Maintainer

Jyothi Sree
Senior Data Engineer
Email: Jyothisree.work@gmail.com
LinkedIn: https://www.linkedin.com/in/jyothisree123/

### About the Developer
Senior Data Engineer with 6+ years of experience building large-scale batch and streaming pipelines across AWS, Azure, GCP, Snowflake, and Databricks. Specializing in data modeling, warehousing, and Lakehouse architecture, with a focus on optimizing pipeline performance and hardening data quality for enterprise production environments.