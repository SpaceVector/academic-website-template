---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research


<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  Our research focuses on cutting-edge exploration and cross-disciplinary applications of continuous-variable quantum computing frameworks, aiming to overcome performance limitations of classical computing in complex problem-solving. Key research priorities include advancing fundamental theories and algorithmic optimizations in continuous-variable quantum computing (e.g., efficient implementations of quantum search), constructing dynamic decision-making models for quantum reinforcement learning, developing high-dimensional information encoding and parallel acceleration techniques for quantum image processing, and innovatively designing duplication-free quantum neural networks to enhance resource efficiency. The overarching objective is to integrate quantum computational advantages with core demands in machine learning, image processing, and related fields, thereby establishing a scalable quantum intelligent algorithm framework. This initiative seeks to accelerate the practical deployment of quantum computing in optimization, artificial intelligence, and big data processing scenarios.
  </div>

</div>

<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  <h4>The duplication-free quantum neural network</h4> 
  <div class="text-center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/dqnn.png" alt="描述图片内容" style="width: 600px; height: 350px; object-fit: contain;"><br/>
  </div>
 The duplication-free quantum neural network (DQNN) introduces nonlinearity by integrating a single quantum register with classical sigmoid functions, thereby eliminating the redundant designs in conventional quantum neural networks that rely on data duplication. This architecture employs multiple shallow variational quantum circuits and local observables for quantum state processing, coupled with classical nonlinear post-processing to achieve efficient learning, requiring only a logarithmic number of quantum bits &#36;\log d&#36; relative to classical data dimensionality. Rigorously grounded in the universal approximation theorem under the L²&#36;L^2&#36;-norm framework, the model's expressive power has been formally proven. Experimental evaluations demonstrate its superior performance with significantly lower relative errors in regression and classification tasks compared to QCL and CCQ benchmarks, exhibiting approximately 30% enhancement in noise robustness and achieving 97.6% classification accuracy. Practical validation through quantum phase transition identification (99.1% accuracy) further confirms its applicability. This resource-efficient and theoretically sound framework provides a viable solution for practical deployment on near-term quantum devices.
  </div>
</div>
