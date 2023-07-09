# Jenkins Pipeline with Parameters

This Jenkins pipeline demonstrates the usage of parameters to clone a repository and execute a specified file. It requires Node.js to be installed on the Jenkins environment.

## Pipeline Parameters

The following parameters are required for this pipeline:

1. `Repository` (String): The URL of the repository to be cloned.
2. `AppFile` (String): The file path to be executed.

## Pipeline Stages

The pipeline consists of the following stages:

1. **Clone Repository**: Clones the specified repository.
2. **Execute App**: Executes the specified file from the cloned repository.

## Prerequisites

Before running this pipeline, ensure that Node.js is installed on the Jenkins environment. You can configure Node.js in the Jenkins global tool configuration.

## Pipeline Setup

To use this pipeline, follow these steps:

1. Configure a Jenkins job to use this pipeline as the Jenkinsfile.
2. Set the following parameters when running the job:
    - `Repository`: Provide the URL of the repository you want to clone.
    - `AppFile`: Specify the file path to be executed.

Please make sure that the nodejs tool is configured in the Jenkins global tool configuration and is accessible to the Jenkins job.

Feel free to update this README.md according to your specific project and pipeline requirements.
