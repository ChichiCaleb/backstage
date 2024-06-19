## Introduction

> - **Implementation of `developers portal` using Backstage**

> - **Serves as application repo used in testing app-controller**


## Features

- Visibility into the infrastruture health and status

- Visibility into running application health and status

- Retrieve relevant cluster credentials and urls

- Ability to securely create and store secrets in AWS secret manager to be consumed by external secret operator and terraform


## Usage

- start the services in docker compose

   ```sh
   docker compose -f docker/docker-compose.yaml up
   ```

- Ultimately to be run in the control cluster and exposed via Ingress

## Bonus

- Integration test in compose

- Vulnerability scan using `Trivy`

- Automated `Changelog generation` and `Release` 


**This is one of multiple projects that aims to setup a functional platform for seemless app deployment with less technical overhead**

**Check Out:**

1. [Terraform-controller](https://github.com/alustan/terraform-controller)

2. [App-controller](https://github.com/alustan/app-controller)

3. [Infrastructure](https://github.com/alustan/infrastructure)

4. [Cluster-manifests](https://github.com/alustan/cluster-manifests)