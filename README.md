# Azure Resource Manager Templates

## Minecraft Server on Azure Container Instances

ARM Template to deploy a containerized Minecraft Server to Azure. The output will be:
- an **ACI** (Azure Container Instance) running the Minecraft Server image from [itzg/docker-minecraft-server](https://github.com/itzg/docker-minecraft-server);
- an Azure **Storage Account** with a *file share* to store the server data and progress.

<div align="center">

![Resource Visualized](./gfx/MinecraftServerTemplate.png)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FTeam-Cloudio-Bisio%2FARM-Templates%2Fmain%2Ftemplates%2Fazure-minecraft-server-template.json)

</div>