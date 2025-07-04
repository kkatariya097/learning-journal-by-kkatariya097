## What is CI/CD?

![image](https://github.com/user-attachments/assets/b100cd25-1af5-49f0-9964-920df60c6154)

**<ins>CI/CD stands for Continuous Integration and Continuous Deployment (or Continuous Delivery).</ins> It is a set of practices and methodologies aimed at automating and streamlining the software development lifecycle, from code changes to production deployment.**

### **Continuous Integration (CI):** 
CI is the practice of frequently and automatically integrating code changes from multiple developers into a shared repository. It involves building and testing the code changes to identify integration issues, conflicts, and bugs as early as possible. 

**Key aspects of CI include:**

1. **Code Repository:** Developers commit their code changes to a central version control repository, such as Git.

2. **Automated Build:** An automated build process is triggered whenever changes are pushed to the repository. The code is compiled, dependencies are resolved, and build artifacts are generated.

3. **Automated Testing:** Various types of tests, including unit tests, integration tests, and other automated tests, are executed to verify that the code changes function correctly and meet the defined quality criteria.

4. **Early Feedback:** CI provides fast feedback to developers by quickly identifying issues and conflicts, allowing them to resolve problems promptly.


In simple words: CI =
-  Build  
-  Run Unit Test  
-  Package  
-  Run Integration Test  


### **Continuous Deployment/Delivery (CD):** 
CD extends CI by automating the process of deploying software to production or other environments. It focuses on the efficient and reliable delivery of software changes. 

**Key aspects of CD include:**

1. **Deployment Automation:** The process of deploying software to different environments, such as staging or production, is automated. This includes tasks like configuring servers, deploying applications, and setting up infrastructure.<br>

2. **Release Management:** CD involves managing the release process, including versioning, release note generation, and coordination with stakeholders.<br>

3. **Environment Consistency:** CD ensures that the deployment process is consistent across different environments, reducing the risk of configuration errors or inconsistencies.<br>

4. **Continuous Monitoring:** CD promotes the monitoring of deployed applications to detect and respond to issues promptly, ensuring smooth operation in production.

In Simple words, CD=
-  Deploy to Test  
-  Run Acceptance Tests  
-  Deploying to Staging  
-  Run Performance Tests  
-  Run End-to-End Tests  
-  Deploy to PROD  
   
**The primary goal of CI/CD is to enable development teams to deliver high-quality software more efficiently and frequently. By automating tasks like building, testing, and deployment, CI/CD practices help reduce manual effort, improve collaboration among team members, shorten feedback loops, and enable faster and more reliable software releases. It fosters a culture of continuous improvement, allowing teams to iterate and release new features or bug fixes in a continuous and controlled manner.**

## Tools for CI/CD 

-  ⭐️ **[Jenkins](https://www.jenkins.io/) — Most popular and widely used**
-  [Azure Pipeline](https://azure.microsoft.com/en-us/products/devops/pipelines)
-  [Tekton Pipeline](https://tekton.dev/)
-  [Travis CI](https://www.travis-ci.com/)
-  [Screwdriver](https://screwdriver.cd/)
-  [GoCD](https://www.gocd.org/index.html)
