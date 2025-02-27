---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /zh/Publications/
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
## **期刊**
{% bibliography --query @unpublished @article %}
</div>

<div class="jumbotron">
## **会议**
{% bibliography --query @inproceedings %}
</div>