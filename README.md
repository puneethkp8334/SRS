#Assessment for SRS Business Soution

Tools & Solutions to use:  GIT,Dockers,K8, AWS, DB, JENKINS, Terraform, Microservices, Others

 

1)Use Public GITHUB store your demo Microservices web application code. At least have min 2 microservices in the application. (Can use GO or Python or JAVA)
2)RDBMS or any SQL DB Is must in your application your microservices access.
3)Build your Microservice based Demo Application using JENKINS when code commit triggered from GIT Repository.
4)Run few automated tests in JENKINS pipeline
5)Create Docker Image in the JENKINS pipeline and store it in AWS ECR or Docker hub
6)Build AWS EC2,RDS, ALB, CF and other resources needed to run your microservice application. Use Terraform or cloud formation to build the infrastructure VIA Jenkins.  Provision right IAM Roles and polices.
7)The microservice need to run in a Kubernetes based environment K8 or AWS EKS or others.
8)Once K8 Environment is up and running deploy the latest version of application into the K8 Cluster as PODS in a namespace – Use Jenkins + other available tools.
9)Demo scaling up and down of application PODS.
10)Demo your microservices application working via web URL.
