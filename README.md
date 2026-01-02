# Sales-Analysis-BI-End-to-End-Pipeline
I want to share my journey through a challenging task. The task was to analyze and transform retail invoice  data collected monthly from February to May.
. It demonstrates real-time data ingestion, processing, storage, and live analytics of different tools. The project utilizes a combination of Excel, SSIS, Power BI, SQL Server, and Power BI.


## Table of Contents

- [Technologies Used](#technologies-used)
- [Prerequisites](#Prerequisites-workflow)
- [Usage](#usage)
## Architecture Overview
The project consists of a scalable, data pipeline that processes, and stores data using different services and technologies.

![DBT drawio(1)](https://github.com/user-attachments/assets/b567df8d-fab4-4bcc-bcef-a4f903242939)





### Key Components:
1. **Data Analysis**: Analyze data using Excel And Power Pivot.
2. **Data Pipeline (SSIS)**: Managed by SSIS To move And preprocess Into SQL Server.
3. **Data Processing (SQL Server )**:
    - First Step  Cleaning Data And Drop Unwanted Columns.
    - The second step builds Star Schema For Dimensions Tables And Fact and stores the results in SQL Server.
    - Third Step Move Data From the Sql Server To Power Bi.

## Technologies Used

- **Excel**: Data processing and analyzing data.
- **SSIS**: Move Data Pipline.
- **SQL Server**: Stores processed data and results.


### Prerequisites

- **Microsoft Excel**.
- **SSISe**.
- **SQL Server**.

## Usage
- Excel: Ensure Data is Good And Make Some Analysis.
- SSIS: Use SSIS to manage and Move Data From Excel To SSIS.
- SQL Server: SQL will process the data To Make Star Schema And Dim, Fact.




![Excel_Analysis](https://github.com/user-attachments/assets/55ecc73b-31d5-47c4-b5dd-fb352069b410)
![data model](https://github.com/user-attachments/assets/4574e40f-b49b-4ae7-9c97-61ffa671c577)
![sql](https://github.com/user-attachments/assets/614e0f9a-0099-4917-a47a-e4589553dc94)
![Data_Model_Sql](https://github.com/user-attachments/assets/34dd2351-37bb-4cb4-9b6b-68adfb05305e)


