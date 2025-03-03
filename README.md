### **Spotify ETL Pipeline using AWS & Snowflake**  
**Automated Data Pipeline for Extracting, Transforming, and Loading (ETL) Spotify Data into Snowflake for Analytics**  

---

## **🔹 Overview**  
This project implements an **ETL pipeline** using **AWS Lambda, S3, Snowflake, and Power BI** to automate the extraction, transformation, and loading of **Spotify API** data for real-time analytics.  

---

## **🔹 Workflow**  
1. **Extract (Data Ingestion)**  
   - **AWS Lambda** extracts data from **Spotify API** and stores it in **Amazon S3 (Raw Data Bucket)**.  
   - **Amazon CloudWatch** triggers the extraction process daily.  

2. **Transform (Data Processing)**  
   - Another **AWS Lambda function** cleans, processes, and transforms the extracted data.  
   - The transformed data is stored in **Amazon S3 (Processed Data Bucket)**.  
   - **S3 Event Triggers** automate this transformation process.  

3. **Load (Data Warehousing & Analytics)**  
   - **Snowpipe** loads the transformed data into **Snowflake** for structured storage.  
   - **Power BI** connects to **Snowflake**, enabling interactive **data visualization** and analytics.  

---

## **🔹 Tech Stack**  
- **Cloud Services:** AWS Lambda, S3, CloudWatch, Snowflake, Power BI  
- **Programming Languages:** Python  
- **Database & Warehousing:** Snowflake, S3  
- **API Integration:** Spotify Web API  
- **Automation & Monitoring:** CloudWatch, Snowpipe  

---

## **🔹 Key Features**  
✔ **Automated ETL workflow** using AWS Lambda and Snowflake  
✔ **Real-time data processing** with Snowpipe and S3 event triggers  
✔ **Scalable and cost-efficient** cloud-based architecture  
✔ **Data visualization** in Power BI for business insights  

