# **CI/CD Java Spring Boot Application 🚀**

**Developed & Maintained Automated CI/CD WorkFlows of the Java Based Spring Boot Web Application. By Using the Jenkins & Open Soruce Tools.** 
🧑
## **Tech Stack:-🧑‍🚀**
***Following are the tools which are using in this project:-***

- **Jenkins**
- **SonarQube** 
- **Nexus**
- **Docker**
- **Kubernetes**
- **Helm Charts**
- **Gradle**
- **Datree**

## **Description:- 👻**
When the Developer Commit the Code in the Version Control System Which is **Git** in our Case.
It Triger the Code by using GitHub Actions and Jenkins Pipeline. Our Second Stage to build the code by using the build tools **Gradle** & with the command ***./gradlew build*** .Also Integrated the webhooks which notify the developer about the
pipeline by using slack channels and emails. Our Second Stage is to analyse the Code by using 
the Sonar Qube with the help of Quality Gates. At last, I Containerized the application by using multistage Docker File in which at first docker build the application and at second it generate the war file on the tomcat based image. Integrated nexus to store all the artefacts of docker images and Helm charts. In the End I deployed application on Kubernetes with the help of Datree plugin to prevent the misconfiguration.
