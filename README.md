# whizlabs Google Certified Professional Data Engineer  
# Chapter 3: Data enineering Basics

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
    - Unstructured datais a sequence of bytes which could be from a video, image or a document 
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
<img src="https://github.com/cgpeanut/whizlabs-data-engineer/blob/master/images/gcp-storage-flowchart.png" alt="IMAGE ALT TEXT HERE" width="550" height="250" /></a>
```