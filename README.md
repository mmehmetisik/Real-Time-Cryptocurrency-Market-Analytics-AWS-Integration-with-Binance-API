# Real-Time-Cryptocurrency-Market-Analytics-AWS-Integration-with-Binance-API

![project](https://github.com/mmehmetisik/Real-Time-Cryptocurrency-Market-Analytics-AWS-Integration-with-Binance-API/assets/64706956/34db4131-1693-4ff1-afda-7d0702aa5055)


## Project Overview
This project taps into the real-time data stream from cryptocurrency markets via the Binance API. It showcases how to leverage the power of AWS infrastructure for real-time analytics. The application captures data in one-minute intervals using buffers on EC2 instances, which are then securely transferred to S3 buckets. The data is subsequently migrated from S3 to RDS, where it is organized into structured tables for real-time processing.

## Architecture
The system's architecture is designed to support continuous data streaming and processing without interruption. It includes the following AWS services:
- **EC2 Instances:** For running the application and managing one-minute data buffers.
- **S3 Buckets:** To securely store data blocks received from EC2 instances.
- **RDS:** For structuring the data into tables, facilitating query operations and analytics.

## Technologies Used
- **Binance API:** For obtaining real-time cryptocurrency market data.
- **AWS Services:** Including but not limited to EC2, S3, RDS, VPC, IAM, Route 53, CloudWatch, and Lambda for comprehensive cloud infrastructure management.

## Security
Implemented within a VPC to ensure an isolated network environment, the project also utilizes IAM roles and policies for stringent authentication and access control measures.
