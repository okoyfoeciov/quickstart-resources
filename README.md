This is a fork to support streamable HTTP transport for `mcp-client-typescript`. Demo purpose only. 

## Usage

1. Deploy your MCP server.
2. Fill your ANTHROPIC_API_KEY in .env file.
3. Run: 
```sh
cd mcp-client-typescript
npm install
npm run build
node build/index.js <your_mcp_server_url>
```