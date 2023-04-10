# AWS Glue

AWS Glue is a serverless ETL tool.AWS Glue is a fully-managed extract, transform, and load (ETL) service provided by Amazon Web Services (AWS) for processing large amounts of data. It enables users to create and run ETL jobs that extract data from various sources, transform it into the desired format, and load it into target systems for analysis.

AWS Glue offers a visual interface and a code editor for developing ETL jobs using pre-built templates or custom code written in Python or Scala. It also includes a variety of built-in transformations for common data manipulation tasks, such as filtering, mapping, and aggregating data.


# Set Up

1.	Create a bucket
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230790630-c545c62d-b8d9-4a8e-aaaf-42a33e01f9a0.png">
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230790719-6571d718-b9a8-4316-9f67-9c034f5e4605.png">
	
	Need to create sub-folders: data,script and temp-dir
	script folder contains the python scripts and temp-dir is use to Glue to process thier jobs releated processings
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230790883-a356b875-b0f1-4428-9b15-b3424e6c1f12.png">
	
	Need to create three more subfolder inside data folder client_database, client_csv and  dataload=20220329
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230791496-cba22c21-5a55-4ecb-8d31-5718b79ba97d.png">


2. 	IAM Role for Glue
	Need to create IAM Role and attached the Policy
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230791961-95a99fed-d4d4-4f73-837f-07255483d996.png">
	
	Adding AdminstractorAccess Role is bad for productoin but pratice we can you use 
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230792083-567d8f51-1334-44d0-861c-a74f4282b7bf.png">
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230792255-498878bf-08f3-49aa-84b0-7c55b0d44679.png">


# AWS Glue Data Catalog 

The Glue Data Catalog is a fully-managed metadata repository and catalog service provided by Amazon Web Services (AWS) for storing and managing structured and semi-structured data. It serves as a central repository that stores information about data sources, metadata definitions, data lineage, and data transformation processes.


Using Glue Data Catalog, organizations can manage and organize their data assets, and make it easier for data analysts, scientists, and engineers to discover, understand, and use the data. The catalog is designed to work with a range of AWS data services, such as Amazon S3, Amazon RDS, Amazon Redshift, and Amazon Athena, as well as third-party data sources.


# AWS Glue Database

AWS Glue Database is a central metadata repository in AWS Glue that stores information about data sources, targets, ETL jobs, and other artifacts used in the ETL process. It allows users to define and manage tables and schemas that represent their data, making it easier to perform ETL operations and manage data catalogs.


AWS Glue Database provides a logical view of data stored in various sources and enables users to define and organize tables into a hierarchical structure called a database. It supports various data formats, including structured, semi-structured, and unstructured data.












