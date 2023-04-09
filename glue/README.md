# AWS Glue

AWS Glue is a serverless ETL tool.AWS Glue is a fully-managed extract, transform, and load (ETL) service provided by Amazon Web Services (AWS) for processing large amounts of data. It enables users to create and run ETL jobs that extract data from various sources, transform it into the desired format, and load it into target systems for analysis.

AWS Glue offers a visual interface and a code editor for developing ETL jobs using pre-built templates or custom code written in Python or Scala. It also includes a variety of built-in transformations for common data manipulation tasks, such as filtering, mapping, and aggregating data.


# Set Up

1.	Create a bucket
	
	<img width="500" alt="image" src="https://user-images.githubusercontent.com/64408106/230790630-c545c62d-b8d9-4a8e-aaaf-42a33e01f9a0.png">
	
	<img width="500" alt="image" src="https://user-images.githubusercontent.com/64408106/230790719-6571d718-b9a8-4316-9f67-9c034f5e4605.png">
	
	Need to create sub-folders: data,script and temp-dir
	script folder contains the python scripts and temp-dir is use to Glue to process thier jobs releated processings
	
	<img width="500" alt="image" src="https://user-images.githubusercontent.com/64408106/230790883-a356b875-b0f1-4428-9b15-b3424e6c1f12.png">
	
	Need to create three more subfolder inside data folder client_database, client_csv and  dataload=20220329
	
	<img width="500" alt="image" src="https://user-images.githubusercontent.com/64408106/230791496-cba22c21-5a55-4ecb-8d31-5718b79ba97d.png">


2. 	IAM Role for Glue
	Need to create IAM Role and Policy
	
	<img width="500" alt="image" src="https://user-images.githubusercontent.com/64408106/230791804-bcc15243-23c9-4211-b7a4-521b00d5d9e5.png">











