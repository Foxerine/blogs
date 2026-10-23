---
title: 博客开张
published: 2026-10-23
description: 第一篇文章：这个博客是怎么搭起来的。
image: ''
tags: [博客]
category: 随笔
draft: false
---

博客开张了，以后在这里分享技术笔记。

本站的技术栈：

- 静态站点生成器：[Astro](https://astro.build/) + [Fuwari](https://github.com/saicaca/fuwari) 主题
- 托管：Cloudflare Pages，用 `wrangler` 部署
- 搜索：[Pagefind](https://pagefind.app/)，构建时生成索引，不需要后端

写一篇新文章只需要：

```bash
pnpm new-post <文件名>
```
