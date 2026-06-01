---
title: MS-4019 Transform your everyday business processes with agents
permalink: index.html
layout: home
---

This page lists exercises associated with Microsoft skilling content on [Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/implement-no-code-copilot-agents-microsoft-365-sharepoint/) for **MS-4019: Transform your everyday business process with agents**.

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
{% for activity in labs  %}
- [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})
{% endfor %}
