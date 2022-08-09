#Assessment for SRS Business Soution

Tools & Solutions to use:  GIT,Dockers,K8, AWS, DB, JENKINS, Terraform, Microservices, Others

 

Use Public GITHUB store your demo Microservices web application code. At least have min 2 microservices in the application. (Can use GO or Python or JAVA)
RDBMS or any SQL DB Is must in your application your microservices access.
Build your Microservice based Demo Application using JENKINS when code commit triggered from GIT Repository.
Run few automated tests in JENKINS pipeline
Create Docker Image in the JENKINS pipeline and store it in AWS ECR or Docker hub
Build AWS EC2,RDS, ALB, CF and other resources needed to run your microservice application. Use Terraform or cloud formation to build the infrastructure VIA Jenkins.  Provision right IAM Roles and polices.
The microservice need to run in a Kubernetes based environment K8 or AWS EKS or others.
Once K8 Environment is up and running deploy the latest version of application into the K8 Cluster as PODS in a namespace – Use Jenkins + other available tools.
Demo scaling up and down of application PODS.
Demo your microservices application working via web URL.
