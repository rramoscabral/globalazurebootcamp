# Azure Bootcamp Template

This is a fork from Puneet Ghanshani https://github.com/punitganshani/azurebootcamp.

I updated the 2017 source code for .NET Core with Visual Studio Code and is compatible with Visual Studio 2017.
By default is using Singapore data from [AzureBootcamp-Data Wiki](https://github.com/punitganshani/azurebootcamp-data/wiki).

## Technology Stack

- .NET Core 2.0 SDK (https://www.microsoft.com/net/download/core)
- HTML5
- jQuery
- CSS3
- Google API
- Facebook API

## How to use it?

- You don't need to edit HTML code, or deploy this as well
- You just need to submit a pull request to create a json file with your event details at [AzureBootcamp-Data Wiki](https://github.com/punitganshani/azurebootcamp-data/wiki) or use your GitHub and voila, the site is up!



- Detailed steps for json file and the entire process is documented at [AzureBootcamp-Data Wiki](https://github.com/punitganshani/azurebootcamp-data/wiki)

## Configuring subdomain like region.azurebootcamp.net

- Login to [Gloabl Site](http://global.azurebootcamp.net)
- Select your host (say, singapore.azurebootcamp.net) and add CNAME to your Azure WebApp (like, azurebootcamp2016.azurewebsites.net/**your-location**)
- Now access sub-domain website (say, singapore.azurebootcamp.net) and it will route to azurebootcamp2016.azurewebsites.net/**your-location**
