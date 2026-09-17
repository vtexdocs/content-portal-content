---
title: 'VTEX Localization Agent'
id: ai0001-es
status: PUBLISHED
createdAt: 2026-09-15T13:00:00.000Z
updatedAt: 2026-09-15T13:00:00.000Z
publishedAt: 2026-09-15T13:00:00.000Z
firstPublishedAt: 2026-09-15T13:00:00.000Z
contentType: trackArticle
productTeam: Localization
slugES: vtex-localization-agent
locale: es
trackId: 4hT9wZLKq0Yx7Bn2AeVta1
trackSlugES: vtex-localization-agent
---

El **VTEX Localization Agent** es un agente de IA especializado en internacionalización, localización y traducción. Aplica las normas de escritura y la terminología curadas por el equipo de Localización de VTEX, a partir de las bases de conocimiento oficiales y los estándares internos de contenido, ayudando a que el contenido de los productos y la documentación de VTEX se mantenga consistente, preciso y alineado con la marca en todos los idiomas admitidos.

## En qué puede ayudarte

- **Traducir contenido** con dominio total en inglés, portugués y español, los idiomas principales admitidos por VTEX, además de trabajar también con los demás idiomas disponibles en el Admin y en el Storefront/Checkout, aplicando reglas generales de traducción.
- **Consultar términos del glosario** para mantener la terminología consistente entre los contenidos.
- **Aplicar el VTEX Content Style Guide** y otras normas internas de escritura a un texto.
- **Seguir las pautas de traducción de VTEX** al adaptar un contenido a un nuevo idioma.
- **Aplicar buenas prácticas de internacionalización (i18n)**, como identificar textos que podrían no traducirse o escalar bien entre idiomas.

## Cómo acceder al agente

### Desde el navegador

Accede a la interfaz del agente en [localization.myvtex.com/admin/vtex-localization-agent](https://localization.myvtex.com/admin/vtex-localization-agent). Esta opción requiere iniciar sesión con una cuenta de VTEX.

### A través de MCP (IDEs agénticas)

El agente también expone un servidor MCP (Model Context Protocol), lo que permite que las IDEs agénticas —como Cursor, Claude Code y VS Code— llamen a sus herramientas directamente desde tu editor. Agrégalo a la configuración de MCP de tu IDE:

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

Después de recargar el servidor MCP en tu IDE, las herramientas del agente —traducción, consulta del glosario, normas de escritura de VTEX, pautas de traducción y buenas prácticas de i18n— quedan disponibles automáticamente, sin necesidad de parámetros manuales en cada conversación.

## Accesos y permisos

El VTEX Localization Agent está diseñado para ser utilizado exclusivamente por empleados de VTEX, para la generación y revisión de contenidos textuales según las normas de escritura de VTEX.

- **El acceso desde el navegador** requiere iniciar sesión con una cuenta de VTEX válida.
- **El acceso vía MCP** requiere estar conectado a la VPN de VTEX.

Si no tienes acceso a ninguna de las dos opciones, comunícate con el equipo de Localización de VTEX.
