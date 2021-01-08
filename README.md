# whizlabs Google Certified Professional Data Engineer  
# Chapter 3: Data engineering Basics

Storage Options Intro:
- Cloud Storage
- Cloud SQL
- Cloud Spanner
- Cloud Datasore
- Cloud Bigtable
- Cloud BigQuery
- Persistent Disk
- Cloud Firestore

Storage Options Features:

- High availability and reliability across regions and zones - riding on the Google Cloud Network
- All the data is encrypted automatically
- Store Exabytes of data in multiple storage classes
- Integrated with other products and services via a single access and API
```
```
<img src="https://github.com/cgpeanut/whizlabs-data-engineer/blob/master/images/storage-aws.png" alt="IMAGE ALT TEXT HERE" width="550" height="250" /></a>
```
```

Storage Options Types:

- Structured Data
    - If the data you want to store can be organized into a table structure with rows and columns, it's structured data.
    - Structured data comes in various sizes, and cost based on the requirements. 
    - Examples - Logs, user profiles, sensor data, financial data.
- Structured Data can be stored in:
    - Cloud SQL, Cloud Spanner, Clouad Datastore, Cloud Bigtable, Clouad Bigquery, Persistent Disk.

- Unstructured Data
    - Unstructured data is a sequence of bytes which could be from a video, image or a document 
    - Data is stored as objects in buckets
    - You can't get any insights from structured data
    - Cloud Firestore save data in a document format with key-value pair. 
Unstructed Data can be stored in: 
    - Cloud Storage, Cloud Firestore

- Cloud SQL Overview:-Web service that allowsa you to create, configure, and use relational database that live in Google's cloud. 
    - Used for: Structured data, Typical web frameworks, Hosting MySQL & PostgreSQL
    - Common Workloads: SaaS, Blogs, CMS, BI, CRM, Geospatial applications: Examples: Phillips

- Cloud Spanner Overview: Fully managed, mission-critical relational database service.
    - Used for: Structured data, atomic, OTP, Strong consistency
    - Common Workloads: Trading, Insurance, Telecom, Gaming, Logistics, E-Commerce

- Cloud Storage Overview: Unstructured blob/bucket storage - scalable, fully managed, cost effective and highly available. 
    - Used for: Images, pictures, videos - Objectsm blobs - Unstructured data
    - Common workloads: Multimedia, - streaming, storage, - storage for custom data anaytics pipeline.
    - Archive, backup and disaster recovery.

- Cloud Datastore Overview: Fully managed, schemaless, non-relational datastore
    - Used for: NoSQL solutiuon, Atomic, rioch queries, High scalability
    - Common Workloads: Gaming apps - states, leaderboards - Catalogs - User/device profiles.

- Cloud Bigtable Overview: Fast, fully managed, highly scalable NOSQL database service.
    - Used for: 1 TB to hundreds of Petabytes - Low latency - Autoscaling via nodes.
    - Common Workloads: Fintech, Adtech - Internet of Things - Machine learning applications. 

- Cloud BigQuery Overview: Fully managed data analyis service that enables business to analyze Big Data.
    - Used for: 1 TB to hundreds of Petabytes - Low Latency - ASutoscaling via nodes 
    - Common Workloads: Fintech, Adtech - Internet of Things - Machine learning applications

- Persustent Disk Overview: Durable High performance block storage for GCP. 
    - Used for: Compute Engine - Kubernetes Engine - Snapshots 
    - Common Workloads: Attached to VMs, Containers, Durable backups

- Cloud Firestore Overview: NoSQL database for storing, syncing, and quering data for mobile and web apps
    - Used for: Serverless third party authentication - NoSQL JSON database - Document Storage
    - Common Workloads: Mobile/web apps - Simple storag with global sync, query - Real-time mobile access.

```
```
<img src="https://github.com/cgpeanut/whizlabs-data-engineer/blob/master/images/gcp-storage-flowchart.png" alt="IMAGE ALT TEXT HERE" width="750" height="450" /></a>
```

# Data Engineering Basics:
Chapter 4: Storage Options:
Chapter 5: Cloud SQL: Web service that allowsa you to create, configure, and use relational database that live in Google's cloud.

- Features: 

    - Fully managed community editions of MySQL and PostreSQL - 2 generations
    - MySQL and PostredSQL instances can scale up to 64 CPUs, 416 GB RAM and 30 TB data storage
    - Integrated tightly with other producst and services in GCP
    - Instances are accessible from anywhere, available regionally in US, EU and Asia
    - Secure external connections with the Cloud SQL Proxy or with the SSL/TLS protocol

Chapter 6: Cloud Spanner:
Chapter 7: Cloud Bigtable 1
Chapter 8: Cloud Bigtable 2
Chapter 9: Clouad Datastore

# Data Processing
Chapter 10: Pipelines 1: Design & Development 
Chapter 11: Pipelines 2: Deployment 
Chapter 12: Pipelines Demo: Dataflow PubSub
Chapter 13: Cloud Dataflow
Chapter 14: Cloud Datproc
Chapter 15: Data Loss Prevention
Chapter 16: Cloud DataPrep 1
Chapter 17: Cloud Dataprep 2
Chapter 18: Cloud Dataprep Demo
Chapter 19: Clouad Data Lifecycle Management 
Chapter 20: Clouad Composer
Chapter 21: Cloud Composer Demo: Dataproc Airflow Hadoop

# Big Data
Chapter 22: Clouad BigQuery and DataStudio
Chapter 23: Data Warehous Migration
Chapter 24: Hybrid Multi Cloud

# Operations and management 
Chapter 25: Compliance
Chapter 26: Clouad IAM
Chapter 27: Encryption and key management 
Chapter 28: Cloud Datalab

# AI ML
Chapter 29: Clouad Apeeh API, Clouad Vision API, Translate API
Chapter 30: A.I Platforn (demo training)
Chapter 31: Cloud AutopML (demo training)
