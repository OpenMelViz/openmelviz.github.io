---
title: About
description: |
  MelViz Core is a Web application that can render Dashboards in YAML format.
layout: :theme/page
---

# About Roq

Melviz is a tool to visualize data visualizations, dashboards and reports built using `YAML`.

- Supports `YAML` based pages, allowing users to build dahsboards and reports in a declarative way;
- Can read data from `JSON`, metrics and `CSV` sources;
- Data can be transformed using `JSONAta`;
- Support microfrontends for custom visualizations;
- Can pull real-time data from its datasets;
- Allow Communication between components using Filter components;

This is the core project. It results in a web application that can be embed or live standalone to render YAML contents.

## Authors

<div class="authors">
  <!-- authors.yml is in the data/ -->
  {#for id in cdi:authors.fields}
    {#let author=cdi:authors.get(id)}
    <!-- the author-card tag is defined in the default Roq theme -->
    {#author-card name=author.name avatar=author.avatar nickname=author.nickname profile=author.profile /}
  {/for}
</div>

