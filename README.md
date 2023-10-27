# ETLFlowGCP
 ETLFlowGCP is a data integration and processing project designed for Google Cloud Platform (GCP). It streamlines the Extract, Transform, Load (ETL) process, enabling users to efficiently collect, transform, and store data on GCP.

#Technology Stack:

Google Cloud Platform (GCP): The project is hosted on and fully utilizes GCP's services for data storage, processing, and analytics.

Cloud Storage: GCP Cloud Storage is employed to store both raw and processed data. Data extraction and transformation results are stored here.

BigQuery: Google BigQuery serves as the primary data warehousing and analytical platform for storing and querying processed data.

Cloud Dataflow: Google Cloud Dataflow, powered by Apache Beam, is used for parallelized data processing. It executes data transformations at scale.

Python: Python is the primary programming language for implementing data transformation logic. Google Dataflow and Cloud Storage client libraries in Python are used for this purpose.


----IN FUTURE-----
Automation and CI/CD: Infrastructure as Code (IaC) tools, like Terraform, are used for automation and provisioning of resources. Continuous Integration and Continuous Deployment (CI/CD) pipelines automate testing and deployment of changes to the project.
