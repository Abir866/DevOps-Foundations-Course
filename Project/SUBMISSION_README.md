## Multi-Container Docker Application with CI/CD: Calculator App Project

#### Complete Project Instructions: [DevOps Foundations Course/Project](https://github.com/shiftkey-labs/DevOps-Foundations-Course/tree/master/Project)

#### Submission by - **Toufiq Abir Farhan Tufan **

### Project Overview

- **Brief project description:** What is the purpose of your application?

<!-- To test workflow -->
<!-- To utilize microservices to perform calculations-->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


- **Which files are you implmenting? and why?:**

<!-- devops.yml - to create a workflow for automating CI/CD -->
<!-- Docker to create images for containers-->




- _**Any other explanations for personal note taking.**_

<!--None-->



### Docker Implementation

**Explain your Dockerfiles:**

- **Backend Dockerfile** (Python API):
    - Here please explain the `Dockerfile` created for the Python Backend API. 
    - This can be a simple explanation which serves as a reference guide, or revision to you when read back the readme in future. 

<!-- Starts it a base image of python runtime -->
<!-- Adds required dependencies to run the code files in a created working dictorectory-->
<!--  gather all the code to run in that directory before running app.py and exposing the container port 5000 ready to be mapped -->


- **Frontend Dockerfile** (React App):
    - Similar to the above section, please explain the Dockerfile created for the React Frontend Web Application. 

<!-- Start with installing avalable image of javascript run-time environment -->
<!-- Installs dependecies to the image for excuting commands that run the front code starting from building to testing. -->
<!-- Everythings gathered to working directory before the code files are used to buld and test-->


**Use this section to document your choices and steps for building the Docker images.**


### Docker Compose YAML Configuration

**Break down your `docker-compose.yml` file:**

- **Services:** List the services defined. What do they represent?
- **Networking:** How do the services communicate with each other?
- **Volumes:** Did you use any volume mounts for persistent data?
- **Environment Variables:** Did you define any environment variables for configuration? 

**Use this section to explain how your services interact and are configured within `docker-compose.yml`.**

<!-- Forntend  and Backend service. They are containerized applications -->
<!-- via host network -->
<!-- No-->
<!-- No -->



### CI/CD Pipeline (YAML Configuration)

**Explain your CI/CD pipeline:**

- What triggers the pipeline (e.g., push to main branch)?
- What are the different stages (build, test, deploy)?
- How are Docker images built and pushed to a registry (if applicable)?

**Use this section to document your automated build and deployment process.**

<!-- Github pull and push from and to master branch-->
<!-- build , test , docker -->
<!-- images are built by running the docker files  in the Github runner via docker install and then pushed to the dockerhub via envronment variables saved in github that contains user name and password to the docker hub account which is available in the runner and can be access in the workflow -->

<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->




### Assumptions

- List any assumptions you made while creating the Dockerfiles, `docker-compose.yml`, or CI/CD pipeline. 

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### Lessons Learned

- What challenges did you encounter while working with Docker and CI/CD?
- What did you learn about containerization and automation?

**Use this section to reflect on your experience and learnings when implementing this project.**

<!-- Learned more in the project and I came to know I need to learn during the exam-->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### Future Improvements

- How could you improve your Dockerfiles, `docker-compose.yml`, or CI/CD pipeline? 
- (Optional-Just for personal reflection) Are there any additional functionalities you would like to consider for the calculator application to crate more stages in the CI/CD pipeline or add additional configuration in the Dockerfiles?

**Use this section to brainstorm ways to enhance your project.**

<!-- I will make it a Quantum Calculator -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->






<!-- BEST OF LUCK! -->
