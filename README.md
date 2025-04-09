## Deploy to Azure for Remote MCP

Run this [azd](https://aka.ms/azd) command to provision the function app, with any required Azure resources, and deploy your code:

```bash
azd env set VNET_ENABLED true
```

```shell
azd up
```

https://<apim-name>.azure-api.net/mcp/sse try in MCP Inspector 

