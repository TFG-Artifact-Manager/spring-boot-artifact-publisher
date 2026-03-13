# Demo API - Spring Boot Artifact Publisher

This project demonstrates CI/CD integration with the Artifact Manager.

## What it does:
- Builds a Spring Boot JAR file
- Calculates SHA-256 checksum
- Publishes to Artifact Manager via API
- Tags: backend, java, spring-boot, [branch-name]

## Setup:
1. Fork this repository
2. Add secrets in GitHub:
   - `ARTIFACT_MANAGER_URL`: http://your-server:3000
   - `ARTIFACT_MANAGER_TOKEN`: your-api-token
3. Push to main/develop to trigger build

## Artifact Details:
- Name: demo-api
- Type: JAR
- Size: ~20MB
- Version: 1.0.{BUILD_NUMBER}