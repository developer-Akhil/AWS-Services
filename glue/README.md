# AWS Glue

AWS Glue is a serverless ETL tool.AWS Glue is a fully-managed extract, transform, and load (ETL) service provided by Amazon Web Services (AWS) for processing large amounts of data. It enables users to create and run ETL jobs that extract data from various sources, transform it into the desired format, and load it into target systems for analysis.

AWS Glue offers a visual interface and a code editor for developing ETL jobs using pre-built templates or custom code written in Python or Scala. It also includes a variety of built-in transformations for common data manipulation tasks, such as filtering, mapping, and aggregating data.


Set Up
1.	Create a bucket
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230790630-c545c62d-b8d9-4a8e-aaaf-42a33e01f9a0.png">
	
	<img width="588" alt="image" src="https://user-images.githubusercontent.com/64408106/230790719-6571d718-b9a8-4316-9f67-9c034f5e4605.png">
	
	Need to create sub-folder data,script and temp-dir
	script folder contains the python script and temp-dir is use to Glue to process thier items
	<img width="350" alt="image" src="https://user-images.githubusercontent.com/64408106/230790883-a356b875-b0f1-4428-9b15-b3424e6c1f12.png">



	a.	Open IAM role and create the IAM role for the EMR notebook using the emr notebook role json
	
	b.	Need to attach AmazonElasticMapReduceEditorsRole policy

	c.	Attached AmazonS3FullAccess policy(can change dependent on needs)
	
	d.	Attached AmazonS3FullAccess policy

2.	Create EMR Serverless Execution Role

	a.	Open IAM and create the IAM role for the EMR Servlerless Execution using emr serverless role
	
	b.	Attach policy for permisions
	
3.	Create S3 bucket

	a.	Open S3 console
	
	b.	create S3 bucket to use for the demo

4.	Create Folder To use in S3 Bucket

	a.	Create a scripts folder
	
	b.	Create a customers folder (We use this to upload a CSV to)
	
	c.	Create a query-results folder
	
	d.	Upload files to folders










