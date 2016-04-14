# Create a VM with an RDP port

This sample template demonstrates how to create a NAT rule in loadbalancer to allow RDP to a vm.

You can connect to the vm using:

* mstsc.exe /v:&lt;publicDnsName&gt;.&lt;location&gt;.cloudapp.azure.com:&lt;rdpPort&gt;


This template deploys the following resources:
<ul><li>storage account</li><li>vnet</li><li>public ip</li><li>load balancer with a NAT rule for RDP</li><li>a virtual machine</li></ul>


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FBlueContext%2F/AzureTemplates%2Fmaster%2FVM-With-RDP-NAT%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FBlueContext%2F/AzureTemplates%2Fmaster%2FVM-With-RDP-NAT%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
