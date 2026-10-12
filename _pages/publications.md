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

<p>Full publications list on <a href="https://scixplorer.org/public-libraries/Eb-XcR2BQCGhyIXMlEHfWw" target="_blank" rel="noopener">SciX</a>.</p>

{% bibliography --query @*[author_position=first] %}


</div>
