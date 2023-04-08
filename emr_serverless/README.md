EMR Serverless

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



