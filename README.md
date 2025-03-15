# Spotify ETL Data Pipeline Project Using AWS

### Description
I built an ETL pipeline using the Spotify API on AWS. It extracts music data, transforms it into a structured format, and loads it into an AWS data store. This automated pipeline ensures efficient data processing for analytics and insights, leveraging AWS services for scalability and reliability.

### Architecture
![Architecture Diagram](https://github.com/sudeshnadas0101/spotify-etl-data-pipeline-project/blob/main/spotify_architecture.jpg)

### API Used
Spotify API is a RESTful web service that allows developers to access Spotify’s vast music database, including songs, albums, artists, playlists, and user data.
Link for the API used - [Spotify API Documentation](https://developer.spotify.com/documentation/web-api/).


### Amazon Services Used
- **S3 (Simple Storage Service) -** Amazon S3 (Simple Storage Service) is a scalable, secure, and high-performance cloud storage service provided by AWS. It is used to store and retrieve any amount of data at any time.
  
- **AWS Lambda -** AWS Lambda is a serverless computing service that lets you run code without provisioning or managing servers. It automatically scales and executes your code in response to events.

- **Cloud Watch -** Amazon CloudWatch is a monitoring and observability service that helps you track AWS resources and applications in real time. It collects and analyzes logs, metrics, and events to provide insights and automate responses.

- **Glue Crawler -** AWS Glue Crawler is a service that automatically scans and catalogs data stored in various sources, such as Amazon S3, relational databases, and NoSQL stores. It helps create a schema for your data, making it easier to query and analyze using AWS Glue Data Catalog and services like Amazon Athena.

- **Data Catalog -** AWS Glue Data Catalog is a centralized metadata repository that stores information about datasets, such as their location, schema, and structure. It helps organize and manage data across various AWS services, making it easier to search, query, and analyze.

- **Amazon Athena -** Amazon Athena is a serverless, interactive query service that allows you to run SQL queries on structured and semi-structured data stored in Amazon S3. It eliminates the need for complex ETL pipelines by enabling direct querying without provisioning infrastructure.

### Installed Packages
```
pip install spotipy
pip install pandas
```
