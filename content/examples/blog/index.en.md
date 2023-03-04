---
title: Blog Home Page
date: 2023-02-26T18:24:31+08:00
layout: landing
draft: false
summary: Blog home page example.
---

<div class="row">
  <div class="col-12 col-lg-6">
    {{< hb/carousel params.featured=true >}}
  </div>
  <div class="col-12 col-lg-6">
    {{< hb/blog/posts params.pinned=true limit=2 cols="row-cols-2" >}}
  </div>
</div>

<div class="row">
  <div class="col-12 col-lg-8">
    {{< bootstrap/toggle name="home-toggle" style=pills >}}

      {{< bootstrap/toggle-item name="Recent Posts" >}}
        {{< hb/blog/posts type=blog sorting="Date desc" limit=6 cols="row-cols-1 row-cols-xl-2" >}}
      {{< /bootstrap/toggle-item >}}

      {{< bootstrap/toggle-item name="Recent Docs" >}}
        {{< hb/blog/posts type=docs sorting="Date desc" limit=6 cols="row-cols-1 row-cols-xl-2" >}}
      {{< /bootstrap/toggle-item >}}

    {{< /bootstrap/toggle >}}
  </div>
  <div class="col-12 col-lg-4">
    {{< hb/blog/taxonomies limit=20 >}}
  </div>
</div>
