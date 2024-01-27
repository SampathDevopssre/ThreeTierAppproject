
Welcome to ThreeTierAppToDo, where CI/CD meets enchantment! This project orchestrates a seamless CI/CD pipeline for a 3-Tier TODO application. With Jenkins, Docker, Kubernetes, and more

### Technologies List:

AWS (Amazon Web Services)
Cloud infra creation: Terraform
Jenkins:
SonarQube 🕵️: Code detective, sniffing out issues in our project
OWASP Dependency-Check and Trivy 🕵️‍♂️: Security guard duo inspecting our dependencies
Docker :
Kubernetes (EKS) 
ArgoCD 
rometheus and Grafana

### Technologies Used in This Project:

### AWS (Amazon Web Services):

``` Purpose: AWS provides the infrastructure for hosting our EC2 instance, EKS cluster, and ECR repositories. Leveraging AWS services ensures scalability, reliability, and seamless integration with other tools.```

### Terraform:

```Purpose: Terraform is employed for infrastructure as code (IaC), enabling the automated provisioning and management of AWS resources. This ensures consistency in our environment and simplifies the setup of the Jenkins server. ```

### Jenkins:

``` Purpose: Jenkins serves as the backbone of our CI/CD pipeline. It automates the build, test, and deployment processes, enhancing collaboration and efficiency among development teams.```

### Docker:

``` Purpose: Docker facilitates containerization, encapsulating application code and dependencies. This ensures consistency across different environments, easing deployment and minimizing compatibility issues.```

### Kubernetes (EKS):

``` Purpose: Kubernetes orchestrates containerized applications, providing scalability and resilience. EKS (Elastic Kubernetes Service) simplifies the deployment and management of Kubernetes clusters on AWS.``

### ArgoCD:

``` Purpose: ArgoCD automates the deployment of applications in Kubernetes. It ensures consistency between the desired and actual state of applications, promoting continuous delivery in a Kubernetes environment.```

### Prometheus and Grafana:

``` Purpose: Prometheus monitors Kubernetes clusters, collecting metrics and alerts. Grafana visualizes these metrics, providing insights into the system's health and performance, crucial for maintaining reliability.```

### SonarQube:

``` Purpose: SonarQube performs static code analysis, identifying and fixing code quality issues early in the development process. This enhances code maintainability, security, and overall software quality.```