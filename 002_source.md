---
layout: default
title: The Source
number: 002
---

# The Source

Model District Post Office
<!-- <iframe width="420" height="315" src="https://www.youtube.com/watch?v=EmSrQCDsMv4&t=1282s&ab_channel=BillRaymond" frameborder="0" ></iframe> -->

{% assign source = site.mindoc_media | sort: "order" | where_exp: "lvov_model_plan_1782_rev.jpg", "item.page == 'source'" | where_exp: "lvov_model_plan_1782_rev.jpg", "item.media_type == 'image'" | where_exp: "lvov_model_plan_1782_rev.jpg", "item.order == '01'"%}

{% include media.html pages=source %}






