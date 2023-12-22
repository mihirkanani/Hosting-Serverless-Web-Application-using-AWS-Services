Objective:

The goal of this project is to showcase proficiency in AWS services by creating a full end-to-end web application using various AWS tools. This project will not only demonstrate technical skills but also serve as a portfolio piece, strategically aimed at reaching hiring managers and potential employers on LinkedIn.

[
![architecture](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/dff645a0-abef-455d-8bbf-2848b4717fd2)
](url)


Project Outline:

1. AWS CodeCommit:
Generate a new repository on AWS CodeCommit to host the source code for the web application.
Set up the necessary branching strategy (e.g., develop, main).

![codecommit](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/6c0a4764-8392-4e5b-a2f4-0779884abddf)

![codecommit 2](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/2a8a8dda-8981-4a7a-afff-045a7f78ebae)


3. Amazon IAM:
Create an IAM user specifically for CodeCommit with the required permissions.
Configure access credentials for the IAM user.

![iam](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/4416ae23-3a27-4c41-bc60-070e50204558)


3. Amazon CloudShell:
Utilize Amazon CloudShell to access the AWS environment.
Clone the CodeCommit repository to the CloudShell environment.
Copy a sample website from an S3 bucket to the CodeCommit repository.
Commit and push the changes to the CodeCommit repository.

5. Amazon Amplify:
Create an Amplify app linked to the CodeCommit repository.
Configure the build settings for the web application.
Deploy the web application using Amplify.

![amplify 2](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/8afa7fcf-e43f-4011-87f8-7450d1386b0c)


5. Amazon Cognito:
Configure Amazon Cognito for user authentication in the web application.
Integrate Cognito with the Amplify app for secure user authentication.

![cognito](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/af57c736-b519-4ce5-8405-f49b3a5f82b9)


7. Amazon DynamoDB:
Create a DynamoDB table to store user account information.
Define the necessary attributes for user accounts.
Implement Lambda functions to interact with DynamoDB for CRUD operations.

![dynamodb](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/724df70f-97e8-4e0f-a990-4a27df5898de)


9. Amazon API Gateway:
Create an API Gateway to manage and expose Lambda functions.
Integrate API Gateway with Lambda functions to handle user requests.
Secure API Gateway using Cognito authentication.

![authentication success](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/55416c43-8b1f-4fac-af8b-5871ead46e4a)

![output](https://github.com/mihirkanani/Hosting-Serverless-Web-Application-using-AWS-Services/assets/70439380/01edfe52-b758-4768-a9ba-d392ded4939a)



#AWS #WebDevelopment #CloudComputing #AWSCodeCommit #AmazonAmplify #AmazonCognito #DynamoDB #APIGateway #LinkedInProject #TechPortfolio

This project not only demonstrates technical skills but also showcases the ability to integrate multiple AWS services into a cohesive and functional web application. It is designed to catch the attention of hiring managers looking for candidates with hands-on experience in cloud development.
