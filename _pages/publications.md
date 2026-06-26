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

<h2 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.3rem; margin-bottom: 1.5rem; margin-top: 2rem;">Journal Papers</h2>
{% bibliography --query @article %}

<h2 style="font-size: 1.5rem; font-weight: 700; border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.3rem; margin-bottom: 1.5rem; margin-top: 2.5rem;">Conference Papers</h2>
{% bibliography --query @inproceedings %}

</div>
