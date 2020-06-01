+++
title = "Static Sites"
outputs = ["Reveal"]
layout = "bundle"
[reveal_hugo]
theme = "night"
margin = 0.2
weight = 1
+++

# Static Sites
by [@rodislavable](https://twitter.com/rodislavable)

---

## Introduction

{{% eyes-up %}}

{{% fragment %}}
A static site usually has all the pages pre-rendered, when those are being served to the browser.
{{% /fragment %}}


{{% fragment %}}*With* backend &nbsp;&nbsp;&nbsp;&nbsp;OR&nbsp;&nbsp;&nbsp;&nbsp;*Without* backend{{% /fragment %}}


---

## With Backend

Server side rendering. Meaning you can have some backend application that will generate the page.

{{% fragment %}}<br/>For example<br/>{{% /fragment %}}

{{% fragment %}}- **NodeJS** EJS, vuexpress, react, etc.{{% /fragment %}}

{{% fragment %}}- *Others*, like Twig, JSP, ASP, etc.{{% /fragment %}}

---

## Without backend

{{% in-love %}}

{{% fragment %}}
Usually pure HTML, CSS and some JS for interactivity,
therefore easy and fast.
{{% /fragment %}}

---

## We'll focus on last

---

## Anatomy

1. Technical backend, coding.
1. Content, text, media and portability.
1. Infrastructure, hosting and domain.