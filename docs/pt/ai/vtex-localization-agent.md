---
title: 'VTEX Localization Agent'
id: ai0001-pt
status: PUBLISHED
createdAt: 2026-09-15T13:00:00.000Z
updatedAt: 2026-09-15T13:00:00.000Z
publishedAt: 2026-09-15T13:00:00.000Z
firstPublishedAt: 2026-09-15T13:00:00.000Z
contentType: trackArticle
productTeam: Localization
slugPT: vtex-localization-agent
locale: pt
trackId: 4hT9wZLKq0Yx7Bn2AeVta1
trackSlugPT: vtex-localization-agent
---

O **VTEX Localization Agent** é um agente de IA especializado em internacionalização, localização e tradução. Ele aplica as normas de escrita e a terminologia com curadoria da equipe de Localização da VTEX, a partir das bases de conhecimento oficiais e dos padrões internos de conteúdo, ajudando a manter o conteúdo dos produtos e da documentação da VTEX consistente, preciso e alinhado à marca em todos os idiomas suportados.

## O que ele pode te ajudar a fazer

- **Traduzir conteúdo** com domínio total em inglês, português e espanhol, os idiomas principais suportados pela VTEX, além de também atuar nos demais idiomas disponíveis no Admin e no Storefront/Checkout, aplicando regras gerais de tradução.
- **Consultar termos do glossário** para manter a terminologia consistente entre os conteúdos.
- **Aplicar o VTEX Content Style Guide** e outras normas internas de escrita a um texto.
- **Seguir as diretrizes de tradução da VTEX** ao adaptar um conteúdo para um novo idioma.
- **Aplicar boas práticas de internacionalização (i18n)**, como identificar textos que podem não traduzir ou escalar bem entre idiomas.

## Como acessar o agente

### Pelo navegador

Acesse a interface do agente em [localization.myvtex.com/admin/vtex-localization-agent](https://localization.myvtex.com/admin/vtex-localization-agent). Essa opção exige login com uma conta VTEX.

### Via MCP (IDEs agênticas)

O agente também expõe um servidor MCP (Model Context Protocol), permitindo que IDEs agênticas — como Cursor, Claude Code e VS Code — chamem suas ferramentas diretamente do seu editor. Adicione-o às configurações de MCP da sua IDE:

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

Depois de recarregar o servidor MCP na sua IDE, as ferramentas do agente — tradução, consulta ao glossário, normas de escrita da VTEX, diretrizes de tradução e boas práticas de i18n — ficam disponíveis automaticamente, sem exigir parâmetros manuais a cada conversa.

## Acessos e permissões

O VTEX Localization Agent foi projetado para ser utilizado exclusivamente por funcionários da VTEX, para a geração e revisão de conteúdos textuais de acordo com as normas de escrita da VTEX.

- **O acesso pelo navegador** exige login com uma conta VTEX válida.
- **O acesso via MCP** exige conexão com a VPN da VTEX.

Caso você não tenha acesso a nenhuma das opções, entre em contato com o time de Localização da VTEX.
