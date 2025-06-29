# youtube-Data-engineering-project

📊 Data Engineering Project on AWS: YouTube Trending Analytics
This project showcases a cloud-based data engineering pipeline designed to ingest, transform, store, and analyze trending YouTube video data across multiple countries. Using a combination of AWS services, the pipeline handles both structured and semi-structured data, transforming raw CSV/JSON files into actionable insights.

The primary objective is to create a scalable, serverless architecture that enables end-to-end data processing, efficient querying, and interactive reporting without relying on on-premise infrastructure.

🚀 Key AWS Services Used:
Amazon S3: Used as the central data lake to store raw and transformed datasets in a secure and scalable manner.

AWS IAM: Manages access to various services with granular permissions, ensuring data security and role-based access.

AWS Glue: Performs the ETL (Extract, Transform, Load) operations on the raw YouTube dataset using Glue Jobs and Crawlers.

AWS Lambda: Used to automate and trigger transformations and workflows without maintaining any servers.

Amazon Athena: Enables interactive SQL-based querying directly on the S3 data using serverless computing.

Amazon QuickSight: A business intelligence tool used to create dynamic dashboards and visualize YouTube video performance by views, categories, countries, and more.

📂 Dataset:
The project uses publicly available YouTube trending data from Kaggle, which includes daily stats such as views, likes, comments, tags, video categories, and more — stored in multiple regional files.

Kaggle Dataset Link →
