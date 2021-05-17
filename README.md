# Sitecore Data Studio Connector
Sitecore Data Studio Connector makes Sitecore Experience Analytics data available in Google Data Studio

I've taken down my site with instructions, but I have included the connector code under Google App Scripts\Code.gs for anyone that wants to create their own connector.

## Small notes on the fork

1. This fork uses unicorn and Sitecore 10
2. I have published the original connector from the author, so you can find it on google

## Usage

1. Create the **Data Studio Connector** named item under the `/sitecore/system/marketing control panel/`
2. In the Data studio connector item - configure the API key, etc. 
3. Add a dataset
4. Use the datastudio script to view the data. You will need to provide the valid api URL and Key. Default API url is  `https://<yoursite>/dcapi/datastudio`