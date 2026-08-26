<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-26
- 运行时间：2026-08-26 20:34:59 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日聚焦神经网络偏微分方程（PDE）代理模型的全局-局部处理与混合物理信息框架，共扫描17篇论文。  
最值得关注：两篇9.0分精读分别揭示PDE代理需兼顾全局与局部处理，以及混合PINN可高效计算广义非均匀分层介质中的SH波色散关系。  
下一步可结合“一步演化+误差界引导”的外推思路，验证其在长期PDE预测中的实际效果。
- 详情：[/202608/26/README](/202608/26/README)

### 精读区论文标签
1. [Read, Write, Relax: Why Neural PDE Surrogates Need Both Global and Local Processing](/202608/26/2608.21677v1-read-write-relax-why-neural-pde-surrogates-need-both-global-and-local-processing)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：分析神经PDE代理模型，统一全局与局部处理；直接讨论PDE神经代理建模。
2. [A Hybrid Physics-Informed Neural Network Framework for Computing Dispersion Relations of SH Waves in Generalized Hetrogeneous Layered Media with Applications](/202608/26/2608.22353v1-a-hybrid-physics-informed-neural-network-framework-for-computing-dispersion-relations-of-sh-waves-in-generalized-hetrogeneous-layered-media-with-applications)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：用混合物理信息神经网络计算非均匀层状介质中SH波频散关系，直接涉及PINN求解波动问题。
3. [Structure-preserving generalized transferable neural networks for the Cahn-Hilliard equation](/202608/26/2608.23980v1-structure-preserving-generalized-transferable-neural-networks-for-the-cahn-hilliard-equation)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：GTransNet-BDF格式对Cahn-Hilliard方程保持质量守恒和能量稳定性
4. [Real-time inverse solutions via neural matrix operators](/202608/26/2608.24833v1-real-time-inverse-solutions-via-neural-matrix-operators)  
   标签：评分：9.0/10、query:sci-ml-agent
   evidence：神经算子作为PDE约束反问题的实时代理模型，面向数字孪生
5. [Hype Meets Reality: Large Language Models as Mutators in Search-based Automated Program Repair of Simulink-Stateflow Models](/202608/26/2608.19347v1-hype-meets-reality-large-language-models-as-mutators-in-search-based-automated-program-repair-of-simulink-stateflow-models)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：在基于搜索的程序修复中用LLM作为变异算子，直接应用LLM引导的演化搜索
6. [Closed-loop AI achieves certifiable engineering design](/202608/26/2608.21976v1-closed-loop-ai-achieves-certifiable-engineering-design)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：将LLM代理耦合工程求解器实现可认证设计，涵盖流体动力学约束

### 速读区论文标签
1. [One-Step Evolution for Long-Time Extrapolation: An Error-Bound-Informed and Prior-Guided Neural Residual Framework for Autonomous PDEs](/202608/26/2608.22026v1-one-step-evolution-for-long-time-extrapolation-an-error-bound-informed-and-prior-guided-neural-residual-framework-for-autonomous-pdes)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：面向自治PDE求解与长期外推的误差界知情神经残差深度学习框架
2. [LongWoF-Bench: Evaluating EvoMap Genes for Verifiable Long-Workflow Tasks](/202608/26/2608.23200v1-longwof-bench-evaluating-evomap-genes-for-verifiable-long-workflow-tasks)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：面向可验证长工作流的EvoMap基因基准，契合LLM引导演化合成与可执行验证
3. [LongWoF-Bench: Evaluating EvoMap Genes for Verifiable Long-Workflow Tasks](/202608/26/2608.23200v2-longwof-bench-evaluating-evomap-genes-for-verifiable-long-workflow-tasks)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：EvoMap将验证器确认的执行轨迹整合为可复用基因，用于可验证长工作流任务
4. [Physics-Integrated Operator Learning via Gaussian Splatting Representations](/202608/26/2608.24049v1-physics-integrated-operator-learning-via-gaussian-splatting-representations)  
   标签：评分：8.0/10、query:sci-ml-agent
   evidence：面向时空偏微分方程的神经算子代理模型，通过表示级物理集成提升长时程预测。
5. [Information fusion and machine learning for sensitivity analysis using physics knowledge and experimental data](/202608/26/2608.17248v1-information-fusion-and-machine-learning-for-sensitivity-analysis-using-physics-knowledge-and-experimental-data)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：结合物理知识与实验数据的物理信息机器学习（深度网络和高斯过程）用于全局敏感性分析
6. [Physics-Informed Learning of Probabilistic Gegenbauer Reconstruction for Transport-Dominated Problems](/202608/26/2608.18001v1-physics-informed-learning-of-probabilistic-gegenbauer-reconstruction-for-transport-dominated-problems)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：面向输运主导PDE重建参数自动选择的物理信息机器学习框架
7. [Composing Flow-Matching Energies with Known Physics: Generation, OOD Detection, and Inversion on PDE Fields](/202608/26/2608.18004v1-composing-flow-matching-energies-with-known-physics-generation-ood-detection-and-inversion-on-pde-fields)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：将物理定律与流匹配能量组合用于PDE场生成与反演
8. [Evo-GTransNet for Parabolic PDEs: A Fixed-Feature Galerkin Method of Lines with Quadrature-Mass Orthonormalization](/202608/26/2608.19615v1-evo-gtransnet-for-parabolic-pdes-a-fixed-feature-galerkin-method-of-lines-with-quadrature-mass-orthonormalization)  
   标签：评分：7.0/10、query:sci-ml-agent
   evidence：用进化型可迁移神经网络求解抛物型偏微分方程，属于神经代理建模与PDE求解。
9. [When Machines Speak: A Unified Generative Framework for Integrating Machine-Native Symbols into Pretrained Large Language Models](/202608/26/2608.19529v1-when-machines-speak-a-unified-generative-framework-for-integrating-machine-native-symbols-into-pretrained-large-language-models)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：扩展大语言模型词汇表以支持机器符号的一等公民生成，助力程序化符号合成任务
10. [Data-Driven Dynamic Algorithm Dispatch with Large Language Models](/202608/26/2608.21584v1-data-driven-dynamic-algorithm-dispatch-with-large-language-models)  
   标签：评分：6.0/10、query:ai-pde
   evidence：利用大语言模型自动发现线性代数算法调度策略，属于AI驱动的数值算法自动发现。
11. [OptiMAS: Automatically Optimize Multi-Agent System](/202608/26/2608.21918v1-optimas-automatically-optimize-multi-agent-system)  
   标签：评分：6.0/10、query:sci-ml-agent
   evidence：通过连续进化自动优化多智能体系统，可迁移到智能体驱动的CFD自动仿真


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
