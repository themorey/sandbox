# LCI Workshop
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgrandparoach%2Fsandbox%2FLCIstudent%2F%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This repository will deploy a login node, two compute nodes, and 4 storage nodes for use in the hands-on labs for the LCI Workshop.

Users:  
The following users have profiles stored on NFS share located on the Login node:
        root kara tim bob mary rae david joe alice
These users also have passwordless SSH to the other nodes in the environment (ie. ssh Compute-0)

![Workshop Environment](Doc/LCI_environment.png)


