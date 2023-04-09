AWS Glue

AWS Glue is a serverless ETL tool.AWS Glue is a serverless data integration service that makes it easier to discover, prepare, move, and integrate data from multiple sources for analytics, machine learning (ML), and application development.

AWS Glue is a fully managed ETL (extract, transform, and load) AWS service. One of its key abilities is to analyze and categorize data. You can use AWS Glue crawlers to automatically infer database and table schema from your data in Amazon S3 and store the associated metadata in the AWS Glue Data Catalog.

Set Up
1.	Create EMR Notebook Role

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










