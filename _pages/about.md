---
permalink: /
title: "Welcome to the Zhao Group"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
We are **A Semiconductor Electronics Laboratory** at Rensselaer Polytechnic Institute. We study semiconductor devices and integration by leveraging ultra-wide bandgap materials to push the limits of performance, functionality, and scalability. Our research bridges fundamental physics and applied engineering to enable next-generation technologies in RF communications, sensing, and quantum information.

Our research directions include:

- **RF acoustic filters**

Developing high-frequency, high-Q acoustic filters that are compact and compatible with on-chip integration.

- **Monolithically integrated RF electronics**

Merging acoustic and electronic components on a single chip to realize compact, multifunctional platforms.

- **Quantum acoustics for superconducting systems**

Exploring phonon-mediated signal transduction and device integration for hybrid quantum technologies.

[Read about our research](/research/)

---

## Lab News

- **July 2025** –  Our lab is officially launched at RPI, focusing on wide bandgap semiconductors acoustic and electronic devices.
- **June 2025** –  Wenwen presented the AlN/GaN/AlN BAWFET work in DRC 2025.

{% for post in site.News limit:10 %}
- **{{ post.date | date: "%Y-%m-%d" }}**: [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
