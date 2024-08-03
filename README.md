# JAVA WEBSITE CI/CD PIPELINE PROJECT

## Description

**DEVOPS CI/CD PIPELINE PROJECT.**
This project demonstrates the implementation of a CI/CD pipeline for a Java-based website. The pipeline automates the process of building, testing, analyzing, and deploying the application. It begins by retrieving the latest code from the GitHub repository. Next, Maven is utilized to compile the project and run unit tests, ensuring the code is functional and reliable. SonarQube then performs a thorough code quality analysis, generating detailed reports on any issues found. Following this, a Docker image of the application is created and subsequently scanned with Trivy to identify potential vulnerabilities. Once the Docker image passes the security scan, it is pushed to a Docker container registry. The final deployment stage involves deploying the application to a Kubernetes cluster. To keep the team informed, an email notification is sent upon successful deployment. This CI/CD pipeline leverages GitHub Actions to automate each step, ensuring a streamlined, efficient, and secure development process.

## Technologies

- Amazon Web Services(AWS) EC2
- CI/CD
- Jenkins
- Kubernetes
- SonarQube
- Docker
- Trivy
- Maven
