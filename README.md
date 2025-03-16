Project – Azure 204/400 
Scenario: Cloud-Based eCommerce Application 
You have been hired by a company called "TechShop" that operates an eCommerce 
platform for selling electronics online. The company wants to modernize its infrastructure by 
moving parts of their platform to Azure. Your task is to implement various Azure services to 
build, deploy, and monitor the cloud-based components for their online store. 
Assignment Objectives: 
• Develop and deploy cloud-based applications using Azure. 
• Work with Azure App Services, Azure Functions, and Azure Storage. 
• Implement monitoring, logging, and diagnostics using Azure Monitor. 
• Integrate security features in the cloud application. 
• Use Azure DevOps for deployment automation. 
Scenario Description: 
Background: TechShop’s eCommerce platform is currently running on-premise and relies 
heavily on a monolithic architecture. Due to increased traffic, the company is facing 
scalability issues and performance bottlenecks. They aim to redesign the system using cloud
native technologies to improve scalability, reliability, and performance. 
You will be required to design and implement the following cloud-based solution for 
TechShop’s application: 
1. Web Application Hosting 
TechShop wants to migrate their customer-facing website to the cloud using Azure App 
Service. The website includes a product catalog, shopping cart, and checkout pages, which 
need to be served to customers worldwide. 
• Task: Set up an Azure App Service for the eCommerce web application. 
o Deploy the web application to Azure App Service. 
o Configure deployment slots (production, staging). 
o Set up custom domain and SSL certificates for secure communication. 
2. Backend API Development 
TechShop wants to develop a set of RESTful APIs to manage products, user accounts, and 
orders. These APIs should be developed using Azure Functions and be able to scale 
automatically based on demand. 
• Task: Develop an Azure Function App for managing the backend APIs: 
o Create functions for handling product listings, customer orders, and user 
authentication. 
o Set up API management for secure access and monitoring. 
AZ-204/400 Project 
o Implement an Azure Key Vault to securely store sensitive credentials such as 
API keys. 
3. Data Storage 
The application needs to store and manage user data, product information, and order history. 
TechShop wants to use Azure Storage and Azure SQL Database for persistent storage. 
• Task: 
o Set up Azure SQL Database for storing transactional data like orders, users, 
and inventory. 
o Configure an Azure Blob Storage container to store product images and other 
static content. 
o Implement an efficient way to retrieve and store product data and images. 
4. Scalability and Load Balancing 
TechShop needs to ensure the application scales based on traffic patterns. The eCommerce 
platform should automatically scale to accommodate sudden traffic surges (e.g., during sales 
events). 
• Task: Configure Azure App Service scaling and set up an Azure Load Balancer to 
ensure high availability for your APIs. 
o Implement auto-scaling for the Azure App Service. 
o Use Azure Traffic Manager to distribute traffic across multiple instances or 
regions. 
5. Logging and Monitoring 
TechShop wants to monitor application performance and gather usage data. They also need to 
log user activities such as login events, product views, and order processing for auditing 
purposes. 
• Task: Implement logging and monitoring: 
o Set up Azure Monitor and Application Insights for monitoring application 
health and performance. 
o Configure logging for Azure Functions and App Services to capture detailed 
telemetry data. 
o Set up Azure Log Analytics to track and analyze user activity and application 
logs. 
6. Security Implementation 
TechShop wants to ensure that their application is secure from various types of attacks. They 
require secure authentication, data encryption, and access control mechanisms. 
• Task: 
o Implement Azure Active Directory (Azure AD) for user authentication and 
authorization. 
AZ-204/400 Project 
o Configure OAuth2 for external authentication (e.g., Google, Facebook). 
o Encrypt sensitive data at rest and in transit using Azure Key Vault and Azure 
Storage Encryption. 
7. DevOps and Continuous Integration/Continuous Deployment (CI/CD) 
TechShop wants to automate the deployment process for faster development and production 
cycles. They need you to set up an automated CI/CD pipeline to deploy changes to their web 
application and APIs. 
• Task: Set up an Azure DevOps pipeline: 
o Create a build pipeline for compiling and testing the code. 
o Create a release pipeline to deploy the application to Azure App Service, with 
approval gates for production deployment. 
o Configure notifications for build and release success or failure. 
Deliverables: 
1. Azure Resource Setup: 
o Azure App Service setup for the web application. 
o Azure Functions and API Management configuration. 
o Azure SQL Database and Blob Storage setup. 
o Load balancer and scaling configurations. 
o Key Vault and security settings for sensitive data storage. 
2. Codebase: 
o Source code for the backend APIs (Azure Functions). 
o Code for web application (e.g., React, Angular, or any web technology). 
o Documentation on how the APIs interact with the Azure services. 
3. CI/CD Pipeline: 
o Azure DevOps pipeline YAML files. 
o Setup documentation for the automated build and release process. 
4. Monitoring and Logging Configuration: 
o Configuration for Azure Monitor, Application Insights, and Log Analytics. 
o Sample logs and monitoring reports. 
5. Security Configuration: 
o Azure AD configuration for authentication. 
o Documentation on encryption and key management using Azure Key Vault.
