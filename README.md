# Zomato-Clone DevSecOps CI/CD

## Project Architecture
<img src="https://github.com/swaleham/Zomato-Clone/blob/main/ZomatoClone.svg">

### Steps:
1. Launch an Ubuntu instance(t2.large, increase the RAM to 10).
2. Install Jenkins, Docker and Trivy on the instance.
3. Create a Sonarqube Container using Docker.
4. Install Plugins like JDK, Sonarqube Scanner, Nodejs, and OWASP Dependency Check.
5. Create a Pipeline Project in Jenkins using a Declarative Pipeline.Write pipeline script.
6. Build a docker image from docker file and push it to DockerHub.
7. Deploy the image using Docker.
8. Terminate the AWS EC2 Instances.

### End to End CI/CD pipeline
<img src="https://github.com/swaleham/Zomato-Clone/blob/main/CICD-stages.png">

### Sonarqube code quality checks
<img src="https://github.com/swaleham/Zomato-Clone/blob/main/sonarquberesults.png">

### OWASP Dependency check
<img src="https://github.com/swaleham/Zomato-Clone/blob/main/Dp-report.png">
