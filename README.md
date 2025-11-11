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
