# EMR Serverless

# Set Up
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

# EMR Serverless Creation Process

![emr_1](https://user-images.githubusercontent.com/64408106/230758360-4824c1b8-06a6-4c6a-ac04-c2393ce0bd3b.jpg)

![emr_2](https://user-images.githubusercontent.com/64408106/230758373-542e3a01-bfac-4edc-8c8e-f9ad7f46f633.jpg)

![emr_4](https://user-images.githubusercontent.com/64408106/230758384-25099fdc-43cb-465c-a11f-8052051b2caf.jpg)

![emr_5](https://user-images.githubusercontent.com/64408106/230758393-f9545ea1-4827-4985-8734-6fd73a16f387.jpg)

![emr_6](https://user-images.githubusercontent.com/64408106/230758409-e6d34768-1d9a-4192-b4bd-3db7a3d0a54e.jpg)

![emr_7](https://user-images.githubusercontent.com/64408106/230758430-50f83861-c389-4984-ab15-27a397d82012.jpg)

![emr_8](https://user-images.githubusercontent.com/64408106/230758441-f432ef12-a666-474c-a909-816601964f9e.jpg)











