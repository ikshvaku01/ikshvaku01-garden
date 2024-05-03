---
title: Draft Example
published: 2024-05-01
tags: [Markdown, Blogging, Demo]
category: Examples
draft: true
---

# This Article is a Draft
## Github repository cards
You can add dynamic cards that link to Github repositories, on page load, the repository information is pulled from the Github API. `::github{repo="ikshvaku01/ikshvaku01-garden"}`


## Admonitions, notes, containers
Fuwari supports admonitions of type: `tip, note, important, warning, caution`

:::note
This is a note, other frameworks call them containers or alerts
:::

:::tip{title="TIP"}
This is a tip, you can change the title using the title property: `:::tip{title="Custom title"} \`
:::

:::important
Drink 8 glasses of water!
:::

:::warning
* asjksd
* askdjad
    1. aasd
    2. asds
        * errt45
        * refrf
        * wrf434
:::

:::caution
Admonitions can have other elements inside
::github{repo="ikshvaku01/ikshvaku01-garden"}
:::
