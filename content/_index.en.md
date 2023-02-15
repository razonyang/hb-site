---
title: "HB - Hugo Bootstrap Framework"
date: 2022-09-24T18:24:31+08:00
draft: false
tags:
  - A
  - B
  - C
menu:
  main:
    name: Home
    weight: 1
    params:
      icon:
        vendor: bootstrap
        name: house
---

{{< hero >}}
{{< hero-img "images/logo.png" >}}
{{< hero-heading "Build fast, responsive sites with HB" >}}
{{< hero-lead >}}
Fast, responsive, flexible, open source (MIT), modular and feature-rich Hugo Bootstrap Framework (HB). Focusing on user experience, performance and SEO.
{{< /hero-lead >}}
<div class="mt-3 d-flex align-items-center justify-content-center flex-wrap">
  <a class="btn btn-lg btn-primary fw-semibold mb-2" href="{{< relref `docs` >}}">
    {{< icons/icon vendor=bootstrap name=book className="me-1" >}} Read the docs
  </a>
  <a class="ms-2 mb-2" href="https://github.com/razonyang/hb/stargazers" target="_blank" rel="external">
    <img height="36" src="https://img.shields.io/github/stars/razonyang/hugo-mod-icons?style=social" />
  </a>
</div>
{{< /hero >}}

{{< icon-grid "features" >}}
