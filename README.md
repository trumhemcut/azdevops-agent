# Azure DevOps Agent running in Docker Container

While Azure Hosted Agent is free and very easy to use, it's not convenient when you build the projects especially Docker or Node modules: it doesn't cache the things for you and we need to wait super long from time to time. And I think self-hosted is a solution if you want to make the build process much faster. There're several options though:

- Run the VM agent in Windows
- Run the VM agent in Linux-distro
- Run the agent in container: I prefer this way. The guideline below will use this option.

The steps below help you go through how to build an Azure DevOps agent in Docker. Mostly based on the document here (https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops) and here (https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops)

## 1. Create personal token

[TODO]

## 2. Create linux virtual machine

[TODO]

## 3. Install Docker

[TODO]

## 4. Build Dockerfile

[TODO]

## 5. Run an agent & connect to Azure DevOps
