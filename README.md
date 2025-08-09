# automated-receipt-processing-using-AWS
This will create an AWS database of all your receipts, by simply uploading them.

Here's the AWS architecture:
AWS S3 to store digital uploads of the receipts
AWS Textract, an AI tool that will read the receipts
AWS Dynamo DB to organize the data
AWS SES to send summaries
AWS Lamda to automate and bring the whole thing together.
AWS IAM to access all the roles
