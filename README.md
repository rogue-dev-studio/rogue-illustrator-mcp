# rogue-illustrator-mcp

**Rogue Development** MCP package for agents.

Rogue MCP bridge for Adobe Illustrator - artboards, vectors, and exports for agents

- Asset Store: https://rogue-dev-studio.github.io/rogue-asset-store/

## Requirements

- Adobe Illustrator desktop installed and preferably running
- Node.js 18+ (`npx`)

## Install (Cursor)

Copy `cursor.mcp.fragment.json` into your Cursor MCP config, or merge:

```json
{
  "mcpServers": {
    "illustrator": {
      "command": "npx",
      "args": [
        "-y",
        "illustrator-mcp-server"
      ]
    }
  }
}
```

Then restart Cursor.

## License

MIT - Rogue Development. See `LICENSE` and `NOTICE`.
