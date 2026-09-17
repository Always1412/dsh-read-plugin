# DSH-Read plugin marketplace

Read-only access to local DeepSeek Harness (DSH) sessions through a remote MCP server.

- Marketplace manifest: `.agents/plugins/marketplace.json`
- Plugin: `plugins/dsh-read` (display name **DSH-Read**)
- MCP endpoint: Streamable HTTP, OAuth 2.1 (authorization code + PKCE S256 + dynamic client registration)
- Tools: 11 read-only tools (session list / session read / cross-session search / knowledge base / shared memory / AI-HQ ledger). **No write tools exist on the server.**
