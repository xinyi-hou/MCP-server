# MCP Server

An implementation of the [Model Context Protocol](https://modelcontextprotocol.io/) (MCP).

## Getting Started

### Installation

```bash
npm install
```

### Running the server

```bash
npm start
```

### Configuration

To use this server with Claude Desktop, add the following to your configuration:

```json
{
  "mcpServers": {
    "myserver": {
      "command": "npm",
      "args": ["start"]
    }
  }
}
```

## License

MIT