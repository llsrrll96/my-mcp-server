# my-mcp-server

[![smithery badge](https://smithery.ai/badge/@llsrrll96/my-mcp-server)](https://smithery.ai/server/@llsrrll96/my-mcp-server)

An MCP server built with [Smithery CLI](https://smithery.ai/docs/getting_started/quickstart_build_python)

## Prerequisites

- **Smithery API key**: Get yours at [smithery.ai/account/api-keys](https://smithery.ai/account/api-keys)

## Getting Started

### Installing via Smithery

To install Say Hello automatically via [Smithery](https://smithery.ai/server/@llsrrll96/my-mcp-server):

```bash
npx -y @smithery/cli install @llsrrll96/my-mcp-server
```

### Installing via Smithery (local)

1. Run `smithery dev` to start your MCP server locally.
2. Copy the endpoint URL `http://localhost:1382` into your Claude app to connect.
3. Try sending the request `Say hello to John` to test the example tool.

### Testing locally

1. Run the server:
   ```bash
   uv run dev
   ```

2. Test interactively:

   ```bash
   uv run playground
   ```

Try saying "Say hello to John" to test the example tool.

## Development

Your server code is in `src/hello_server/server.py`. Add or update your server capabilities there.

## Deploy

Ready to deploy? Push your code to GitHub and deploy to Smithery:

1. Create a new repository at [github.com/new](https://github.com/new)

2. Initialize git and push to GitHub:
   ```bash
   git add .
   git commit -m "Hello world 👋"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. Deploy your server to Smithery at [smithery.ai/new](https://smithery.ai/new)
