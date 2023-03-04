---
title: Blog Home Page
date: 2023-02-26T18:24:31+08:00
layout: landing
draft: false
---

<div class="row">
  <div class="col-12 col-lg-6">
    {{< hb/carousel params.featured=true >}}
  </div>
  <div class="col-12 col-lg-6">
    {{< hb/blog/posts limit=1 cols="row-cols-1" >}}
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
    {{< taxonomies-toggle limit=20 style=tabs >}}
  </div>
</div>
