---
title: Unity
layout: default
nav_order: 6.5
---

# Unity

You specify the layout for a page in its [front matter]. Just the Docs has a `default` layout with a sidebar, used for almost all pages in the theme docs, and a `minimal` layout that omits the sidebar.
{: .fs-6 .fw-300 }

## The layout concept

See the [Jekyll docs page about layouts] for an explanation of the general idea of layouts and how to specify them.

You can use [Jekyll's front matter defaults] to specify the same layout for many pages.

## The `default` layout

This page uses the default layout. This site configures `layout: default` as a [front matter default](https://jekyllrb.com/docs/configuration/front-matter-defaults/) value for all pages in the `docs` directory.

The default layout of Just the Docs is a *responsive* layout: on medium and larger width displays, it displays a sidebar, including a navigation panel; on smaller width displays, the sidebar is automatically hidden under a button.

All pages except top-level pages automatically have a list of  so-called *breadcrumbs*: links to their parent pages and any higher-level ancestors. They show the breadcrumbs above the main content of the page.

Each page that has child pages generally has a list of links to those pages (you can suppress it by `has_toc: false` in the front matter). It shows the list as a *table of contents* below the main content.