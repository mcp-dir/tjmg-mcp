# Instalação detalhada

Jurisprudência TJMG é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjmg`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjmg` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjmg` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjmg` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjmg` (ou `servers.tjmg` no VS Code) do config do cliente e reinicie.
