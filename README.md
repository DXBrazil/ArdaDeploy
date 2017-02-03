# Deploying Arda in Azure

Deploy the Docker Host machine with Windows Server 2016.

Deploy the VM Extension in order to 
- Install Docker Compose
- Configure Docker to use a public DNS
- Restart Docker Daemon
- Executar o Docker Compose para subir o ambiente

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/DXBrazil/ArdaDeploy/master/azuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/DXBrazil/ArdaDeploy/master/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template deploys Arda. 

For more information, see here:

[https://github.com/DXBrazil/Arda]()
