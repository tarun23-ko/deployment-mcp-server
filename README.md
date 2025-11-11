## ⚙️ MCP Client Configuration

To connect your client to the **MCP Server** directly from GitHub using `uvx`, add the following to your MCP configuration file (for example, `mcp.json` or `mcp_tools.json`):

```json
{
  "mcpServers": {
    "deployment-mcp-server": {
      "command": "uvx",
      "args": [
        "git+https://github.com/yourname/deployment-mcp-server.git",
        "mcp-server"
      ],
      "env": {
        "PYTHONUNBUFFERED": "1"
      }
    }
  }
}
