# Docker CI Pipeline
Concourse CI pipeline for building upgraded Docker Images automatically.

## Sequence (WIP)
1. Detect new **Base Image** or **Package**.
2. Build and test new Docker Image.
3. Re-tag and Push to Docker Hub.
