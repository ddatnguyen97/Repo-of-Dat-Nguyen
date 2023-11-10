# Repo-of-Dat-Nguyen
# This is a summary of GitFlow:
GitFlow 
What is GitFlow? 
- Workflow model for managing source code using Git 
- Open-source software development 
- Develop by Vincent Driessen 

Benefits of using GitFlow:
- Work organization: GitFlow provides a clear division of branches such as master, develop, feature, release & hotfix. 
- Concurrent development: Multiple features or bug fixes can be developed concurrently on `feature` branch -> increase productivity and reduce production time. 
- Quality control: `develop` branch is used for integrating new features. These new features are tested before being merged into the `master` branch -> ensure stability. 
- Stable release process: `release` & `hotfix` branches allow you to create release versions and fix bugs separately -> ensure product stability during development. 

GitFlow branches:
- `master` branch: represent the production – ready code, contain the latest stable release of the project. All the code should be deployable & tested. 
- `develop` branch: serve as the integration branch for new features. 
- `feature` branch: it is created for developing new features or enhancements. Once it is completed, this branch is merged into the `develop` branch. 
- `release` branch: it is created when you are preparing to release a new version of your software. Once it is ready, it is merged into both `master` & `develop` branches, and then it is deleted. 
- `hotfix` branch: it is used to quickly address critical issues in the production code. Once it is completed, it will be merged into both `master` & `develop` branches, and then it is deleted.
  
Other branching model:
- Forking workflow: it gives every developer their own server-side repository. This means each contributor has 2 repositories: a private local & a public server-side one. This one is most often seen in public open-source projects.
- Git feature branch workflow: all feature development should take place in a dedicated branch instead of the main branch -> this makes it easy for multiple developers to work on a particular feature without disturbing the main codebase -> the main branch nevers contain broken code. 

# This is a summary of Docker:
Docker
What is Docker?
- Containerization-based application platform
- Allow you to package applications & their dependencies into isolated, convenient & portable containers

Docker's components:
- Docker daemon: a background service running on a server. It manages containers, listens for & executes Docker API requests.
- Docker client: a command-line tool or graphical user interface used to interact with the Docker daemon. Users use Docker client to create, manage & control containers.
- Docker images: records specifying how a container should run. This includes application code, operating system, necessary dependencies.
- Docker containers: isolated runtime environments that contain an application & its dependencies. They share the same kernel as the host operating system but run independently of each other.
- Dockerfile: a text file that defines how to build a Docker image. It contains commands for copying files, installing software & configuring the environment.
- Docker registery: where Docker images are stored & shared.
- Docker compose: a tool that helps you define and manage multiple containers in a configuration file.
- Docker swarm: a tool that manages & deploys multiple containers across multiples servers -> creating scalable & reliable container runtime environment.
- Docker Kubernetes: integrated with Kubernetes. It allows efficient management & deployment of 100 or 1000 containers.
- Docker documentation: providing extensive documentation usage guides, examples, Docker API, ...

Benefits of using Dockers:
- Consistency: ensure applications run consistently across different environments: development -> testing -> production.
- Isolation: allow applications and their dependencies to run in isolated environments -> enhance security & eliminate conflicts between differences applications & libraries.
- Portability: can run on any system that supports Docker -> make it easier to move applications between different environments & cloud providers.
- Efficiency: Docker containers are light weight & share the host operating system's kernel -> lead to efficient resource utilization & allow to run more containers on the same hardware.
- Rapid deployment: Docker containers can be created and launched quickly -> reduce time. It is crucial for microservices architectures & CI/CD pipelines.
