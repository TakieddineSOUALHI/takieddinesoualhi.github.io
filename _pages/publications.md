---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

<h2 class="bibliography">Journal Papers</h2>
{% bibliography --query @article %}

<h2 class="bibliography">Conference Papers</h2>
{% bibliography --query @inproceedings %}

</div>
