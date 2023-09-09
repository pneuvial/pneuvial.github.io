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

<h1>Journal papers</h1>

{% bibliography --query @article[category!=popscience & category!="to appear"] %}

<h1>Book chapters</h1>

{% bibliography --query @incollection%}

<h1>Popular science (in French)</h1>

{% bibliography --query @article[category=popscience] | @inbook[category=popscience] %}

<h1>Technical reports and theses</h1>

{% bibliography --query @techreport|@mastersthesis|@phdthesis %}

</div>
