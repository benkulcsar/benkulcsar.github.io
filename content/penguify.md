---
title: "Penguified Hacker News"
date: 2025-08-03
draft: false
layout: "terms"
description: "Penguified Hacker News - {{ .Site.Title }}"
url: "/penguify.html"
---

Top 9 [Hacker News](https://news.ycombinator.com/news) stories, illustrated with penguins using [Gemini 2.0](https://developers.googleblog.com/en/generate-images-gemini-2-0-flash-preview/) in [Google AI Studio](https://aistudio.google.com). 

Updated daily by [Penguify](https://github.com/benkulcsar/penguify).🐧

{{< s3img_prefix9
     id="grid"
     base="d2135birk3game.cloudfront.net"
     manifest="/manifest.json"
     placeholder="Choose a day:"
     cacheBust="true"
>}}
