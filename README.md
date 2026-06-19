# redis-commander-pro

Manage resources using redis-cli natively from your AI agent.

## Requirements

- **License key** — purchase from [MCP Marketplace](https://mcpmarketplace.com) to get your `MCP_LICENSE_KEY`
- Node.js 18+

## Installation

```json
{
  "mcpServers": {
    "redis-commander-pro": {
      "command": "npx",
      "args": [
        "-y",
        "redis-commander-pro"
      ],
      "env": {
        "MCP_LICENSE_KEY": "your-license-key-here"
      }
    }
  }
}
```

## Tools

| Tool | Description |
|------|-------------|
| `manage` | Run arbitrary commands using the redis-cli CLI. |

## Development

```bash
npm install
npm run build
npm test
```
