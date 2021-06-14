# Cloud_Resume
Instructions:
[] AWS CLOUD PRACTITIONER Certification: This should be added to the resume
[] HTML: Create a resume static website
[] CSS: Use this to add styling to the website
[] S3: The HTML resume should be deployed online as an Amazon S3 static website
[] HTTPS: The S3 website URL should be a secured site, I will need to use Amazon Cloudfront to help with this
[] DNS: Point a custom DNS domain name to the Cloudfront distribution
[] Javascript: The resume webpage should include a visitor counter that displays how many people accessed the site
[] Database: The visitor counter will need to retrieve and update its count in a database
[] API: Create an APT that accepts requests from your web app and communicates with the database (API Gateway & Lambda)
[] Python: Write a bit of code in the Lambda function
[] Tests: Create some tests for your Python code
[] Infrastructure as Code: Use automation to configure your API resources – the DynamoDB table, the API Gateway, the Lambda function
[] Source Control: Create a continuous integration and deployment, or CI/CD automated pipeline, create a private Github repo for your backend code
[] CI/CD (Back end): Set up GitHub Actions such that when you push an update to your Serverless Application Model template or Python code, your Python tests get run
[] CI/CD (Front end): Create a second private GitHub repository for your website code. Create GitHub Actions such that when you push new website code, the S3 bucket automatically gets updated  *Important note: DO NOT commit AWS credentials to source control! Bad hats will find them and use them against you!*