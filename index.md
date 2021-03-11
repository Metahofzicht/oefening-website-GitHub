---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: defalt
title: "Learning how to build websites with Jekyl"
---

## Description
{{ site.description }}

{% assign lead = site.team_members |where:"role", "project lead" | first %}
The project is led by {{ lead.name }}.
[See our full team](/about).

More details about the project is on the [About Page](/about)
go to find more info on me {% include contact.html %}

See some [examples of our work]({{ page.lesson-example }})
