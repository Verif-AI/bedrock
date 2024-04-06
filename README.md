# Bedrock

This repo hosts the code to call Bedrock Mistral-7B

## Prerequisites
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [Poetry](https://python-poetry.org/docs/#installation)

## Getting Started

1. `aws configure`
    - This sets up your AWS local with credentials
    - To get access keys for IAM users, see [Managing access keys for IAM users](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html)
2. `poetry install` 
    - This installs the necessary dependencies to create the environment
    - Connect Jupyter Notebook to Poetry environment under kernel