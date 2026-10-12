---
layout: page
permalink: /publications/
title: publications
description: selected publications in reversed chronological order.
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>First-author</h2>
{% bibliography --query @*[author_position=first] %}

<h2>Co-authored</h2>
{% bibliography --query @*[author_position=co] %}

</div>
