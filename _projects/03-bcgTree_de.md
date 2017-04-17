---
title: bcgTree
github: https://github.com/molbiodiv/bcgTree
logo: https://github.com/molbiodiv/bcgTree/raw/master/doc/bcgTree.png
permalink: /de/projects/bcgTree
lang: de
ref: bcgtree
---

Ein Werkzeug um automatisiert die Phylogenie von Bakterien zu rekonstruieren.
Dabei werden sogenannte "single-copy core genes", also Gene die in fast allen Bakterien genau einmal vorkommen, verwendet.

Phylogenetische Bäume für Bakterien werden häufig mit Hilfe des Standardmarkers 16S rDNA berechnet.
Durch die Verfügbarkeit großer Mengen genomischer DNA ist es möglich andere und mehr Marker zu verwenden um robustere Bäume zu erhalten.
Die Auswahl geeigneter Gene kann jedoch eine Herausforderung sein.
Daher nutzt `bcgTree` eine vorberechnete Liste von 107 "single-copy core genes".
Die Proteine zu diesen Genen werden automatisch in den Eingabedateien gefunden und zur Rekonstruktion des Baums verwendet.

![Workflow](/images/bcgTree_workflow.svg)

Der Quelltext ist auf [GitHub]({{page.github}}).
Ein Artikel der `bcgTree` beschreibt wurde in [Genome](https://www.nrcresearchpress.com/doi/abs/10.1139/gen-2015-0175) veröffentlicht.

