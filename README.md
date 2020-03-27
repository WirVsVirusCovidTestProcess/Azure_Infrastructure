# Azure_Infrastructure

Azure Infrastructure for a registration process of Corona testing

Template deploys following resources

- Storage Account
- Cosmo DB
- App Service Plan
  - Web Application (Patient)
  - Web Application (Test Center)
  - Function App (Backend)
- SendGrid Account for sending out emails to patients

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FWirVsVirusCovidTestProcess%2FAzure_Infrastructure%2Fmaster%2Fazuredeploy.json)
