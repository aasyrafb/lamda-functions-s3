# lamda-functions-s3

Given a Lambda function that is triggered upon the creation of files in an S3 bucket, answer the following:
1. What is the purpose of the execution role on the Lambda function?
The execution role gives permsission to Lamda function also to access other AWS services, example like writing logs in CloudWatch.
2. What is the purpose of the resource-based policy on the Lambda function?
is to trigger or invoke the Lamda Functions.
3. If the function is needed to upload a file into an S3 bucket, describe (i.e no need for the actual policies)
   - What is the needed update on the execution role? update the execution role, can add permision to upload files to S3 bucket. eg: s3:PutObject
   - What is the new resource-based policy that needs to be added? To which resource? added through S3 bucket which allows the Lamda funtion's role to upload file.

Create a public github repository that has a README.md file, containing the above answers.

Submission is the url to your public github repository.