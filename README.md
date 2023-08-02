# Amazon-AWS
## Find this link which  may helpful https://www.datacamp.com/tutorial/aws-ec2-beginner-tutorial

When it comes to deployments on AWS, each service you mentioned has its own purpose and plays a role in different aspects of your application. Let's discuss the deployment options for each service:

EC2 (Elastic Compute Cloud): EC2 provides virtual servers in the cloud, giving you full control over the infrastructure. With EC2, you can deploy your applications on virtual machines, which allows for a high level of customization. You can choose the operating system, install any software you need, and configure the environment to suit your requirements. However, deploying applications on EC2 involves more manual setup and management compared to other services.

S3 (Simple Storage Service): S3 is a scalable object storage service. While S3 is not typically used for deploying applications directly, it is commonly used for storing static assets, such as images, videos, and files, which can be served by web applications running on other services like EC2 or Lambda.

RDS (Relational Database Service): RDS offers managed relational databases, such as MySQL, PostgreSQL, or Oracle. When deploying applications that require a relational database, RDS simplifies the management tasks associated with database administration, such as backups, patching, and scaling. You can deploy your application on other services like EC2 or Lambda and connect to the RDS database for data storage.

Lambda: AWS Lambda is a serverless compute service that allows you to run code without provisioning or managing servers. It is an event-driven service where you upload your code, and Lambda automatically scales it in response to incoming events. Lambda is particularly useful for small functions or microservices that can run independently. Deploying with Lambda eliminates the need to manage infrastructure and provides automatic scalability.

The choice of deployment option depends on your specific requirements. If you require full control over the infrastructure and need to customize the environment, EC2 might be the best choice. If you have a small function or microservice that needs to scale automatically, Lambda can be a good option. For storing static assets, S3 is a reliable choice, and for managed relational databases, RDS simplifies database administration.

In some cases, you might use a combination of these services for different components of your application. AWS provides various tools and services to assist with deployment, such as AWS Elastic Beanstalk, AWS CloudFormation, and AWS CodeDeploy, which can help automate the deployment process and integrate with the services mentioned above.

## Deployments:
1. login to Amazon EWS
2. select region as Mumbai ( Your nearest region )
3. In search Bar click on EC2.
4. click on instance at the left and click on launch button.
5. Select UBUNTU
6. Use x86
7. Select t2.micro free tire eligible.
8. Create a new key pair.
9. Use private key format as .ppk if you are using windows.( Below windows 9 users espessially). If you have pem then you need to convert pem to .ppk
10. In Firewall select all 3 options

### Run instance and click on connect to run
