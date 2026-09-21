---
title: 'Onboarding'
id: edu0008-ro
status: PUBLISHED
createdAt: 2024-12-03T19:24:22.388Z
updatedAt: 2025-02-03T11:11:00.388Z
publishedAt: 2024-12-03T19:24:22.388Z
firstPublishedAt: 2024-12-03T19:24:22.388Z
contentType: trackArticle
productTeam: Education
slugEN: onboarding-template
locale: ro
trackId: 5PxyAgZrtiYlaYZBTlhJ2A
trackSlugEN: onboarding-template
---

Onboarding articles introduce new users to a specific technology, tool, or system to facilitate the learning curve and enable them to become proficient and productive.

In this guide, you'll see the available template, general guidelines, and examples of Onboarding articles in this guide.

> ℹ️ Make sure to review the guidelines from the [Best practices for writing documentation](https://contentguide.vtex.com/docs/documentation/documentation-overview#best-practices-for-writing-documentation).

## Writing an onboarding article

| Topic | Description |
| :---- | :---- |
| **Focus on Fundamentals** | Emphasize the core elements a user needs to understand to get started, such as critical dependencies, initial configurations, and key setup steps. Avoid overwhelming users with advanced configurations unless they're necessary for the initial usage.  |
| **Assets** | Whenever possible, include visuals such as diagrams, screenshots, or flowcharts. These can clarify complex processes and provide users with a quick reference. In the architecture section, a well-labeled diagram helps illustrate system components and interactions. |
| **Instructions** | For sections like **Quickstart**, make sure each step is actionable and, if needed, link to additional resources for deeper understanding. |
| **Links to Prerequisites and Further Learning** | Use links to redirect users to related technologies, documentation, and guides. For example, in the Next steps section, suggest related configurations or customizations and link to resources that expand on or complement the basic onboarding content. |

## Onboarding template

<details>
<summary><b>Onboarding template</b></summary>

```md
# Title
[Describe what the technology is in this section.]

Ex.: To work with {technology name}, you should be familiar with the following technologies:
[Add here the technologies that the user should know before starting to work with it.]
[Technology 1](#)
[Technology 2](#)
[Technology 3](#)
… 
## {technology name} architecture
[Add here a diagram illustrating the technology architecture and provide an explanation.]

## Quickstart
[Describe the instructions for developing a project using the technology, from installing the requirements to running the project locally. The steps below can vary depending on the technology used.]

### 1. Initial settings
[Describe the requirements and initial configuration needed before developing the project.]

### 2.  Setting up the project
[Provide instructions for setting up the development environment to kickstart the project and run it locally.]

### 3. Customizing the storefront
[After running the project locally, describe the customization options available.]

## Next steps
[Suggest additional initial configurations or steps for those who have completed the quickstart section, and include the card component along with links to suggestions.]
```

</details>

## Examples of Onboarding articles

- [FastStore - Overview](https://developers.vtex.com/docs/guides/faststore)  
- [Store Framework - Overview](https://developers.vtex.com/docs/guides/store-framework)

## Exemple pentru română

Secțiunea de mai sus este redactată în engleză. Mai jos găsiți un exemplu de articol de onboarding adaptat pentru publicul român.

<details>
<summary><b>Exemplu de onboarding (română)</b></summary>

```md
# FastStore

FastStore este un framework headless pentru vitrine VTEX. Pentru a lucra cu FastStore, ar trebui să cunoașteți următoarele tehnologii:

- [React](https://react.dev/)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)

## Arhitectura FastStore

[Adăugați aici o diagramă care ilustrează arhitectura și o explicație scurtă.]

## Quickstart

Urmați pașii de mai jos pentru a configura un proiect local. Timp estimat: **45 minute**.

### 1. Setări inițiale

1. Instalați **Node.js** versiunea **18** sau mai recentă.
2. Instalați **VTEX IO CLI**.
3. Verificați că aveți acces la un cont VTEX cu workspace de dezvoltare.

### 2. Configurarea proiectului

1. Executați `vtex use {numeWorkspace}` în terminal.
2. Clonați repository-ul starter FastStore.
3. Rulați `yarn install` și apoi `yarn dev`.
4. Accesați vitrina la `http://localhost:3000`.

### 3. Personalizarea vitrinei

1. Editați componentele din directorul `src/components`.
2. Configurați moneda implicită la **RON** și locale-ul la **ro-RO**.
3. Testați afișarea unui produs cu preț **299,90 RON**.

## Pași următori

- [Configurarea checkout-ului pentru România](https://developers.vtex.com/docs/guides)
- [Publicarea vitrinei în producție](https://developers.vtex.com/docs/guides)
```

</details>
