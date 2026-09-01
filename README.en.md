# Jurisprudência TJMG

### Minas Gerais state court case law for Claude, Cursor and AI agents

Search case law from the **Minas Gerais state court (TJMG)**, one of the largest state courts in Brazil, straight from your AI agent. The same connection reaches 16 other courts when you need to know whether the local understanding follows the superior courts. Free, no login, hosted by the platform.

- ⚖️ **TJMG** plus 16 other Brazilian courts on the same connection
- 🎯 **The snippet that actually MATCHED**, not the boilerplate opening every ruling shares
- 🔗 **Link to the official court site** on every result
- 📄 **Full text on demand** where the ruling allows it
- 🚦 **Says when it does not know**: an unavailable source becomes an explicit notice, never an unexplained blank
- 🔒 **Read-only**
- ⚡ **Free, no login, no credentials**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue

[Versão em português](README.md) · [Full docs (PT-BR)](docs/) · [Agent skill](skills/)

---

## One-click install

### Claude (Web and Desktop)

Anthropic unified MCP installation at `claude.ai/customize/connectors`. **The same link works for Claude Web and Claude Desktop** (just be logged in):

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (if the deeplink does not open): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → paste **Name** `Jurisprudência TJMG` and **URL** `https://api.mcp.ai/p_tjmg`.

### Cursor

[➕ Install Jurisprudência TJMG in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tjmg&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90am1nIn0=)

### VS Code (Copilot Chat)

[➕ Install Jurisprudência TJMG in VS Code](vscode:mcp/install?name=tjmg&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tjmg%22%7D)

### ChatGPT, Manus, OpenClaw and 40+ other clients

Works with any MCP client that speaks **MCP over HTTP**. The server URL is always:

```
https://api.mcp.ai/p_tjmg
```

Per-client details: [INSTALL.md](INSTALL.md).

---

## Example prompts

```
TJMG case law on extraordinary adverse possession
How does TJMG rule on damages in traffic accidents with victims?
Does TJMG follow the STJ on health-plan coverage denials?
```

---

## 3 tools available

| Tool | Description |
|---|---|
| `jurisprudencia_buscar` | Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese. |
| `jurisprudencia_sumulas` | Busca SÚMULAS (incluindo vinculantes) por termo. |
| `jurisprudencia_documento` | Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo). |

Details for each tool: [docs/ferramentas.md](docs/ferramentas.md) (PT-BR)

---

## Pricing

Free.

---

## Privacy & data protection

- **Read-only**, no tool changes data at the source.
- **Sub-processors**: Serper (Google Search), the LLM host you choose (Claude, ChatGPT, Cursor, your own agent). Full list in [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Data returned by the tools is sent to **the LLM host you choose**, a sub-processor outside our control. We recommend plans with training opt-out.

---

## FAQ

**Serve para conferir se a instância local segue o entendimento superior?**
Sim. A mesma conexão traz TJMG e as cortes superiores, então a comparação é uma pergunta só, com o link oficial dos dois lados.

**Precisa de login ou cadastro?**
Não. É grátis e sem credencial, e você não precisa de conta em nenhum tribunal.

**Serve para citar em petição?**
Serve para encontrar e ler. Todo resultado traz o link no site oficial, e a conferência lá é obrigatória antes de citar.

**Por que uma busca voltou vazia?**
Quase sempre é vocabulário: o tribunal nomeia a tese de um jeito diferente do coloquial, e a resposta sugere o que tentar. Se a fonte estiver indisponível no momento, ela diz isso explicitamente, o que é diferente de a decisão não existir.

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills, tudo MIT.


---

## Support

- 📧 [tjmg@mcp.ai](mailto:tjmg@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/tjmg-mcp/issues)
- 📄 [docs/](docs/)

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_tjmg` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
