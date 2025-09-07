# 🏅 Tokyo Olympic Data Analytics with Azure

This project showcases an **end-to-end data engineering** pipeline built on the Microsoft Azure platform.  
The pipeline covers **data ingestion, storage, transformation, analytics, and dashboard visualization**.

![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Tokyo 2020 Olympics](https://img.shields.io/badge/Tokyo%202020%20Olympics-000000?style=for-the-badge&logo=olympics&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)


## 🙌 Acknowledgements
- Dataset: [Kaggle - Tokyo Olympics](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)  
- Uploaded to **GitHub repository** for integration with Azure Data Factory.
- Azure Documentation: [Mount Data Lake to Databricks](https://learn.microsoft.com/en-us/azure/databricks/dbfs/mounts)
---

## ⚙️ Architecture Overview
![Architecture Diagram](https://github.com/Aryan-Christian27/Olympic-Data-Analytics-With-Azure/blob/main/Images/Data-Architecture.png) <!-- replace with your image path -->

## ⚙️ Technologies Used

* **Data-modeling/Data-Architecture:** Draw.io
* **Cloud Platform:** Microsoft Azure
* **Data Ingestion:** Azure Data Factory (ADF)
* **Data Storage:** Azure Data Lake Storage (ADLS) Gen2
* **Data Transformation:** Azure Databricks
* **Data Warehousing & Analytics:** Azure Synapse Analytics
* **Data Visualization:** Microsoft Power BI

**Steps in the Pipeline:**

1. **Data Ingestion**
   - Used **Azure Data Factory** to create a pipeline.
   - The pipeline extracts data directly from GitHub (Kaggle dataset uploaded).
   - Data is ingested into **Azure Data Lake Gen2** (Raw Zone).

2. **Raw Data Storage**
   - All ingested files are stored in **Data Lake Gen2** inside the `raw-data` folder.

3. **Data Transformation**
   - Connected **Azure Databricks** with **Azure Data Lake Gen2**.  
     👉 Refer to the official guide: [Mount Azure Data Lake Storage to Databricks](https://learn.microsoft.com/en-us/azure/databricks/dbfs/mounts).
   - Performed data cleaning, formatting, and transformation in **Databricks (PySpark)**.
   - Transformed data is stored back into **Data Lake Gen2** inside the `transformed-data` folder.

4. **Analytics**
   - Used **Azure Synapse Analytics** to query transformed data stored in Data Lake.
   - Enabled interactive SQL queries for deeper insights.

5. **Dashboard & Visualization**
   - Created dashboards using **Power BI**.
   - Visualized key metrics and insights from the Olympics dataset.

---


## 🚀 Key Insights
- Built a robust **data pipeline** that can be extended to real-time datasets.
- Demonstrated the integration of multiple **Azure services** for analytics.
- Created **interactive dashboards** with Power BI to showcase Olympic trends.

---

## 📌 How to Run
1. Download dataset from kaggle.  
2. Upload dataset to your GitHub repo.  
3. Configure **Azure Data Factory** pipeline to pull data from GitHub.  
4. Mount **Data Lake Gen2** to **Databricks** and run transformation notebooks.  
5. Use **Synapse Analytics** for querying transformed data.  
6. Connect **Power BI** to Synapse or Data Lake for dashboarding.

---

## 📷 Dashboard Overview
![Dashboard](https://github.com/Aryan-Christian27/Olympic-Data-Analytics-With-Azure/blob/main/Images/Dashboard-PowerBI.png)

---
## 👤 Author

* **[Aryan Khristi]** - [![linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christian-aryan2710/)
  
Feel free to reach out with any questions or feedback!




