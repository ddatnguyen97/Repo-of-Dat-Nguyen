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
  

# This is a summary of Docker:
