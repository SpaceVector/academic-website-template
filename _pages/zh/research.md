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
  <img src="{{ site.url }}{{ site.baseurl }}/images/dqnn.png" alt="描述图片内容"/><br/>
  </div>
  该模型使用多个浅层变分线路及多个局部可观测量对量子数据进行处理，并通过对测量结果进行非线性经典后处理，从而可以有效解决学习问题。其特点是可以通过利用多个浅层变分量子线路与简单的经典后处理来高效生成量子神经网络的非线性性(Nonlinearity)，同时仅需要相较于经典数据维度指数少的量子比特。
  免拷贝量子神经网络（DQNN）通过结合单个量子寄存器和经典Sigmoid函数引入非线性，避免了传统量子神经网络（如QCL和CCQ）需要复制量子数据导致的资源消耗问题。其设计采用变分量子电路和多个局域可观测量，通过理论证明了其在&#36;L^2&#36;范数下的通用近似能力，显著减少了量子比特数和电路深度，从而降低噪声影响。实验表明，DQNN在回归、分类任务及噪声环境下的性能优于现有方法，并在经典和量子学习问题中展现出应用潜力，为近中期量子设备的实际部署提供了高效解决方案。
  </div>
</div>