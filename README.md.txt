AWS CI/CD Project

Overview

This repository contains the configuration files and scripts for an AWS CI/CD pipeline. The pipeline automates the build, test, and deployment of applications to AWS environments.

Project Structure

- .github/workflows: Contains the GitHub Actions workflow files for the CI/CD pipeline.
- aws: Contains the AWS CloudFormation templates and configuration files.
- scripts: Contains scripts for automating tasks and deploying applications.
- tests: Contains unit tests and integration tests for the applications.

Prerequisites

- AWS account with necessary permissions
- GitHub account with repository access
- Docker installed on local machine (optional)

Getting Started

1. Clone the repository to your local machine.
2. Create a new AWS CloudFormation stack using the provided template.
3. Configure the GitHub Actions workflow files to point to your AWS environment.
4. Push changes to the repository to trigger the CI/CD pipeline.

Pipeline Stages

1. Build: Builds the application code using Docker.
2. Test: Runs unit tests and integration tests for the application.
3. Deploy: Deploys the application to the AWS environment using CloudFormation.
4. Monitor: Monitors the application for errors and performance issues.

Contributing

Contributions are welcome! Please submit pull requests with changes and updates.

License

This repository is licensed under the MIT License.

Contact

For questions and feedback, please contact Chukwuemeka Ezeobi at emeka_aws.devops@protonmail.com.