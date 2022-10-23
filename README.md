# Deploy Static Website on AWS

This is the first project of Cloud Developer Nanodegree Project. In this project, I deployed a static website to AWS using S3 bucket, 
CloudFront, and IAM policies.

## Steps Performed:
    I created a public S3 bucket and uploaded the website files to my bucket.
    I configured the bucket for website hosting and secured it using IAM policies.
    I sped up content delivery using AWS’s content distribution network service, CloudFront.
    I accessed the website in a browser using the unique CloudFront endpoint.

## Prerequisites:
    AWS Account
    Student-ready starter code - Download and unzip this file.

## Topics Covered:
    S3 bucket creation
    S3 bucket configuration
    Website distribution via CloudFront
    Access website via web browser

## Dependencies
### Cloud Services
    Amazon Web Services S3 - Resource hosting and deployments
    AWS CloudFront - CDN for SPA
    AWS EKS - Backend API
    AWS DynamoDB - Persistent Datastore
    AWS Cognito - User Authentication
### Performance Tracking and DevOps Tools:
    AWS CloudWatch - Performance and Health checks
    Sentry - Bug Reporting
        Alternates:
        TBD
    Google Analytics - Usage Reporting
        Alternates:
        Mixpanel
    Travis (CI/CD)
### Frameworks:
    Ionic (Javascript) (Frontend)
    Node.js (Javascript) (Backend)

### The website files included are: 
    index.html - The Index document for the website.
    /img - The background image file for the website.
    /vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
    /css - CSS files for the website.

### After deploying the website, it could be accessed with the following URL:

    https://d11itkvn9gha2s.cloudfront.net/
    http://my-864942481424-bucket.s3-website.us-east-1.amazonaws.com/
    https://my-864942481424-bucket.s3.amazonaws.com/index.html

### Screenshots of deployment process can be found in th screenshots folder.




