# Instalação detalhada

DETRAN RJ: GRT (Guia de Regularização de Taxas) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_detran_rj_grt`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_detran_rj_grt` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_detran_rj_grt` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_detran_rj_grt` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.detran_rj_grt` (ou `servers.detran_rj_grt` no VS Code) do config do cliente e reinicie.
