# azure-test-azure-traffic-manager

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

Use this repository to quickly deploy a pair of Azure Web App instances in multiple regions that use an Azure Traffic Manager to geo-distribute the traffic according to the users region. 

The Web App instances will be deployed to App Service Plans using Standard S0 pricing tier as Standard is required to use Azure Traffic Manager. The Traffic Manager will be bound to the two Web App instances. The Web App instances themselves will need to be linked post-deployment to the GitHub Repository for the website contents.


