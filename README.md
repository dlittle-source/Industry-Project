**Project: Deploy a Java-based Address Book application**

**Project Overview:** This project showcases the implementation of a CI/CD pipeline utilizing a range of DevOps tools, including AWS EC2, AWS ECR, Git & GitHub, Ansible, Terraform, SonarQube, Nexus, Maven, Docker, EKS (Kubernetes), and Jenkins:

**Deployment Steps**:

1. **Jenkins Implementation**:
   - Set up and configured the Jenkins server on an AWS EC2 instance using a vendor-provided script. Installed essential DevOps tools, including Terraform, Docker, Kubernetes, and Git, on the same server. Added Maven tools and configure the AWS plugin with secure credential management using access keys.
  
2. **Terraform Implementation**:
   - Created a pipeline script using pipeline syntax to deploy three AWS EC2 servers: SonarQube, Nexus, and a testing server.
   - Set up and configured the SonarQube server for continuous code quality and security analysis, integrated the SonarQube plugin with Jenkins, and set up secure authentication by generating a token.
