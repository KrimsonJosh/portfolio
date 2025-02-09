---
layout: ../../layouts/MarkdownPostLayout.astro
title: Testing glob
author: Joshua Moinzadeh
description: "This post will show up on its own!"
image:
    url: "https://docs.astro.build/default-og-image.png"
    alt: "The word astro against an illustration of planets and stars."
pubDate: 02/08/2025
tags: ["astro", "successes"]
---
This post should show up with my other blog posts, because `import.meta.glob()` is returning a list of all my posts in order to create my list.