---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
fa-icon: book
---

<div class="publications">


<h1>Preprints and submitted manuscripts</h1>

{% bibliography --query @misc[category=submitted] %}

<h1>Conference papers</h1>

{% bibliography --query @inproceedings %}

<h1>Journal papers</h1>

{% bibliography --query @article[category!=popscience] %}

<h1>Book chapters</h1>

{% bibliography --query @incollection[category!=popscience] %}

<h1>Popular science (mosttly in French)</h1>

{% bibliography --query @article[category=popscience] | @incollection[category=popscience] %}

<h1>Technical reports and theses</h1>

{% bibliography --query @techreport|@mastersthesis|@phdthesis %}

</div>
