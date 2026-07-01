# Azure AI Vision App

## Structure
- frontend/: Static Web App frontend
- api/analyzeImage/: Azure Function
- host.json: Azure Functions host
- local.settings.json: Local settings

## Run locally
1. Install Azure Functions Core Tools and Node.js.
2. Add your Azure AI Vision endpoint and key to local.settings.json.
3. Run:
   - func start
4. Serve the frontend or use Azure Static Web Apps CLI.

Deploy the repository to Azure Static Web Apps. The frontend calls POST /api/analyzeImage.
