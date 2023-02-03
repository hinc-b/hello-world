# DevOps Project

CI/CD with GitHub, Jenkins, Maven, Tomcat, Ansible, Docker and Kubernetes.

## Main purpose
To learn how to combine "DevOps" toolkit together in a CI/CD pipeline.

- [x] Firstly - how to deploy artifacts on Tomcat Server / on a Container using Jenkins as a Build Tool.

- [ ] Then combine it with Ansible (to make this CI/CD pipeline more smoother). So in this manner
  - Jenkins is going to take the code from GitHub and build artifacts, and copy those artifacts on to Ansible server
  - Ansible is going to take the artifact, and with help of Docker file, it creates a Docker image
```
The purpose of integrating Jenkins with Ansible in a CI/CD pipeline is to automate the deployment process. Jenkins can be used to build and test the software, while Ansible can be used to manage and provision the infrastructure, making the deployment process more efficient, reliable, and repeatable. By combining the two tools, the deployment process can be streamlined, reducing the potential for errors and making it easier to make changes to the infrastructure and applications.
```

- [ ] Last but not least - integrate Kubernetes in AWS. Why Kubernetes? In case the Docker container goes down, there is no way to recover. So to overcome this problem, we can use Docker native service called Docker swarm, or else we can use container management service like Kubernetes.
