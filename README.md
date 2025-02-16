├── README.md  
├── lambda_data_ingestion/  
│   ├── sap_ingestor.py      # Lambda code for SAP HANA API  
│   ├── shopify_ingestor.py  # Lambda code for Shopify API  
├── glue_scripts/  
│   ├── sales_transformer.py # PySpark ETL script  
├── dbt_models/  
│   ├── inventory_turnover.sql  # dbt model for Redshift  
├── airflow_dags/  
│   ├── etl_orchestrator.py  # Airflow DAG  
├── terraform/  
│   ├── glue_job.tf          # IaC for AWS resources  
│   ├── redshift_cluster.tf  
└── sample_data/  
    └── sales_sample.csv  
