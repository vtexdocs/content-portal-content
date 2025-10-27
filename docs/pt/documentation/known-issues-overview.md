---
title: 'Known Issues overview'
id: edu0007
status: PUBLISHED
createdAt: 2025-02-06T15:00:00.388Z
updatedAt: 2025-02-06T15:00:00.388Z
publishedAt: 2025-02-06T15:00:00.388Z
firstPublishedAt: 2025-02-06T15:00:00.388Z
contentType: trackArticle
productTeam: Education
slugEN: known-issues-article
locale: en
trackId: 5PxyAgZrtiYlaYZBTlhJ2A
trackSlugEN: known-issues-article
---

[Known Issues](https://help.vtex.com/known-issues) inform users about identified problems in the VTEX platform or products, their current status, and potential solutions (workarounds) or permanent fixes. We constantly update these articles so you can anticipate potential issues and know that our team is aware of them.

This guide covers the complete Known Issues workflow, including the differences between Known Issues and other article types, how to create them, and best practices for writing effective Known Issues documentation.

## Publication workflow

Each time someone from VTEX Product Support creates or updates a public Known Issue on Zendesk, an automated integration workflow is triggered:

1. **Creation/Update in Zendesk**: Product Support team creates or updates a Known Issue
2. **Automatic translation**: Content is automatically translated to Spanish and Portuguese using DeepL API
3. **Publication**: Translated content is published or updated on Help Center
4. **Notification**: A Slack thread is created in `#known-issues-feed` for status tracking

> ℹ️ Only the VTEX Product Support team can create Known Issues. All Known Issues are created in Zendesk, not directly in the repository.

## Differences between Known Issues and Troubleshooting guides

When navigating VTEX documentation, it's important to understand the differences between article types, which have specific purposes. For example, Known Issues articles alert users to identified problems within the platform, providing updates, workarounds, or solutions. In contrast, Troubleshooting guides offer step-by-step instructions for fixing specific errors.

Below, find the goal, content focus and audience between Known Issues articles and other article types:

| **Topic** | **Known Issue** | **Troubleshooting** |
| --------- | --------------- | ------------------- |
| **Goal** | Informing users of known issues within the platform and products and their workarounds or solutions. | Providing step-by-step instructions to solve specific problems or errors. |
| **Content focus** | Problem description, impact, workaround or solution, and status updates. | Troubleshooting steps, error messages, and potential causes. |
| **Audience** | All users who may be affected by the known issue. | Users experiencing specific problems or errors. |
| **Article example** | [Benefits and taxes are not applied to services](https://help.vtex.com/known-issues/benefits-and-taxes-are-not-applied-to-services--4u12zyfc387daNQamFohA2) | [My store’s Site Editor is not working](https://help.vtex.com/tutorial/my-stores-site-editor-is-not-working--3A6Ois91zEZ8zpKJp1wsP2) |

## Guidelines on identifying known issues or product improvements

Both known issues and product improvements intend to enhance the product. However, while known issues focus on solving existing problems, product improvements aim to add new features or enhance existing ones.

To better illustrate the difference between them, consider the following:

| **Topic** | **Known issue** | **Product improvement** |
| --------- | --------------- | ----------------------- |
| **Definition** | An identified problem or bug in the product or platform. | A proposed change to enhance the product or the platform's functionality, usability, or performance. |
| **Focus** | Fixing existing problems. | Adding new features or improving existing ones. |
| **User impact** | Negative impact on user experience or functionality. | Positive impact on user experience or functionality. |
| **Example** | A button on a page doesn't work as expected. | Adding a new feature to filter search results. |

## Known Issue structure

![known-issue-article-overview](https://vtexhelp.vtexassets.com/assets/docs/src/known-issue-article-overview___e5746db32fe1bc696a82b4e1f4fff087.png)

| **Article topic** | **Description** |
| ----------------- | --------------- |
| 1 - Title | Article title describing the issue. |
| 2 - Product name | Tag for the product affected by the issue. |
| 3 - Status | Tag describing the Known Issue status. These are the available status: <ol><li>`Fixed`: The issue has been solved, and a fix has been implemented.</li><li>`Backlog`: The issue has been identified but is not currently scheduled for a fix. It may be prioritized and scheduled for a future release.</li><li>`Scheduled`: The issue has been prioritized and scheduled for a fix.</li><li>`No fix`: The issue won’t be fixed, likely due to low impact, technical constraints, or other reasons.</li></ol> |
| 4 - Created on | Date when the article was created. |
| 5 - Updated on | Date when the article was last updated. |
| 6 - Summary | Section to describe the bug. |
| 7 - Simulation | Section to describe what steps are needed to reproduce the behavior. |
| 8 - Workaround | Section to describe the workaround for the issue, if there’s any. |

## Creating a Known Issue

> ⚠️ Only the VTEX Product Support team can create Known Issues.

To create a Known Issue in Zendesk:

1. Click on **Product > KI > Register a New Known Issue** in Zendesk
2. For public Known Issues (available on Help Center), select **Yes** in the **Is public?** field
3. Fill in the template with detailed information (see [Template structure](#template-structure))

### Linking tickets to Known Issues

Tickets linked to a Known Issue must have:

- **Type** set as `Incident`
- **Linked problem** field with the Known Issue ID
- **Incident Type** as `Regular`

## Template structure

When creating a Known Issue in Zendesk, use this template:

```markdown
[KI] Insert title 

## Summary
Describe the bug concisely.


## Simulation
Describe here what steps are needed to reproduce this behavior.


## Workaround
Is there a workaround for this bug? If yes, describe it here.


PS.: Add images and attachments to reinforce your description

------------------------------------------------------------------------------

## Internal Notes

Include any additional information that should not be public but could be relevant for VTEX staff.
Add here images and attachments to reinforce your description.
```

> ❌ Don't change or remove the template's section titles and formatting. The integration relies on this structure to properly process and publish the Known Issue.

## Best practices (Dos)

When creating a Known Issue, follow these best practices:

✅ **Language and quality**
- Always write the Known Issue in English.
- Run your text through a spell-checking tool (e.g., [Grammarly](https://www.grammarly.com/)).
- Use proper [markdown syntax](https://www.markdownguide.org/cheat-sheet/).
- Test the final result using tools like [Markdown Live Preview](https://markdownlivepreview.com/).

✅ **Content completeness**
- Write detailed descriptions for all Known Issue fields.
- Provide clear, step-by-step simulation instructions.
- Include workarounds when available, even if partial.
- Add relevant images and attachments to support your description.

✅ **Visibility and transparency**
- Make the Known Issue public whenever possible.
- Check `#known-issues-feed` on Slack after creating or updating to verify publication status.

✅ **Internal documentation**
- Use the **Internal Notes** section (below the horizontal bar) for internal comments.
- Add context that helps VTEX staff but should not be public.

## What to avoid (Don'ts)

To ensure proper integration and publication, avoid these common mistakes:

❌ **Template structure**
- Don't change or remove section titles and formatting.
- Don't remove the horizontal bar before the **Internal Notes** section.
- Don't delete **[KI]** from the title.
- Don't leave any Known Issue field blank (even if there's no Simulation or Workaround, add N/A or an explanation).

❌ **Security and privacy**
- Don't write internal comments, confidential information, or client screenshots outside the **Internal Notes** section.
- Don't use sensitive data from VTEX clients' stores.

## Examples of Known Issues

- [Cart does not update in FastStore if external request is made to update orderForm](https://help.vtex.com/known-issues/cart-does-not-update-in-faststore-if-external-request-is-made-to-update-orderform--7ef1GxxapbH2XKKf7HBuAM)
- [Stuck transactions after Risk Rejection](https://help.vtex.com/known-issues/stuck-transactions-after-risk-rejection--4LKwXp4P9IEkUh02vNZKiA)
- [Benefits and taxes are not applied to services](https://help.vtex.com/known-issues/benefits-and-taxes-are-not-applied-to-services--4u12zyfc387daNQamFohA2)
- [FetchMore brings repeated values between the to and from](https://help.vtex.com/known-issues/fetchmore-bringing-repeated-values-between-the-to-and-from--1Vx0YekKCDaf8t6hocU1iv)

## Additional resources

- [Known Issues Help Center](https://help.vtex.com/known-issues)
- [Markdown syntax guide](https://www.markdownguide.org/cheat-sheet/)
- [Grammarly spell checker](https://www.grammarly.com/)
- [Markdown Live Preview](https://markdownlivepreview.com/)