![image](https://github.com/harsh-learner/Project-End-to-End-CI-CD-Automation-with-Argo-CD-/assets/141729189/108b7c5f-6ae6-4f4a-a69b-12bb219cb073)
![my_endproject drawio(1)_473c4634](https://github.com/harsh-learner/Project-End-to-End-CI-CD-Automation-with-Argo-CD-/assets/141729189/f292057d-03d8-4691-996e-2bd248dca4e8)
















**Project**: "End-to-End CI/CD Automation with Argo CD"

**Role**: DevOps Engineer

**Description**:

- Designed and implemented an end-to-end Continuous Integration/Continuous Deployment (CI/CD) pipeline for a Java application.
- Orchestrated the entire development and deployment process to ensure rapid and reliable software delivery, leveraging Jenkins, Docker, Maven, **SonarQube**, Git, Kubernetes, and Argo CD.
- **Automated** code analysis, Docker image creation, and **Kubernetes** deployment, significantly reducing manual interventions.
- Integrated **Argo CD** for GitOps-style continuous delivery, enabling declarative, version-controlled application deployments.
- Collaborated with cross-functional teams to ensure seamless integration and delivery.
- Achieved substantial improvements in code quality, deployment speed, and infrastructure scalability.

**Notable Achievements**:
- Reduced deployment time by **30%** through effective automation and optimization.
- Successfully integrated SonarQube for static code analysis, enhancing overall code quality.
- Implemented Docker containerization and Kubernetes orchestration for **scalable** and portable applications.
- Established a GitOps workflow using Argo CD, ensuring consistent and auditable deployments.

**Technologies Used**:
- Jenkins, Docker, Maven, SonarQube, Git, Kubernetes, Argo CD, Groovy scripting, Docker Hub.


**Steps**:

1. **Install the necessary Jenkins plugins**:
   - 1.1 Git plugin
   - 1.2 Maven Integration plugin
   - 1.3 Pipeline plugin
   - 1.4 Kubernetes Continuous Deploy plugin

2. __Create a new Jenkins pipeline__:
   - 2.1 In Jenkins, create a new pipeline job and configure it with the Git repository URL for the Java application.
   - 2.2 Add a Jenkinsfile to the Git repository to define the pipeline stages.
     
3. __Define the pipeline stages__:
    - Stage 1: Checkout the source code from Git.
    - Stage 2: Build the Java application using Maven.
    - Stage 3: Run unit tests using JUnit and Mockito.
    - Stage 4: Run SonarQube analysis to check the code quality.
    - Stage 5: Package the application into a JAR file.
    - Stage 6: Deploy the application to a test environment using Helm or Kubernetes manifests.
    - Stage 7: Run user acceptance tests on the deployed application.
    - Stage 8: Promote the application to a production environment using Argo CD.

4. __Configure Jenkins pipeline stages__:
    - Stage 1: Use the Git plugin to check out the source code from the Git repository.
    - Stage 2: Use the Maven Integration plugin to build the Java application.
    - Stage 3: Use the JUnit and Mockito plugins to run unit tests.
    - Stage 4: Use the SonarQube plugin to analyze the code quality of the Java application.
    - Stage 5: Use the Maven Integration plugin to package the application into a JAR file.
    - Stage 6: Use the Kubernetes Continuous Deploy plugin to deploy the application to a test environment using Helm or Kubernetes manifests.
    - Stage 7:Use Argo CD to promote the application to a production environment.
      ![credentials](https://github.com/harsh-learner/Project-End-to-End-CI-CD-Automation-with-Argo-CD-/assets/141729189/cfc2dc0b-6dab-4e70-8651-ae237844b857)



    

5. __Set up Argo CD__:
    - Install Argo CD on the Kubernetes cluster.
    - Set up a Git repository for Argo CD to track the changes in the Helm charts and Kubernetes manifests.
    - Add the Helm chart or Kubernetes manifests to the Git repository that Argo CD is tracking.
      ![argo-cd status](https://github.com/harsh-learner/Project-End-to-End-CI-CD-Automation-with-Argo-CD-/assets/141729189/1477347d-5a6f-4c02-904b-686e5d48dcfc)
      ![deployment-manifest](https://github.com/harsh-learner/Project-End-to-End-CI-CD-Automation-with-Argo-CD-/assets/141729189/b705956c-511c-4208-82d9-4807b2b35eb9)




6. __Run the Jenkins pipeline__:
   - 7.1 Trigger the Jenkins pipeline to start the CI/CD process for the Java application.
   - 7.2 Monitor the pipeline stages and fix any issues that arise.
     ![jenkins-updated](https://github.com/harsh-learner/Project-End-to-End-CI-CD-Automation-with-Argo-CD-/assets/141729189/6e8cf194-e8a8-455c-bcbc-98c49966f9b5)
     

