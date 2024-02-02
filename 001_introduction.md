---
layout: default
title: Introduction
number: 001
---
# Introduction

This edition presents a model plan for a district post office in the Russian empire, from 1782.  The image presented here was created by archivists in the Russian State Historical Archive (RGIA) in the early 2010s. The original document--shot here as a photograph--can be found in the papers of the imperial Russian postal department's archive, RGIA f. 1289 op. 1 d. 30, p. 17a.  The plan was is signed (center) by Nikolai Aleksandrovich L'vov, its lead architect.

This edition's text and scholarly apparatus are all by John Randolph, Department of History, University of Illinois Urbana-Champaign.

I am adding some stuff here as a test. 

{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'introduction'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.order == '01'" %} 

{% include media.html pages=intro_images %} 
{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'introduction'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.order == '01'" %} 

{% include media.html pages=intro_images %}
{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'introduction'" | where_exp: "item", "item.media_type == 'image'" |  where_exp: "item", "item.order == '01'" %} 

{% include media.html pages=intro_images %}
