# Deploying Arda in Azure

ARDA source code is available at [https://github.com/DXBrazil/Arda]().

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDXBrazil%2FArdaDeploy%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template automates the deployment of the Docker Host machine:

- Provision the Virtual Machine 
- Install Docker Compose
- Start Arda microservices and databases

There is also a version for Windows Container. However, the containers are quite large and take about 45 minutes to download and complete.
