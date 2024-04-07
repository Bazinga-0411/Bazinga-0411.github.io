---
title: "短代码（Shortcodes）"
date: 2022-05-02T13:12:47+02:00
slug: shortcodes
draft: false
toc: false
summary: 一些短代码示例
tags:
  - Shortcodes
  - Hugo
categories:
  - Luna
---

## 文字排版

```markdown
{{</* align left "文字居左" */>}}

{{</* align center "文字居中" */>}}

{{</* align right "文字居右" */>}}
```

{{< align left "文字居左" >}}

{{< align center "文字居中" >}}

{{< align right "文字居右" >}}

## GitHub

```markdown
{{</* github name="tailwindlabs/tailwindcss" link="https://github.com/tailwindlabs/tailwindcss" description="A utility-first CSS framework for rapid UI development." color="#f1e05a" language="JavaScript" */>}}
```

{{< github name="tailwindlabs/tailwindcss" link="https://github.com/tailwindlabs/tailwindcss" description="A utility-first CSS framework for rapid UI development." color="#f1e05a" language="JavaScript" >}}

## 轮播图

```markdown
{{</* carousel "../links/Resume_Qinyang Huang.pdf" */>}}
```

{{< carousel "https://unsplash.it/1920/1080/?random=1" "https://unsplash.it/1920/1080/?random=2" "https://unsplash.it/1920/1080/?random=3" "https://unsplash.it/1920/1080/?random=4" >}}
