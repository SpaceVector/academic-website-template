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
.jumbotron{
  border-radius: 25px;
}
</style>

# 研究

<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  我们的研究聚焦于连续变量量子计算框架的前沿探索与交叉应用，致力于突破经典计算在复杂问题中的性能瓶颈。研究重点涵盖连续变量量子计算的基础理论及算法优化（如量子搜索的高效实现）、量子强化学习的动态决策模型构建、量子图像处理的高维信息编码与并行加速技术，以及创新性设计免拷贝（duplication-free）的量子神经网络以提升资源效率。总体目标是通过融合量子计算优势与机器学习、图像处理等领域的核心需求，发展可扩展的量子智能算法体系，推动量子计算在优化、人工智能及大数据处理等场景中的实用化进程。
  </div>

</div>

<h4>免拷贝量子神经网络</h4>
<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  <div class="text-center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/dqnn_zh.png" alt="描述图片内容" style="width: 600px; height: 350px; object-fit: contain;"/>
  </div>
 免拷贝量子神经网络（Duplication-free Quantum Neural Network, DQNN）通过结合单个量子寄存器与经典Sigmoid函数引入非线性，摒弃了传统量子神经网络依赖数据复制的冗余设计。其采用多组浅层变分量子电路及局部可观测量处理量子态，并通过经典非线性后处理实现高效学习，仅需与经典数据维度对数级（&#36;\log d&#36;）的量子比特。该模型基于&#36;L^2&#36;范数下的通用近似定理严格证明了其表达能力，实验表明其在回归、分类任务中相对误差显著低于QCL和CCQ模型，噪声鲁棒性提升约30%，分类准确率达97.6%，并在量子相变识别（准确率99.1%）等场景中验证了实用性，为近中期量子设备的实际部署提供了资源高效且理论完备的解决方案。
  </div>
</div>

<h4>连续变量量子搜索算法</h4>
<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  <div class="text-center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/qcsa.png" alt="描述图片内容" style="width: 600px; height: 350px; object-fit: contain;"/>
  </div>
 我们提出了一种基于连续变量（CV）量子计算的固定点量子连续搜索算法，用于解决连续搜索问题（CSPs），在优化、物理和工程领域具有广泛适用性。通过设计包含参数化旋转算子的Grover迭代结构，算法在连续域中实现了无需离散化的高效搜索，并证明了其查询复杂度为最优的&#36;O(\frac{1}{\sqrt{\lambda}})&#36;，其中&#36;\lambda&#36;为目标解空间与初始搜索空间的测度比。研究进一步建立了任意量子算法解决CSPs的查询复杂度下界&#36;\frac{1}{2\sqrt{2}}[(1+\sqrt{p}−\sqrt{1-p})\sqrt{n-2}]&#36;，验证了该算法的最优性。此外，我们还构建了适用于连续优化的量子Oracle框架，通过相位估计技术将梯度信息编码至辅助量子态，并成功应用于Rosenbrock函数等非凸优化问题及连续谱算子的特征值求解，展示了算法在收敛性和抗噪性方面的优势。该工作为连续变量量子计算在复杂优化问题中的应用提供了理论框架和实现方案。
  </div>
</div>

<h4>连续动作空间中的量子强化学习</h4>
<div class="jumbotron">
  <div class="col-md-12 col-sm-12">
  <div class="text-center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/qrl.jpg" alt="描述图片内容" style="width: 600px; height: 350px; object-fit: contain;"/>
  </div>
 强化学习应用于量子系统时，尤其是在处理连续动作空间（continuous action spaces）问题时面临着显著挑战。这类问题的动作选择并非离散有限集合，而是存在于连续谱中，导致计算复杂度呈指数级增长。本研究提出了一种适用于连续动作空间的量子深度确定性策略梯度（Deep Deterministic Policy Gradient, DDPG）算法。简而言之，该方法通过变分量子电路（variational quantum circuits）构建量子神经网络，以学习将量子系统从任意初始态驱动至目标态所需的最优量子操作序列（即控制脉冲）。其关键创新在于，算法经过单次训练后即可针对任意目标态生成适配的控制序列，无需在每次需求新目标态时重新训练。本文通过单量子比特和双量子比特系统的数值模拟验证了该方法的有效性，并进一步应用于解决量子本征值问题——这类问题对于理解量子系统基本性质具有核心意义。
  </div>
</div>


