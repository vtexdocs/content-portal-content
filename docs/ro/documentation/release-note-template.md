---
title: 'Release note'
id: edu0009-ro
status: PUBLISHED
createdAt: 2025-02-06T15:00:00.388Z
updatedAt: 2025-02-06T15:00:00.388Z
publishedAt: 2025-02-06T15:00:00.388Z
firstPublishedAt: 2025-02-06T15:00:00.388Z
contentType: trackArticle
productTeam: Education
slugEN: release-note-template
locale: ro
trackId: 5PxyAgZrtiYlaYZBTlhJ2A
trackSlugEN: release-note-template
---

A release note informs users about updates, enhancements, and bug fixes in a new product version. In this guide, you’ll see general guidelines on how to write a release note and the release note template.

> ℹ️ Make sure to review the guidelines in the [Best practices for writing documentation](https://contentguide.vtex.com/docs/documentation/documentation-overview#best-practices-for-writing-documentation).

## Writing a release note

| **Topic** | **Description** |
| --------- | --------------- |
| **Introduction** | <ol><li>Start the first paragraph with an overview, explaining the change and its impact.</li><li>Ensure the reader immediately understands how the changes presented in the release note will affect their store operations.</li></ol> |
| **"What has changed?"** | Explain the changes introduced by the release. |
| **"Why did we make this change?"** | Explain what motivated VTEX to create it and the issues that were solved. |
| **"What needs to be done?"** | <ol><li>Guide readers on how to leverage these new capabilities or adapt to changes.</li><li>Add a call to action to direct the reader to additional information.</li></ol> |

## Release note template

Release notes must have the following tags at their beginning:

| **Tag name** | **Icon** | **Description** |
| ------------ | -------- | --------------- |
| `added`      | `+`      | New features, functionalities, or components introduced in the release. |
| `deprecated` | `➖` | A feature, function, or component is no longer recommended for use. |
| `info` | `ℹ` | Important information or updates that aren't tied to specific changes but are relevant for users. |
| `fixed` | `✔` | Bugs or issues that have been solved in the release. |
| `removed` | `x` | A feature, functionality, or component has been eliminated. |
| `improved` | `^` | Enhancements or optimizations made to existing features or products. |

<details>
<summary><b>Release Note template</b></summary>

```md
# Feature name: summary
 
We created/modified this feature to <insert the key benefit> so you can <job to be done>.

## What has changed?

Before, you had to <how the user used to solve the problem>. Now, you have this <new button/screen/experience> where you can <benefit>.

## Why did we make this change?

In order to <facilitate your job to be done>, we developed <subject>. This is available for <specific or general users?>.

## What needs to be done?
To <use this new resource> you have to <install something or adjust a configuration.>

To learn more <about the feature/module/product>, see <the article>.
```

</details>

> See release note examples in the [Developer Portal](https://developers.vtex.com/updates/release-notes).

## Exemple pentru română

Secțiunea de mai sus este redactată în engleză. Mai jos găsiți un exemplu de release note adaptat pentru publicul român. Pentru formate de dată, monedă și locale, consultați [Formate de date](https://contentguide.vtex.com/ro/docs/interface-copy/data-formats).

<details>
<summary><b>Exemplu de release note (română)</b></summary>

```md
# Checkout: suport pentru rate în RON

Am modificat această funcționalitate pentru a afișa ratele de plată în format local, astfel încât să puteți oferi opțiuni de plată clare clienților din România.

`added` Suport pentru afișarea **3 rate de 150,00 RON** în checkout.

`improved` Formatarea prețurilor cu separator zecimal virgulă și simbol **RON** (ex.: **1.299,99 RON**).

`fixed` Eroare la calculul totalului pentru comenzi peste **10.000 RON**.

## Ce s-a schimbat?

Anterior, ratele erau afișate doar ca valoare totală. Acum, checkout-ul afișează numărul de rate și valoarea fiecărei rate, conform formatului **ro-RO**.

## De ce am făcut această schimbare?

Pentru a alinia experiența de plată la convențiile locale din România și pentru a reduce confuzia la finalizarea comenzii.

## Ce trebuie făcut?

Pentru a utiliza această resursă, actualizați tema la versiunea **2.4.0** sau mai recentă. Nu este necesară nicio configurare suplimentară.

Pentru a afla mai multe, consultați [Notele de lansare](https://developers.vtex.com/updates/release-notes).
```

</details>
