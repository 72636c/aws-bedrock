# AWS Bedrock

[![Build Status](https://cloud.drone.io/api/badges/72636c/aws-bedrock/status.svg)](https://cloud.drone.io/72636c/aws-bedrock)

AWS base infrastructure.

## Components

- Artefacts
- CI/CD
- DNS

## Pipeline

Pull requests:

- `stage` changes with `test` stacks
- `deploy` changes with `test` stacks
- `stage` changes with `prod` stacks

Default branch:

- `deploy` changes with `prod` stacks
