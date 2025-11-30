---
title: "Projects"
date: 2025-08-03
draft: false
layout: "terms"
description: "Projects - {{ .Site.Title }}"
url: "/projects.html"
---

## Projects

### Penguify (2025)

[Repo](https://github.com/benkulcsar/penguify)

[Check out the Page](https://benkulcsar.github.io/penguify.html)

From WIP to RIP: as of 18 November 2025, the party is over. The free image generation model in the Gemini API has been discontinued.

Illustrates Hacker News with penguins 🐧 

{{< figure
    src="/images/penguify.png"
>}}

<br />

### Llamachat (2025)

[Repo](https://github.com/benkulcsar/llamachat)

Simulated chat between two users roleplayed by Gemma 3 4B Q4_0 using Ollama. Different scenarios can be configured in a YAML file.

The model performs surprisingly well on an older Intel i5 CPU without a GPU.

{{< figure
    src="/images/llamachat.gif"
>}}

<br />

### Newswatch (2020)

[Code](https://github.com/benkulcsar/newswatch) 
[newswatch.live](https://newswatch.live)

Real-time Word Frequencies in 🇬🇧 and 🇺🇸 News 

Newswatch collects data from leading UK and US news websites' front pages and creates visualisations to track word frequency changes over time, providing insights into current news trends and topics.

{{< figure
    src="/images/newswatch_line.png"
    width="822"
>}}


{{< figure
    src="/images/newswatch_tree.png"
    width="837"
>}}

<br />

### Reddit Metrics (2022) - unmaintained 🌇

[Code](https://github.com/benkulcsar/reddit-metrics)
[Dashboard](https://lookerstudio.google.com/reporting/865759fa-0b1a-4bee-8b67-89cb2ed0d2f0)

Live and historical upvote ratios of subreddits.

🐢 You need patience for this one because I stopped maintaining it and the data lives in GCP Cloud Storage buckets.

{{< figure
    src="/images/reddit.png"
    width="1000"
>}}