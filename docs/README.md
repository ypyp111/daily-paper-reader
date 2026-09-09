<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-09
- 运行时间：2026-09-09 21:32:20 UTC
- 运行状态：成功
- 本次总论文数：18
- 精读区：7
- 速读区：11

### 今日简报（AI）
今日扫描18篇论文，精读7篇与速读11篇，重点聚焦物理信息神经网络（PINN）的改进与应用。

最值得关注两个方向：PINN训练中的梯度更新冲突问题（精读9.0分），以及基于PINN的弯曲地形颗粒雪崩动力学建模（精读9.0分）。

建议优先精读这两篇高分论文，打好PINN理论地基，再扩展至速读中的稀疏自编码器与PDE算子学习等前沿工具。
- 详情：[/202609/09/README](/202609/09/README)

### 精读区论文标签
1. [Gradient-Update Mismatch: Rethinking Conflict-Free Training of Physics-Informed Neural Networks](/202609/09/2609.01558v1-gradient-update-mismatch-rethinking-conflict-free-training-of-physics-informed-neural-networks)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：研究PINN梯度冲突与优化器变换导致的无冲突方向失效，直接关于PINN稳定训练
2. [Physics-Informed Neural Networks for Depth-Averaged Granular Avalanche Dynamics on Curved Topography](/202609/09/2609.05542v1-physics-informed-neural-networks-for-depth-averaged-granular-avalanche-dynamics-on-curved-topography)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：将物理信息神经网络应用于弯曲地形上深度平均偏微分方程组的求解，直接契合用PINN解PDE的需求。
3. [A Systematic Analysis of Automatic Differentiation versus Discretization-based Constraints for Physics-Informed PDE Solvers](/202609/09/2609.07437v1-a-systematic-analysis-of-automatic-differentiation-versus-discretization-based-constraints-for-physics-informed-pde-solvers)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：系统比较PINN求解PDE时的自动微分与离散化约束策略，直接对应物理信息神经网络求解PDE
4. [Local gradient neural operator](/202609/09/2609.07752v1-local-gradient-neural-operator)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：面向力学PDE场预测的轻量局域梯度神经算子代理模型
5. [Latent-MoE: Domain-Aware Mixture-of-Experts for PDEs with Multi-Regime Physics](/202609/09/2609.07814v1-latent-moe-domain-aware-mixture-of-experts-for-pdes-with-multi-regime-physics)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：面向空间变化物理的PINN求解提出域感知混合专家架构，直接属于物理信息神经网络解偏微分方程的研究
6. [Physics-informed neural networks for viscoelastic fluid flows around a cylinder in a two-dimensional channel](/202609/09/2609.07861v1-physics-informed-neural-networks-for-viscoelastic-fluid-flows-around-a-cylinder-in-a-two-dimensional-channel)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：用PINN直接求解圆柱绕流粘弹性流PDE，并用Cholesky分解保证正定来稳定训练
7. [Solving the Elastic Wave Equation with Physics-Informed Neural Networks: A Robust and Critical Assessment](/202609/09/2609.07983v1-solving-the-elastic-wave-equation-with-physics-informed-neural-networks-a-robust-and-critical-assessment)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：PINN求解弹性波偏微分方程的鲁棒性批判评估

### 速读区论文标签
1. [PhysSAE: Mechanistic Interpretability with Sparse Autoencoders](/202609/09/2609.07061v1-physsae-mechanistic-interpretability-with-sparse-autoencoders)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：用稀疏自编码器与因果干预研究PINN在PDE族中编码的物理特征，紧扣PINN主题
2. [Two-Scale Localized PCA-Net: Coarse-Global and Local-Residual Representations for Artifact-Reduced PDE Operator Learning](/202609/09/2609.08034v1-two-scale-localized-pca-net-coarse-global-and-local-residual-representations-for-artifact-reduced-pde-operator-learning)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：面向PDE的神经算子学习采用粗全局与局部残差PCA表示，直接属于偏微分方程神经网络代理建模
3. [Beyond Residuals: Energy based solutions of partial differential equations using scientific machine learning](/202609/09/2609.08239v1-beyond-residuals-energy-based-solutions-of-partial-differential-equations-using-scientific-machine-learning)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：基于能量的科学机器学习PDE求解方法，与物理信息神经网络紧密相关。
4. [Multi-Level-Set-Based Physics-Driven Neural Network to Solve 3-D Inverse Scattering Problems](/202609/09/2609.08594v1-multi-level-set-based-physics-driven-neural-network-to-solve-3-d-inverse-scattering-problems)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：针对三维电磁逆散射的物理驱动神经网络求解器，属于物理信息神经网络求解PDE的应用
5. [HarnessEvolve: Learning from Reference Trajectories for Reliable Agent Self-Evolution](/202609/09/2609.00829v1-harnessevolve-learning-from-reference-trajectories-for-reliable-agent-self-evolution)  
   标签：评分：7.0/10、query:ai-pde
   evidence：从参考轨迹学习并演化智能体技能与执行逻辑，直接相关于科学工作流中的智能体技能演化。
6. [Bi-HYCO: Bi-Objective Cooperative Learning for PDE Parameter Identification under Fragmented Observations](/202609/09/2609.06511v1-bi-hyco-bi-objective-cooperative-learning-for-pde-parameter-identification-under-fragmented-observations)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：耦合物理与合成模型进行PDE参数辨识的双目标协同学习；属于科学机器学习应用
7. [Introductory Notes on Learning$^2$](/202609/09/2609.06546v1-introductory-notes-on-learning2)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：用已知物理变换耦合双表示的机器学习框架，面向流体动力学，属于科学机器学习方法
8. [FSAN: Flow State Attention Network for Aerodynamic Prediction](/202609/09/2609.06660v1-fsan-flow-state-attention-network-for-aerodynamic-prediction)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：面向空气动力学CFD预测的神经代理模型，用流态注意力考虑局部流动差异，匹配PDE神经代理建模需求
9. [Beyond Prompts: Measuring and Optimizing LLM Tool-Agent Harnesses](/202609/09/2609.05736v1-beyond-prompts-measuring-and-optimizing-llm-tool-agent-harnesses)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：固定LLM工具Agent的提示词与中间件优化，可为Agentic CFD提供基础能力
10. [Selective boundary condition reduction via learned error gating](/202609/09/2609.08461v1-selective-boundary-condition-reduction-via-learned-error-gating)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：面向参数化偏微分方程的边界条件选择性简化，用神经网络估计误差并做门控，是PDE求解中的科学机器学习方法
11. [Flexible Spectral-Normalized Neural Gaussian Process for Dynamic Aperture Prediction](/202609/09/2609.08620v1-flexible-spectral-normalized-neural-gaussian-process-for-dynamic-aperture-prediction)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：可扩展科学机器学习不确定性量化方法，应用于加速器动态孔径预测


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
