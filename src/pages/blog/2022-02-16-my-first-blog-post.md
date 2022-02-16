---
templateKey: blog-post
title: My first blog post
date: 2022-02-16T17:35:44.431Z
description: "delllssdhh shshsg cjajabdhd "
featuredpost: true
featuredimage: /img/blog-index.jpg
tags:
  - code
---
bana a shsbss jsbdksab hdskaaafb belllso cbfeò sjb





<!--StartFragment-->

|                 |                                                                        |
| --------------- | ---------------------------------------------------------------------- |
| \- name: "blog" |                                                                        |
|                 | label: "Blog"                                                          |
|                 | folder: "src/pages/blog"                                               |
|                 | create: true                                                           |
|                 | slug: "{{year}}-{{month}}-{{day}}-{{slug}}"                            |
|                 | fields:                                                                |
|                 | \- {                                                                   |
|                 | label: "Template Key",                                                 |
|                 | name: "templateKey",                                                   |
|                 | widget: "hidden",                                                      |
|                 | default: "blog-post",                                                  |
|                 | }                                                                      |
|                 | \- { label: "Title", name: "title", widget: "string" }                 |
|                 | \- { label: "Publish Date", name: "date", widget: "datetime" }         |
|                 | \- { label: "Description", name: "description", widget: "text" }       |
|                 | \- { label: "Featured Post", name: "featuredpost", widget: "boolean" } |
|                 | \- { label: "Featured Image", name: "featuredimage", widget: image }   |
|                 | \- { label: "Body", name: "body", widget: "markdown" }                 |
|                 | \- { label: "Tags", name: "tags", widget: "list" }                     |

<!--EndFragment-->