# Instalação detalhada

Jurisprudência TJPR é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tjpr`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tjpr` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_tjpr` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_tjpr` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tjpr` (ou `servers.tjpr` no VS Code) do config do cliente e reinicie.
