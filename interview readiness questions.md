This criterion is linked to a Learning OutcomeInterview Readiness
#### Q1) What does it mean to create a Docker image and why do we use Docker images?

creating a Docker image means that we are creating a unit of software that packages all of our code for our ml app or other application. We use Docker Images because it allows for reproducibility for the program but also allows for users of different OS to run the code the same. Containers are also very secure and it is easy to maintain with tagging and images can we rebuilt easily with Dockerfiles.

#### Q2) Please explain what is the difference from a Container vs a Virtual Machine?

Containers run fast, it is often a different OS that is being installed to your machine, and inside the VM we would still need to maintain enviornments based on different projects. With Containers we would be able to isolate each containerized project and can run code on different objects.

### Q3) What are 5 examples of container orchestration tools (please list tools):
      1. Kubernetes 
      2. Openshift
      3. Docker Swarm 
      4. Mesos 
      5. Azure AKS Service
      
### Q4) How does a Docker image differ from a Docker container?:

A Docker images contains everything that we would need to run our program and a docker container is an enviornment where we run the docker image.
