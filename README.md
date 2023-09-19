# SampleASPNET

## Introduction

This is a sample project demonstrating how to use Azure DevOps for continuous integration and continuous deployment (CI/CD).

## Getting Started

1. **Clone the repository**: Use `git clone <repository-url>` to clone the repository to your local machine.

2. **Install dependencies**: Run `dotnet restore` to install all the necessary dependencies.

## Azure DevOps Pipeline

This project uses Azure DevOps for its CI/CD pipeline. The pipeline configuration is located in the `azure-pipelines.yml` file in the root of the repository.

### Continuous Integration

On every push to the repository, the CI pipeline automatically runs. It performs the following steps:

1. Install dependencies
2. Run tests
3. Build the project

### Continuous Deployment

If the CI pipeline succeeds and the changes are on the main branch, the CD pipeline automatically deploys the application to the configured environment.

## Contributing

Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.
