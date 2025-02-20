---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /Publications/
# years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.container-fluid{
    max-width: 1200px;
}
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
    background-color:transparent;
}
</style>

<div class="jumbotron">
## **Publications**
{% bibliography --query @unpublished @article  %}
</div>
