# 5G Deployments

This repository collects different mobile network configurations (.yaml and .env files) specifically built for educational purposes: 5g-core, 4g-core, 5g-radio...

> [!NOTE]
> All docker images used in the compose.yaml files are already available in https://github.com/orgs/Tknika/packages?repo_name=docker_open5gs, so there is no need to build them manually.

## How to use it

> [!WARNING]
> Make sure you have Docker installed. Otherwise, see: https://github.com/Tknika/5g-kutxa-ansible
- Download the .env and compose.yaml files from the deployment you are interested in to your computer
- Access the folder where you downloaded the files using a terminal
- Run the following command:

```bash
docker compose up -d
```