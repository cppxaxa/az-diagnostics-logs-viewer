# Access source
[Clone App with Anvil](https://anvil.works/build#clone:CXCAUXQ6ZWTMAHBV=DLBKZ3FE6NSNXEKKNOMGTGA7)

# Usage
Visit this link for usage: [https://az-diagnostics-logs-viewer.anvil.app/](https://az-diagnostics-logs-viewer.anvil.app/)

# Steps
## Pre-requisites
1. The input to the application is a Azure storage account.
2. Set the CORS settings in Azure storage under the section "Resource sharing (CORS)".
3. Add the website "https://az-diagnostics-logs-viewer.anvil.app" without suffix "/" and provide HTTP access.
4. Get the storage "container" SAS URL with the "READ" and "LIST" permissions. Container name will be similar to "insights-logs-auditevent".
