---
date: 2018-02-07T19:15:00+06:00
title: Sidebar
authors: ["muniftanjim"]
categories:
  - features
tags:
  - config
slug: sidebar
---

## Enabling Sidebar

For enabling Sidebar, use the following configuration options in your **`config.toml`** file:

```toml
[params.sidebar]
enable = true
sticky = true
```

- `params.sidebar` [`Map`]:
  - `enable` [`Boolean`]: Switch for enabling sidebar
  - `sticky` [`Boolean`]: If `false`, sidebar scrolls with page

## Adding Widgets to Sidebar

For adding Widgets to the Sidebar, setup your [Widgets Configuration File]({{< relref "docs/widgets.md#widgets-configuration-file" >}}) according to the [Widgets documentation]({{< relref "docs/widgets.md" >}}).