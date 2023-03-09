# Orchestrator API Gateway Setup
This repository should be cloned and used as the entry-point for all orchestrator services.
## Prerequisites
If you are using Linux:
- Install Docker
If you are using Windows:
- Install WSL2
- Install Docker for Windows
## Usage Instructions
- Clone the repository into a folder.
- Clone all other orchestrator repositories into the same folder.
- Open a terminal in that folder and run the following commands:
```
cd orchestrator-nginx-gateway
docker-compose up -d
```
- The orchestrator should now be accessible on port 80.
- To shutdown the orchestrator, simply run `docker-compose down`.