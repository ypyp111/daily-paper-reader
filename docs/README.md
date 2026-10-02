<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-02
- 运行时间：2026-10-02 22:46:05 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今天扫完 17 篇（精读 6、速读 11），主线集中在物理信息神经网络（PINN）与神经算子训练效率的优化上。

最值得看的是两篇 8.0 分精读：《Tensor-Train Compressed Separable PINNs》用张量列压缩+曲率感知优化攻高维参数 PDE，《Preconditioned Physics-Informed Neural Operator Training》则从预条件角度提速算子训练；速读里 Transolver-σ 的谱—物理联合子空间建模、PE-EK-PINN 的演化核思路同属这一方向。

普通读者可先挑其中一篇精读理解"压缩/预条件如何降低高维 PDE 训练成本"，再顺着速读标题扫一遍谱方法与自适应核的用法即可。
- 详情：[/202610/02/README](/202610/02/README)

### 精读区论文标签
1. [Tensor-Train Compressed Separable PINNs: A Curvature-Aware Optimization Framework for Parametric PDEs in High Dimensions](/202610/02/2609.36165v1-tensor-train-compressed-separable-pinns-a-curvature-aware-optimization-framework-for-parametric-pdes-in-high-dimensions)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：面向参数PDE可分离PINN的曲率感知二阶优化框架
2. [Preconditioned Physics-Informed Neural Operator Training](/202610/02/2609.36216v1-preconditioned-physics-informed-neural-operator-training)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：预条件物理信息神经算子训练与网格无关条件数
3. [HeurEvo: Agentic Evolution of Hybrid Solver-Augmented Heuristics for Time-Critical Mathematical Optimization](/202610/02/2609.36303v1-heurevo-agentic-evolution-of-hybrid-solver-augmented-heuristics-for-time-critical-mathematical-optimization)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：利用AI智能体与执行反馈自动发现算法的智能体式启发式设计
4. [CI-PINN: Causal Integral Physics-Informed Neural Network for Solving Evolution Equations](/202610/02/2609.36615v1-ci-pinn-causal-integral-physics-informed-neural-network-for-solving-evolution-equations)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：求解演化方程的因果积分PINN新架构
5. [Interpolating Neural Operator (INO): A Data-Free and Efficient Approach for Learning PDE Solution Operators](/202610/02/2609.36701v1-interpolating-neural-operator-ino-a-data-free-and-efficient-approach-for-learning-pde-solution-operators)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：在PDE弱形式上训练的无数据神经算子求解解算子
6. [SimpleEvol: An Agent-Loop Framework for LLM-Driven Automated Heuristic Design with Minimal Human Priors](/202610/02/2609.37172v2-simpleevol-an-agent-loop-framework-for-llm-driven-automated-heuristic-design-with-minimal-human-priors)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：智能体循环框架实现大模型驱动的自动启发式设计与算法发现

### 速读区论文标签
1. [Transolver-$σ$: Joint Spectral-Physical Subspace Modeling for Neural PDE Solving](/202610/02/2609.37279v1-transolver--joint-spectral-physical-subspace-modeling-for-neural-pde-solving)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：作为数值仿真高效代理的神经PDE求解器
2. [PE-EK-PINN: Physics Embedding with Evolving Kernel for Scalable Physics-Informed Neural Networks](/202610/02/2609.38023v1-pe-ek-pinn-physics-embedding-with-evolving-kernel-for-scalable-physics-informed-neural-networks)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：面向波动PDE的物理信息神经网络，采用演化核物理嵌入
3. [Component-Aware Feedback for Self-Evolving Programs](/202610/02/2609.38639v1-component-aware-feedback-for-self-evolving-programs)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：基于组件归因反馈的LLM引导演化程序合成
4. [Self-Evolving Algorithm-Design Agents: Escaping In-Context Evolutionary Stagnation via Population-Curated Policy Optimization](/202610/02/2609.38757v1-self-evolving-algorithm-design-agents-escaping-in-context-evolutionary-stagnation-via-population-curated-policy-optimization)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：具备参数化自演化的LLM算法设计智能体
5. [The limits of exactness: On the failure of automatic differentiation in physics-informed machine learning](/202610/02/2609.33078v2-the-limits-of-exactness-on-the-failure-of-automatic-differentiation-in-physics-informed-machine-learning)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：物理信息机器学习中自动微分的失效
6. [Learning in the Transverse Subspace: A Minimal Representation for Divergence-Free Operator Learning](/202610/02/2609.35884v1-learning-in-the-transverse-subspace-a-minimal-representation-for-divergence-free-operator-learning)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：面向无散度PDE场与不可压流的神经算子学习
7. [BiFE: Search-Efficient Discovery of CPU-Only Branching Policies via LLM-based Bi-Fidelity Evolution](/202610/02/2609.36735v1-bife-search-efficient-discovery-of-cpu-only-branching-policies-via-llm-based-bi-fidelity-evolution)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：基于LLM演化的分支策略合成，属于自动算法发现
8. [SINO: Scale-Invariant Neural Operator](/202610/02/2609.36890v1-sino-scale-invariant-neural-operator)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：面向粗网格PDE闭合的尺度不变神经算子
9. [Streamlined Reflective Evolution for Task-Adaptive Self-Refinement Pipelines](/202610/02/2609.32458v1-streamlined-reflective-evolution-for-task-adaptive-self-refinement-pipelines)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：LLM引导的流水线结构与指令演化
10. [SkillVine: Agent Skill Evolution via Branching Exploration](/202610/02/2609.32731v1-skillvine-agent-skill-evolution-via-branching-exploration)  
   标签：评分：6.0/10、query:ai-pde
   evidence：通过分支探索实现智能体技能自动演化
11. [SCOPE: Observation-Conditioned Full-Target Prediction for Sparse PDE Inference](/202610/02/2609.36527v2-scope-observation-conditioned-full-target-prediction-for-sparse-pde-inference)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：从稀疏PDE观测进行全场预测的神经算子式方法


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
