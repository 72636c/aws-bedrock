# AWS Bedrock

[![Build Status](https://cloud.drone.io/api/badges/72636c/aws-bedrock/status.svg)](https://cloud.drone.io/72636c/aws-bedrock)

AWS base infrastructure.

## Components

- Artefacts
- CI/CD

## Pipeline

1. `test` (stage and deploy) changes with test stacks
1. `stage` changes with prod stacks
1. `deploy` changes with prod stacks
