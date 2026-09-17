---
title: 'VTEX Localization Agent'
id: ai0001
status: PUBLISHED
createdAt: 2026-09-15T13:00:00.000Z
updatedAt: 2026-09-15T13:00:00.000Z
publishedAt: 2026-09-15T13:00:00.000Z
firstPublishedAt: 2026-09-15T13:00:00.000Z
contentType: trackArticle
productTeam: Localization
slugEN: vtex-localization-agent
locale: en
trackId: 4hT9wZLKq0Yx7Bn2AeVta1
trackSlugEN: vtex-localization-agent
---

The **VTEX Localization Agent** is a specialized AI agent focused on internationalization, localization, and translation. It applies the writing norms and terminology curated by the VTEX Localization team from VTEX's official knowledge bases and internal content standards, helping keep content across VTEX products and documentation consistent, accurate, and on-brand in every supported language.

## What it can help you with

- **Translate content** with full proficiency in English, Portuguese, and Spanish, VTEX's core supported languages, and also handle the other languages available across the VTEX Admin and Storefront/Checkout by applying general translation rules.
- **Look up glossary terms** to keep terminology consistent across content.
- **Apply the VTEX Content Style Guide** and other internal writing norms to a piece of text.
- **Follow VTEX's translation guidelines** when adapting content for a new language.
- **Apply internationalization (i18n) best practices**, such as flagging text that may not translate or scale well across languages.

## How to access the agent

### Via the browser

Access the agent's Admin UI at [localization.myvtex.com/admin/vtex-localization-agent](https://localization.myvtex.com/admin/vtex-localization-agent). This option requires you to sign in with a VTEX account.

### Via MCP (agentic IDEs)

The agent also exposes an MCP (Model Context Protocol) server, so agentic IDEs — such as Cursor, Claude Code, and VS Code — can call its tools directly from within your editor. Add it to your IDE's MCP settings:

```json
{
  "mcpServers": {
    "vtex-localization-agent": {
      "url": "https://vtex-localization-agent.vtex.systems/mcp/",
      "type": "http"
    }
  }
}
```

After reloading the MCP server in your IDE, its tools — translation, glossary lookup, VTEX writing norms, translation guidelines, and i18n best practices — become available automatically, with no manual parameters needed per conversation.

## Access and permissions

The VTEX Localization Agent is designed to be used exclusively by VTEX employees, to generate and review textual content according to VTEX's writing standards.

- **Browser access** requires signing in with a valid VTEX account.
- **MCP access** requires being connected to the VTEX VPN.

If you don't have access to either option, reach out to the VTEX Localization team.
