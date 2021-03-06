# PowerBI-M365Licensing
Sample PBIX Reports for analyzing usage and consumption of M365 Licenses

## Create an Azure AD App Registration and Grant the App Access to the permissions 
  * Organization.Read.All, Directory.Read.All, Organization.ReadWrite.All, Directory.ReadWrite.All

## Import the Sample Power Automate Flow - Requires Premium Connector
  * https://github.com/M365-DenzilFernandes/PowerBI-M365Licensing/raw/main/Get-SubscriberSku.zip
  * This is a Power Automate to flow the data from graph 
  * Request Example GET https://graph.microsoft.com/v1.0/subscribedSkus/ to a csv file.
  * Source docs https://docs.microsoft.com/en-us/graph/api/subscribedsku-get?view=graph-rest-1.0&tabs=http

## Use the Sample Dashboard to build from. 
  * Sample PBIX Report https://github.com/M365-DenzilFernandes/PowerBI-M365Licensing/raw/main/Microsoft365-Licensing-v3.0.pbix
  * Update the Queries (Use Advanced Editor to change the path to your SharePoint or OneDrive location


<img src="https://github.com/M365-DenzilFernandes/PowerBI-M365Licensing/blob/main/PowerBI-M365Licensing-2.png"  style="max-width:100%;">

<img src="https://github.com/M365-DenzilFernandes/PowerBI-M365Licensing/blob/main/PowerBI-M365Licensing.png"  style="max-width:100%;">

<img src="https://github.com/M365-DenzilFernandes/PowerBI-M365Licensing/blob/main/PowerBI-M365Licensing-3.png"  style="max-width:100%;">
