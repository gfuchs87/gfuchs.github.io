---

layout: page
permalink: /publications/
title: publications
description: My books, volumes, articles, and upcoming work.
nav: true
nav_order: 2
---
<div class="publications">

  <!-- 1. Coming Soon Section -->
  <h2 class="category">Coming Soon</h2>
  {% bibliography -f papers -q @*[category=coming_soon]* %}

  <!-- 2. Books Section -->
  <h2 class="category">Books</h2>
  {% bibliography -f papers -q @book %}

  <!-- 3. Edited Volumes Section -->
  <h2 class="category">Edited Volumes</h2>
  {% bibliography -f papers -q @*[category=edited_volume]* %}

  <!-- 4. Articles Section -->
  <h2 class="category">Articles</h2>
  {% bibliography -f papers -q @article %}

</div>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->


<div class="publications">

{% bibliography %}

</div>
