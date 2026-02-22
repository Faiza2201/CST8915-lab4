# CST8915-lab4: Algonquin Pet Store on Azure VM

**Student Name**: Faiza Boudehane
**Student ID**: 041273470
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Winter 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/HTxuJ9wP_FU)

---

## Technical Explanations
### 1- What are the main differences between a Docker image and a Docker container?
   Docker image is a template from which we can get container once image is run, so a docker image become a container at runtime.
### 2- Explain how Docker's layered architecture improves efficiency.
   the fact that layered architecture is based on a read only layers, this make them reusable by differents containers and this really improve efficiency.
### 3- Why does each container get its own writable layer?
This is because other shared layers are read-only, so each container will get a container layer that is writable for any changes in this container.
### 4- What are the benefits of using Docker Compose over running containers individually?
The Docker compose is a central point for multi container running thus you can customise one services config file 'yaml' , the scale like in this lab where we scaled web service to 3 is easier with docker compose, and then stopping containers is also much easier; with only one docker compose command we stopped all containers running/stopped.
