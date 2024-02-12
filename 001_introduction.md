---
layout: default
title: Introduction
number: 001
---
# Introduction

In 1782, the Russian nobleman Nikolai L'vov prepared a "Model Plan for a District Post-Yard."  This drawing is preserved in St. Petersburg in a clean manuscript copy held by the Russian State Historical Archive[^1].  As a source, L'vov's plan illuminates an important juncture in the history of imperial Russian communications.  It shows how one of the leading architects of the Russian Enlightenment imagined housing one of the Russian Empire's oldest practices--relay obligation--within the structures of the empire's newly-reformed provincial order.

This micro-edition presents an annotated digital copy of L'vov's plan, based on an archival photograph taken in 2010.  An accompanying essay situates the drawing within L'vov's work, the grand reform of local administration undertaken by Catherine II in the 1770s and 1780s, and the longer history of relay service in the Russian Empire.  

The edition is meant to be used by researchers, teachers, students, and the public at large.  It licensed by the author for free use (with credit) under a CC BY 4.0 license.

Cite this edition:

Randolph, John. “Model Plan for a District Post-Yard, Russian Empire (1782).” *Insert access date, e.g. 'Accessed February 12, 2024'*. *Insert page URL, e.g. https://jwr12.github.io/imperial_russian_post_office_1782/*.


{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.order == '01'" %} 

{% include media.html pages=intro_images %} 

[^1]: "O postroike v Gubernskikh i Uezdnykh gorodov gorodakh dlia Pochtovykh Kontor i pochmeisterov domov," RGIA f. 1289, op. 1, d. 30, l. 17a.
