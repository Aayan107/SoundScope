# <h1> SoundScope: Unveiling the Beat of Data
<strong>SoundScope </strong> uses Kafka for data collection, GCS for temporary storage, DBT for data transformation, and BigQuery for analysis. The pipeline is orchestrated by Airflow and deployed on GCP with Docker and Terraform.

</br>

### Architecture
![Streamline Architecture](Screenshots/Streamline%20Architecture%20diagram.jpg)

* **Apache Kafka**: Acts as a messaging queue to handle the real-time data ingestion.
* **Apache Spark**: Performs stream processing to transform the raw data.
* **Data Lake**: Stores processed data for further analysis.
* **Google Cloud Storage (GCS)**: Temporary storage for intermediate data.
* **DBT (Data Build Tool)**: Transforms and models the data stored in GCS.
* **BigQuery**: Performs data analysis and querying.
* **Data Studio**: Visualizes the analyzed data through interactive dashboards.
* **Airflow**: Orchestrates the entire pipeline, ensuring smooth data flow and task management.
* **Docker and Terraform**: Used for containerization and infrastructure as code, respectively, to deploy the pipeline on GCP.


### Real-time data analytics Dashboard in Looker Studio
![Real-time data analytics Dashboard in Looker Studio](Screenshots/Real-time%20data%20analytics%20Dashboard%20in%20Looker%20Studio.jpg)

### Kafka Console
![Kafka Console](Screenshots/Kafka%20Console.jpg)

### Airflow Console
![Airflow Console](Screenshots/Airflow%20Console.jpg)


## Author

* GitHub - [Aayan](https://github.com/Aayan107)
* LinkedIn - [@Aayan107](https://www.linkedin.com/in/aayan107/)