---
title: "Research"
layout: gridlay
sitemap: false
permalink: /zh/research/
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

# 研究

<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  我们的研究聚焦于连续变量量子计算框架的前沿探索与交叉应用，致力于突破经典计算在复杂问题中的性能瓶颈。研究重点涵盖连续变量量子计算的基础理论及算法优化（如量子搜索的高效实现）、量子强化学习的动态决策模型构建、量子图像处理的高维信息编码与并行加速技术，以及创新性设计免拷贝（duplication-free）的量子神经网络以提升资源效率。总体目标是通过融合量子计算优势与机器学习、图像处理等领域的核心需求，发展可扩展的量子智能算法体系，推动量子计算在优化、人工智能及大数据处理等场景中的实用化进程。
  </div>

</div>

<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  <h4>免拷贝量子神经网络</h4> 
  <div class="text-center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/dqnn_zh.png" alt="描述图片内容" style="width: 600px; height: 350px; object-fit: contain;"/>
  </div>
 免拷贝量子神经网络（Duplication-free Quantum Neural Network, DQNN）通过结合单个量子寄存器与经典Sigmoid函数引入非线性，摒弃了传统量子神经网络依赖数据复制的冗余设计。其采用多组浅层变分量子电路及局部可观测量处理量子态，并通过经典非线性后处理实现高效学习，仅需与经典数据维度对数级（&#36;\log d&#36;）的量子比特。该模型基于&#36;L^2&#36;范数下的通用近似定理严格证明了其表达能力，实验表明其在回归、分类任务中相对误差显著低于QCL和CCQ模型，噪声鲁棒性提升约30%，分类准确率达97.6%，并在量子相变识别（准确率99.1%）等场景中验证了实用性，为近中期量子设备的实际部署提供了资源高效且理论完备的解决方案。
  </div>
</div>