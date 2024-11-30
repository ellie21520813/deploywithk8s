# k8s-microservices-cicd
1. Prerequisites
Install Docker
Install Kubernetes: Minikube, kubectl
Install Jenkins 
Install sonarQube
Install Java
2. Project Structure
Backend
Frontend
K8s: Contains Kubernetes manifests for deploying the application
JenkinsFile: Pipeline configuration for automating the build, test, and deployment process using Jenkins.
3. Project steps
    - Lauching EC2 and setup rule accept all traffic
    - Install Required Tools
    - run Jenkins server and setup for Pipeline 
    - run sonarQube and create token for connect with Jenkins
    - setup tools such as maven, sonarQube, k8s, git, docker in Jenkins server
    - Connect Jenkins with k8s server in EC2
    - Connect Jenkins with  Docker in  EC2
    - Connect Jenkins with sonarQube server
    - run Pipeline