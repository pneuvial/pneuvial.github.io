---
layout: page
permalink: /sanssouci.html
title: SansSouci
fa-icon: cogs
description: Post hoc inference via multiple testing. Project ANR-16-CE40-0019 (2016-2021).
---

<img src="{{ site.baseurl }}/assets/img/SansSouci-sketch.png" style="width:100%">

### Rationale of the project

The number and size of available data sets of different types has increased dramatically over the past twenty years. This “data deluge” has been accompanied by a shift from hypothesis-driven research to data-driven research in many scientific fields including astronomy, biology, genetics, or medicine. Analyzing and interpreting such data require innovative approaches for the simultaneous testing of a large number of biological hypotheses.

This project gathers specialists of multiple testing theory, high-dimensional data analysis, and genomics. It aims at filling a gap between the statistical guarantees provided by state-of-the-art multiple testing procedures and the actual needs of practitioners.

We propose to develop "post hoc" procedures (in the sense of Goeman and Solari, *Statistical Science*, 2011), which provide confidence statements on the number or proportion of false positives among any subset of hypotheses chosen by the user after analyzing the data. Both theoretical and applied aspects of post hoc multiple testing will be covered.

### Main events

* Mar 3-4, 2022: Workshop "Post-selection inference for genomic and neuroimaging data", Toulouse. With A. Blain, G. Blanchard, S. Davenport, G. Durand, N. Enjalbert-Courrech, J. Gonzales-Delgado, A. Marandon, C. Maugis-Rabusseau, I. Meah, P. Neuvial, L. Risser, E. Roquain, M. Perrot-Dockès, B. Thirion.

* Jun 15-19, 2020: Participation to the scientific committee of the *[Mathematical Methods of Modern Statistics 2](https://conferences.cirm-math.fr/2146.html)* conference at CIRM (Luminy, France). This conference has been virtualized. 

* Mar 10-12, 2020: ANR meeting, Paris. With G. Blanchard, M. Perrot-Dockès, P. Neuvial, E. Roquain.

* Dec 12-15, 2019: Participation of M. Perrot-Dockès, P. Neuvial, E. Roquain and F. Villers at [MCP 2019](https://mcp2019.com.tw/) in Taiwan. Organization of a session on post-selection inference and multiple testing.

* Apr 8, 2019: ANR meeting, Paris. With G. Blanchard, G. Durand, M. Perrot-Dockès, P. Neuvial, G. Rigaill, E. Roquain, B. Sadacca.

* Feb 7-9, 2018: Workshop "Post-selection inference and multiple testing" in Toulouse. This event is part of a thematic semester [Mathematics and Computer Science for biology](http://www.cimi.univ-toulouse.fr/mib/en/node/619) organized by [CIMI](http://www.cimi.univ-toulouse.fr), the International Centre for Mathematics and Computer Science in Toulouse.

* January 6, 2017: Kick-off meeting, Evry.

### Preprints

{% bibliography --query @misc[category=submitted]  --file sansSouci %}

### Papers

{% bibliography --query @article]  --file sansSouci %}


### Participants

| **Toulouse** ||
|[François Bachoc](https://www.math.univ-toulouse.fr/~fbachoc/)|[Université Paul Sabatier](http://www.univ-tlse3.fr/), [Institut de Mathématiques de Toulouse](http://www.math.univ-toulouse.fr)|
| Alexandre Blain | [Institut de Mathématiques de Toulouse](http://www.math.univ-toulouse.fr) and [Inria Parietal](https://team.inria.fr/parietal/) |
| Nicolas Enjalbert-Courrech | [Institut de Mathématiques de Toulouse](http://www.math.univ-toulouse.fr) |
| Maria Martinez | [INSERM UMR 1043](http://www.cptp.inserm.fr) |
| [Pierre Neuvial]({{ site.baseurl }}) | [CNRS](http://www.cnrs.fr), [Institut de Mathématiques de Toulouse](http://www.math.univ-toulouse.fr) |

<br>

| **Evry** ||
| [Cyril Dalmasso](http://www.math-evry.cnrs.fr/members/cdalmasso/) | [Université d'Evry](http://www.univ-evry.fr/en/index.html), [Laboratoire de Mathématiques et Modélisation d'Evry](http://www.math-evry.cnrs.fr)|
| Jean-François Deleuze | [Centre National de Recherche en Génomique Humaine](http://www.cng.fr) |
| Edith Le Floch | [Centre National de Recherche en Génomique Humaine](http://www.cng.fr) |
| [Guillem Rigaill](http://www.math-evry.cnrs.fr/members/grigaill/welcome) | INRAE, [Laboratoire de Mathématiques et Modélisation d'Evry](http://www.math-evry.cnrs.fr) |
| Franck Samson | INRAE, [Laboratoire de Mathématiques et Modélisation d'Evry](http://www.math-evry.cnrs.fr) |


<br>

| **Paris** ||
| [Sylvain Delattre](http://www.lpsm.paris/dw/doku.php?id=users:delattre:index) | Sorbonne Université, [Laboratoire de Probabilités, Statistique et Modélisation](http://www.lpsm.paris)|
| [Etienne Roquain](https://etienneroquain-81.webself.net) | Sorbonne Université, [Laboratoire de Probabilités, Statistique et Modélisation](http://www.lpsm.paris)|
| [Marie Perrot-Dockès](https://marie-perrotdockes.github.io/) | Université de Paris, [MAP5](MAP5 - Mathématiques Appliquées à Paris 5 - MAP5-UMR 8145)|
| [Benjamin Sadacca](https://science.curie.fr/members/benjamin-sadacca/) | [Institut Curie](https://institut-curie.org/), [Immune responses to cancer](https://institut-curie.org/team/amigorena/)|


<br>

| **Orsay**||
| [Gilles Blanchard](https://www.imo.universite-paris-saclay.fr/~blanchard/) | Université Paris-Saclay,  Institut de Mathématiques d'Orsay |
| [Guillermo Durand](https://durandg12.github.io/) | Université Paris-Saclay,  Institut de Mathématiques d'Orsay |

<br>

### Open source software

- The R package [sanssouci](https://pneuvial.github.io/sanssouci/) implements most of the methods developed in the course of the project. The R package [sanssouci.data](https://github/pneuvial/sanssouci.data/) stores examples of genomic and neuroimaging data that can be used within the main package. A [Python implementation](https://github/pneuvial/sanssouci.python/) is also availble since 2021.

- The R package [sanssouci.hmm](https://github.com/Marie-PerrotDockes/sanssouci.hmm) implements the methods developed in Perrot-Dockès *et al* (2021){% cite PBNR --file sansSouci.bib %}.

- The [IIDEA](https://shiny-iidea-sanssouci.apps.math.cnrs.fr/) Shiny application implements interactive differential analyses (volcano plots and set enrichment analyses).

- The R package [discreteFDR](https://CRAN.R-project.org/package=DiscreteFDR) implements the procedures adapted to discrete tests, as described in Döhler *et al* (2018){% cite doehler2018 --file sansSouci.bib %} and Durand *et al* (2019){% cite durand2019discretefdr --file sansSouci.bib %}.

### Funding

[<img src="{{ site.baseurl }}/assets/img/logos/labelANR.png" alt="Funded by ANR" height="80">](http://www.agence-nationale-recherche.fr/)
[<img src="{{ site.baseurl }}/assets/img/logos/CNRS.png" alt="CNRS" height="80">](http://www.cnrs.fr/)
[<img src="{{ site.baseurl }}/assets/img/logos/CIMI.png" alt="Labex CIMI" height="80">](http://www.cimi.univ-toulouse.fr)

* [ANR (French National Research Agency)](http://www.agence-nationale-recherche.fr/?Project=ANR-16-CE40-0019): Young researcher grant of 192 k€ (2016-2020).
* [CNRS (National Center for Scientific Research)](http://www.cnrs.fr): [PEPS FaSciDo](https://www.cnrs.fr/ins2i/spip.php?article1183) (12k€ in 2015, 5k€ in 2016)
* [CIMI (International Centre for Mathematics and Computer Science in Toulouse)](http://www.cimi.univ-toulouse.fr): Sponsorship and organization of the Feb. 2018 workshop

<!-- *'SansSouci' has been identified as one of the best acronyms for ANR projects in 2016 by the [Agence Nationale de l'Excellence Scientitique (ANES)](http://excellagence.fr/)*. See the [official announcement on twitter](https://twitter.com/Excellagence/status/820206995655524352). -->


