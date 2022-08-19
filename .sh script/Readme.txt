.sh script to create 
- S3 bucket
- dynamodb table 

to store state file of terraform script
dynamodb table maintains state-lock while s3 bucket stores .tfstate file.
