
# Video to MP3 Converter Microservice

This project implements a microservice that converts videos to MP3 files. It utilizes Docker, Kubernetes, Minikube, kubectl, RabbitMQ, MongoDB, PostgreSQL, Flask, and YAML files for deployment and orchestration.

## Description

The Video to MP3 Converter Microservice is designed to convert video files into MP3 format. It leverages a microservice architecture to ensure scalability and flexibility. The key technologies used in this project include:

- Docker: Used for containerization, allowing easy packaging and deployment of the microservice.
- Minikube: Provides a local Kubernetes environment for testing and development purposes.
- kubectl: The command-line tool used to interact with the Kubernetes cluster.
- RabbitMQ: A message broker that enables communication between microservices.
- MongoDB: A NoSQL database used for storing metadata and job information.
- PostgreSQL: A relational database used for persistent storage of configuration and settings.
- Flask: A Python web framework used for developing the microservice's RESTful API.
- YAML Files: Configuration files written in YAML format to define the Kubernetes deployments, services, and other resources.



## Screenshots

![App Screenshot](https://github.com/chaudhary-tushar/Mp3-converter-Microservice/blob/master/designarc.jpg)


## Key Features:

- Video to MP3 Conversion: The microservice accepts video files as input and converts them to MP3 format.
- Scalability: The application is designed to scale horizontally, allowing multiple instances of the microservice to handle conversion requests concurrently.
- Asynchronous Processing: RabbitMQ is used to decouple the conversion process, enabling asynchronous processing and improving performance.
- Metadata Storage: MongoDB is utilized to store metadata and job information related to the conversion process.
- Persistent Storage: PostgreSQL is used for storing configuration and settings to ensure data persistence.

## Installation

Before deploying the microservice, ensure you have the following prerequisites:

- Docker: Install Docker on your local machine.
- Kubernetes and Minikube: Set up Kubernetes and Minikube to create a local Kubernetes cluster.
- kubectl: Install kubectl to manage the Kubernetes cluster.
- Install and start mongodb service.
- Install postgresql.
## Deployment

The project provides YAML files for deploying the microservice on a Kubernetes cluster. The deployment includes:

- Containerization using Docker: Docker images are created for the microservice and its dependencies.
- Kubernetes Deployment: YAML files define the microservice deployment, including replica sets, pods, and services.
- RabbitMQ Configuration: A RabbitMQ instance is deployed to enable message passing between microservices.
- MongoDB and PostgreSQL Setup: YAML files define the deployment of MongoDB and PostgreSQL for data storage.
- Ingress and Load Balancing: Kubernetes Ingress is used to route incoming requests to the microservice.

## 🛠 Skills
Python, Flask, MongoDb, PostgreSQL, Docker, Kubernetes, Minikube, Kubectl, Rabbit-Mq, GridFS, Sharding, Dev-Ops, Rest framework, Pandas, Automation, JWT-Authentication, System Design, microservices . 


## Feedback

If you have any feedback, please reach out to me at chaudharytushar014@.gmailcom


## License

This project is licensed under the [MIT License](LICENSE).

