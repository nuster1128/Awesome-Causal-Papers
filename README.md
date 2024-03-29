# Awesome Causal Papers

For benefiting the research community and promoting causal direction, we organize papers related to causal that published on top conferences recently. Currently, our repository has included:
- `2022`: `NIPS`, `ICLR`, `ICML`, `SIGKDD`, `WWW`, `SIGIR`.
- `2023`: `ICLR`.

We are glad for pointing out our misunderstandings, and welcome to contribute to this repository!

#### What's new:

- 2023/3/29 We add papers from `WWW'22` and `SIGIR'22`.
- 2023/3/13 We add papers from `ICML'22`
- 2023/3/12 We add papers from `SIGKDD'22`.
- 2023/3/7  We add papers from `ICLR'22`. We merge `Causal in QA` into `Causal in NLP`.
- 2023/2/9	We add papers from `ICLR'23` and `NIPS'22`.

## Contents

- [Causal Inference](#Causal-Inference)
- [Causal Discovery](#Causal-Discovery)
- [Causal Representation Learning](#Causal-Representation-Learning)
- [Counterfactual Inference](#Counterfactual-Inference)
- [Causal Application](#Causal-Application)
  - [Causal in RecSys](#Causal-in-RecSys)
  - [Causal in RL](#Causal-in-RL)
  - [Causal in NLP](#Causal-in-NLP)
  - [Causal in CV](#Causal-in-CV)
  - [Causal in Bio](#Causal-in-Bio)
  - [Causal in IR](#Causal-in-IR)

### Causal Inference

**[Causal Inference] Modeling the Data-Generating Process is Necessary for Out-of-Distribution Generalization**. (2023-ICLR) Jivat Neet Kaur, Emre Kiciman, Amit Sharma. 
**TLDR**: Use causal knowledge on data generation to solve OOD problem. (用因果性挖掘数据生成规律以解决分布偏移问题) 

**[Causal Inference] Model-based Causal Bayesian Optimization**. (2023-ICLR) Scott Sussex, Anastasia Makarova, Andreas Krause. 
**TLDR**: A principled algorithm for causal bayesian optimization. (因果贝叶斯优化的新算法) 

**[Causal Inference] A Study of Causal Confusion in Preference-Based Reward Learning**. (2023-ICLR) Jeremy Tien, Jerry Zhi-Yang He, Zackory Erickson, Anca Dragan, Daniel S. Brown. 
**TLDR**: We identify and analyze important factors that influence causal confusion when learning rewards from human preference labels. (有关因果困惑的分析) 

**[Causal Inference] Tier Balancing: Towards Dynamic Fairness over Underlying Causal Factors**. (2023-ICLR) Zeyu Tang, Yatong Chen, Yang Liu, Kun Zhang. 
**TLDR**: We formulate and investigate a long-term fairness notion that captures decision-distribution interplay via a detailed modeling over both observed and latent causal factors. (长期公平性) 

**[Causal Inference] Causal Balancing for Domain Generalization**. (2023-ICLR) Xinyi Wang, Michael Saxon, Jiachen Li, Hongyang Zhang, Kun Zhang, William Yang Wang. 
**TLDR**: We propose a balanced mini-batch sampling strategy to reduce spurious correlations for domain generalization. (域泛化) 

**[Causal Inference] Learning Causal Models from Conditional Moment Restrictions by Importance Weighting**. (2022-ICLR) Masahiro Kato, Masaaki Imaizumi, Kenichiro McAlinn, Shota Yasui, Haruo Kakehi. 
**TLDR**: Learning causal relationships under conditional moment restrictions by importance weighting using the conditional density ratio function. (通过条件密度函数的重要性加权来在条件动量限制下学习因果关系) 

**[Causal Inference] Adversarial Robustness Through the Lens of Causality**. (2022-ICLR) Yonggang Zhang, Mingming Gong, Tongliang Liu, Gang Niu, Xinmei Tian, Bo Han, Bernhard Schölkopf, Kun Zhang. 
**TLDR**: The first attempt towards using causality to understand and mitigate adversarial vulnerability. (以因果视角来理解对抗鲁棒) 

**[Causal Inference] β-Intact-VAE: Identifying and Estimating Causal Effects under Limited Overlap**. (2022-ICLR) Pengzhou Abel Wu, Kenji Fukumizu. 
**TLDR**: See all these naturally in one: limited overlap, prognostic score, identifiable VAE, balanced representation Learning, CATE error bounds. (将一些因果的重要成分统一起来) 

**[Causal Inference] Falsification before Extrapolation in Causal Effect Estimation**. (2022-NIPS) Zeshan Hussain, Michael Oberst, Ming-Chieh Shih, David Sontag. 
**TLDR**: We propose a meta-algorithm that attempts to reject observational estimates that are biased. (基于元算法降低观测估量中的偏差) 

**[Causal Inference] An Adaptive Kernel Approach to Federated Learning of Heterogeneous Causal Effects**. (2022-NIPS) Thanh Vinh Vo, Arnab Bhattacharyya, Young Lee, Tze-Yun Leong. 
**TLDR**: We propose a new causal inference framework to learn causal effects from multiple, decentralized data sources in a federated setting. (联邦学习与因果效应) 

**[Causal Inference] Generalization Bounds for Estimating Causal Effects of Continuous Treatments**. (2022-NIPS) Xin Wang, Shengfei Lyu, Xingyu Wu, Tianhao Wu, Huanhuan Chen. 
**TLDR**: We focus on estimating causal effects of continuous treatments (e.g., dosage in medicine), also known as dose-response function.  (连续treatment下因果效应的泛化界) 

**[Causal Inference] Verification and search algorithms for causal DAGs**. (2022-NIPS) Davin Choo, Kirankumar Shiragur, Arnab Bhattacharyya. 
**TLDR**: We provide (near)-optimal algorithms for two fundamental problems in causal inference: verification and search. (因果推断中的验证和搜索问题) 

**[Causal Inference] Interpolation and Regularization for Causal Learning**. (2022-NIPS) Leena Chennuru Vankadara, Luca Rendsburg, Ulrike von Luxburg, Debarghya Ghoshdastidar. 
**TLDR**: We investigate if interpolation can be optimal for causal learning and explicitly characterize the effect of regularization on causal generalization. (因果发现中的插值与正则化) 

**[Causal Inference] Disentangling Causal Effects from Sets of Interventions in the Presence of Unobserved Confounders**. (2022-NIPS) Olivier Jeunen, Ciarán M. Lee, Rishabh Mehrotra, Mounia Lalmas. 
**TLDR**:  We formally characterise the conditions under which single-variable causal effects can be learnt from only observational and multi-variable interventional data — providing identification proofs alongside an estimation method we evaluate empirically. (从观测数据和多变量干涉数据中学习单变量因果效应) 

**[Causal Inference] Anticipating Performativity by Predicting from Predictions**. (2022-NIPS) Celestine Mendler-Dünner, Frances Ding, Yixin Wang. 
**TLDR**: We study conditions under which the causal effect of performative predictions can be identified from observational data (从观测数据中学习因果效应) 

**[Causal Inference] Sound and Complete Causal Identification with Latent Variables Given Local Background Knowledge**. (2022-NIPS) Tian-Zuo Wang, Tian Qin, Zhi-Hua Zhou. 
**TLDR**: We study what causal relations are identifiable given local background knowledge in the presence of latent confounders. (对于已知背景知识的隐混淆因子的因果关系识别研究) 

**[Causal Inference] Deep Learning Methods for Proximal Inference via Maximum Moment Restriction**. (2022-NIPS) Benjamin Kompa, David Remy Bellamy, Tom Kolokotrones, James Robins, Andrew Beam. 
**TLDR**: The identification of causal effects using neural networks in the setting of proximal inference (在神经网络近端推断中的因果效应识别) 

**[Causal Inference] Staggered Rollout Designs Enable Causal Inference Under Interference Without Network Knowledge**. (2022-NIPS) Mayleen Cortez, Matthew Eichhorn, Christina Yu. 
**TLDR**: We propose a new estimator under a staggered rollout randomized design for estimating the total treatment effect under network interference without knowledge of the underlying network. (未知网络结构下的交错因果推断) 

**[Causal Inference] Empirical Gateaux Derivatives for Causal Inference**. (2022-NIPS) Michael Jordan, Yixin Wang, Angela Zhou. 
**TLDR**: We study a constructive procedure that approximates Gateaux derivatives for statistical functionals by finite-differencing, with attention to causal inference functionals. (经验加托微分与因果推断) 

**[Causal Inference] Scalable Sensitivity and Uncertainty Analyses for Causal-Effect Estimates of Continuous-Valued Interventions**. (2022-NIPS) Andrew Jesson, Alyson Rose Douglas, Peter Manshausen, Maëlys Solal, Nicolai Meinshausen, Philip Stier, Yarin Gal, Uri Shalit. 
**TLDR**: A method to communicate uncertainty about causal-effect estimates for continuous valued interventions. (连续值干涉下因果效应评估的不确定) 

**[Causal Inference] Debiasing Graph Neural Networks via Learning Disentangled Causal Substructure**. (2022-NIPS) Shaohua Fan, Xiao Wang, Yanhu Mo, Chuan Shi, Jian Tang. 
**TLDR**: We first study the severe bias problem on graph data and propose a general GNN disentangled framework for debiasing. (图上数据的偏差问题) 

**[Causal Inference] Off-Policy Evaluation with Policy-Dependent Optimization Response**. (2022-NIPS) Wenshuo Guo, Michael Jordan, Angela Zhou. 
**TLDR**: We study a new framework for off-policy evaluation with policy-dependent linear optimization responses, and construct unbiased estimators for the policy-dependent estimand by a perturbation method. (离线策略评估与策略依赖的优化) 

**[Causal Inference] Causal Inference with Non-IID Data using Linear Graphical Models**. (2022-NIPS) Chi Zhang, Karthika Mohan, Judea Pearl. 
**TLDR**: We model the data generating process using causal graphs and conduct a systematic analysis of the bias caused by different types of interactions when computing causal effects. (线形图模型下基于非IID数据的因果推断) 

**[Causal Inference] Debiased Causal Tree: Heterogeneous Treatment Effects Estimation with Unmeasured Confounding**. (2022-NIPS) Caizhi Tang, Huiyuan Wang, Xinyu Li, Qing Cui, Ya-Lin Zhang, Feng Zhu, Longfei Li, JUN ZHOU, Linbo Jiang. 
**TLDR**:  In this work, we consider the estimation of conditional causal effects in the presence of unmeasured confounding using observational data and historical controls. (使用观测数据和历史干涉在不可测量的混淆因子设定下评估条件因果效应) 

**[Causal Inference] Deep Multi-Modal Structural Equations For Causal Effect Estimation With Unstructured Proxies**. (2022-NIPS) Shachi Deshpande, Kaiwen Wang, Dhruv Sreenivas, Zheng Li, Volodymyr Kuleshov. 
**TLDR**: This paper argues that leveraging this unstructured data can greatly improve the accuracy of causal effect estimation. (非结构化数据对因果效应评估的提升作用) 

**[Causal Inference] What's the Harm? Sharp Bounds on the Fraction Negatively Affected by Treatment**. (2022-NIPS) Nathan Kallus. 
**TLDR**: We derive the tightest-possible bounds on the fraction with negative individual treatment effect, an unknowable quantity due to the fundamental problem of causal inference, and we develop an efficient and robust method for inference on these bounds. (关于负ITE界的理论与模型) 

**[Causal Inference] RISE: Robust Individualized Decision Learning with Sensitive Variables**. (2022-NIPS) Xiaoqing Tan, Zhengling Qi, Christopher Warren Seymour, Lu Tang. 
**TLDR**: We introduce RISE, a robust individualized decision learning framework to improve the worst-case outcomes of individuals caused by sensitive variables that are unavailable at the time of decision. (时间决策中的敏感变量导致的鲁棒性问题) 

**[Causal Inference] Transfer Learning on Heterogeneous Feature Spaces for Treatment Effects Estimation **. (2022-NIPS) Ioana Bica, Mihaela van der Schaar. 
**TLDR**: We address this problem by introducing several building blocks that use representation learning to handle the heterogeneous feature spaces and a flexible multi-task architecture with shared and private layers to transfer information between potential outcome functions across domains. (异质特征空间下迁移学习的因果效应) 

**[Causal Inference] Debiased Machine Learning without Sample-Splitting for Stable Estimators**. (2022-NIPS) Qizhao Chen, Vasilis Syrgkanis, Morgane Austern. 
**TLDR**: We prove asymptotic normality for a target parameter of interest, of debiased machine learning semi-parametric estimators without sample splitting, when the machine learning estimators used for the nuisance functions are leave-one-out stable. (在无采样分割下的去偏机器学习稳定评估) 

**[Causal Inference] Sample Constrained Treatment Effect Estimation**. (2022-NIPS) Raghavendra Addanki, David Arbour, Tung Mai, Cameron N Musco, Anup Rao. 
**TLDR**: We study sample (or budget) constrained treatment effect estimation and provide efficient experimental designs and estimators. (样本受限下的因果效应评估) 

**[Causal Inference] Partial Identification of Treatment Effects with Implicit Generative Models**. (2022-NIPS) Vahid Balazadeh Meresht, Vasilis Syrgkanis, Rahul G Krishnan. 
**TLDR**: We estimate bounds on the average treatment effect using implicit generative models by estimating partial derivatives of the response function in the interval between two points on the response curve. (隐式生成模型下的部分因果效应识别) 

**[Causal Inference] Finding and Listing Front-door Adjustment Sets**. (2022-NIPS) Hyunchai Jeong, Jin Tian, Elias Bareinboim. 
**TLDR**: The paper presents algorithms for finding and enumerating sets satisfying Pearl's front-door criterion. (寻找满足前门准则集合的算法) 

**[Causal Inference] Tractable Uncertainty for Structure Learning**. (2022-ICML) Benjie Wang, Matthew R Wicker, Marta Kwiatkowska. 
**TLDR**: TRUST is a framework for approximate Bayesian inference that uses probabilistic circuits to represent posterior beliefs over causal directed acyclic graphs. (因果DAG的近似后验推断) 

**[Causal Inference] Exploiting Independent Instruments: Identification and Distribution Generalization**. (2022-ICML) Sorawit Saengkyongam, Leonard Henckel, Niklas Pfister, Jonas Peters. 
**TLDR**: The paper proposes a practical method called HSIC-X for exploiting independence in instrumental variable models, which can improve finite sample results and distribution generalization, even in the under-identified case. (利用独立性改善有限样本结果并实现分布泛化) 

**[Causal Inference] On Measuring Causal Contributions via do-interventions**. (2022-ICML) Yonghan Jung, Shiva Kasiviswanathan, Jin Tian, Dominik Janzing, Patrick Bloebaum, Elias Bareinboim. 
**TLDR**: In this paper, we develop a principled method for quantifying causal contributions via do-interventions. (量化因果贡献) 

**[Causal Inference] The Role of Deconfounding in Meta-learning**. (2022-ICML) Yinjie Jiang, Zhengyu Chen, Kun Kuang, Luotian Yuan, Xinhai Ye, Zhihua Wang, Fei Wu, Ying Wei. 
**TLDR**: The paper proposes a causal perspective on meta-learning, identifying the universal label space as the cause of memorization, and offering two simple and effective deconfounder algorithms to combat the effect. (因果视角的元学习) 

**[Causal Inference] Minimum Cost Intervention Design for Causal Effect Identification**. (2022-ICML) Sina Akbari, Jalal Etesami, Negar Kiyavash. 
**TLDR**: The paper proposes an algorithm to minimize the cost of interventions needed to identify causal effects, based on the minimum hitting set problem, which can find either the optimal solution or a logarithmic-factor approximation of it, and presents polynomial time heuristic algorithms to tackle the computational complexity of the problem. (最小化识别因果效应所需的干预成本) 

**[Causal Inference] Causal structure-based root cause analysis of outliers**. (2022-ICML) Kailash Budhathoki, Lenon Minorics, Patrick Bloebaum, Dominik Janzing. 
**TLDR**: The paper proposes a formal method for identifying "root causes" of outliers using a causal graph and functional causal model. The method quantifies the contribution of each variable to the target outlier score and is tested on simulations and a case study on extreme river flows. (使用因果图和函数因果模型识别异常值“根本原因”) 

**[Causal Inference] Context-Aware Drift Detection**. (2022-ICML) Oliver Cobb, Arnaud Van Looveren. 
**TLDR**: The paper proposes a more general drift detection framework using two-sample tests for conditional distributional treatment effects, which borrows machinery from the causal inference domain and is effective for detecting drift in subpopulations of data, as demonstrated in an empirical study. (上下文注意的偏移检测) 

**[Causal Inference] Instrumental Variable Regression with Confounder Balancing**. (2022-ICML) Anpeng Wu, Kun Kuang, Bo Li, Fei Wu. 
**TLDR**: The paper proposes a Confounder Balanced IV Regression (CB-IV) algorithm for estimating treatment effects from observational data in the presence of unmeasured confounders, which removes bias from unmeasured confounders and balances observed confounders, and outperforms existing approaches. (混杂因素平衡IV回归) 

**[Causal Inference] Matching Learned Causal Effects of Neural Networks with Domain Priors**. (2022-ICML) Sai Srinivas Kancheti, Abbavaram Gowtham Reddy, Vineeth N Balasubramanian, Amit Sharma. 
**TLDR**: The paper proposes a regularization method that aligns the learned causal effects of a neural network with domain priors to maintain desired causal effects without compromising accuracy. (正则化方法将学习的因果效应与域先验对齐) 

**[Causal Inference] Strategic Instrumental Variable Regression: Recovering Causal Relationships From Strategic Responses**. (2022-ICML) Keegan Harris, Dung Daniel T Ngo, Logan Stapleton, Hoda Heidari, Steven Wu. 
**TLDR**: We show that we can use strategic responses effectively to recover causal relationships between the observable features and outcomes we wish to predict, even under the presence of unobserved confounding variables. (恢复可观察到的特征和预测结果之间的因果关系) 

**[Causal Inference] Validating Causal Inference Methods**. (2022-ICML) Harsh Parikh, Carlos Varjao, Louise Xu, Eric Tchetgen Tchetgen. 
**TLDR**: Our work introduces a deep generative model-based framework, Credence, to validate causal inference methods. (深度生成模型验证因果推断方法) 

**[Causal Inference] End-to-End Balancing for Causal Continuous Treatment-Effect Estimation**. (2022-ICML) Taha Bahadori, Eric Tchetgen Tchetgen, David Heckerman. 
**TLDR**: We design a new algorithm based on the framework of entropy balancing which learns weights that directly maximize causal inference accuracy using end-to-end optimization. (连续性处理的因果推断) 

**[Causal Inference] Entropic Causal Inference: Graph Identifiability**. (2022-ICML) Spencer Compton, Kristjan Greenewald, Dmitriy A Katz, Murat Kocaoglu. 
**TLDR**: The paper proposes an extension to entropic causal inference for learning causal graphs with more than two nodes, and provides a sound sequential peeling algorithm and heuristic algorithm for evaluation on synthetic and real-world datasets. (熵因果推断的扩展用于学习具有两个以上节点的因果图) 

**[Causal Inference] Inducing Causal Structure for Interpretable Neural Networks**. (2022-ICML) Atticus Geiger, Zhengxuan Wu, Hanson Lu, Josh Rozner, Elisa Kreiss, Thomas Icard, Noah Goodman, Christopher Potts. 
**TLDR**: The paper presents the method of interchange intervention training (IIT), which aligns variables in a causal model with representations in a neural model and trains the neural model to match the counterfactual behavior of the causal model, achieving the best results and producing more interpretable neural models. (交换干预训练(IIT)方法) 

**[Causal Inference] Scalable Computation of Causal Bounds**. (2022-ICML) Madhumitha Shridharan, Garud Iyengar. 
**TLDR**: We consider the problem of computing bounds for causal inference problems with unobserved confounders, where identifiability does not hold. (未观察的混杂因素的因果推断界计算) 

**[Causal Inference] ROCK: Causal Inference Principles for Reasoning about Commonsense Causality**. (2022-ICML) Jiayao Zhang, Hongming Zhang, Weijie Su, Dan Roth. 
**TLDR**: The paper proposes a novel framework called ROCK that adopts the potential-outcomes framework to Reason O(A)bout Commonsense K(C)ausality, which utilizes temporal signals as incidental supervision and balances confounding effects using temporal propensities to improve commonsense causality reasoning. (常识因果推理) 

**[Causal Inference] Causal Conceptions of Fairness and their Consequences**. (2022-ICML) Hamed Nilforoshan, Johann D Gaebler, Ravi Shroff, Sharad Goel. 
**TLDR**: The paper examines the relationship between different causal definitions of algorithmic fairness, finding that they often lead to strongly Pareto dominated decision policies, with potential adverse consequences. (算法公平性的不同因果定义之间的关系) 

**[Causal Inference] Improving Data-driven Heterogeneous Treatment Effect Estimation Under Structure Uncertainty**. (2022-SIGKDD) Christopher Tran, Elena Zheleva. 
**TLDR**: We develop a feature selection method that considers each feature's value for HTE estimation and learns the relevant parts of the causal structure from data.  (数据特征选择算法改进HTE估计) 

**[Causal Inference] Learning Causal Effects on Hypergraphs**. (2022-SIGKDD) Jing Ma, Mengting Wan, Longqi Yang, Jundong Li, Brent Hecht, Jaime Teevan. 
**TLDR**: We investigate high-order interference modeling, and propose a new causality learning framework powered by hypergraph neural networks. (高阶干扰下的ITE估计问题) 

**[Causal Inference] Estimating Individualized Causal Effect with Confounded Instruments**. (2022-SIGKDD) Haotian Wang, Wenjing Yang, Longqi Yang, Anpeng Wu, Liyang Xu, Jing Ren, Fei Wu, Kun Kuang. 
**TLDR**: By considering the conditional independence between the set of confounded instruments and the outcome variable, we propose a novel method, named CVAE-IV, to generate a substitute of the unmeasured confounder with a conditional variational autoencoder. (混杂工具估计个体因果效应) 

**[Causal Inference] DICE: Domain-attack Invariant Causal Learning for Improved Data Privacy Protection and Adversarial Robustness**. (2022-SIGKDD) Qibing Ren, Yiting Chen, Yichuan Mo, Qitian Wu, Junchi Yan. 
**TLDR**: We propose a causal inference pipeline, namely Domain-attack Invariant Causal Learning (DICE) to infer domain-invariant features via an effective approximation of backdoor adjustment. (因果关系保护隐私和稳健性) 

**[Causal Inference] Robust Event Forecasting with Spatiotemporal Confounder Learning**. (2022-SIGKDD) Songgaojun Deng, Huzefa Rangwala, Yue Ning. 
**TLDR**: we introduce a deep learning framework that integrates causal effect estimation into event forecasting. We first study the problem of Individual Treatment Effect (ITE) estimation from observational event data with spatiotemporal attributes and present a novel causal inference model to estimate ITEs. We then incorporate the learned event-related causal information into event prediction as prior knowledge. Two robust learning modules, including a feature reweighting module and an approximate constraint loss, are introduced to enable prior knowledge injection (因果效应的鲁棒事件预测) 

**[Causal Inference] Causal Inference-Based Root Cause Analysis for Online Service Systems with Intervention Recognition**. (2022-SIGKDD) Mingjie Li, Zeyan Li, Kanglin Yin, Xiaohui Nie, Wenchi Zhang, Kaixin Sui, Dan Pei. 
**TLDR**: In this paper, we formulate the root cause analysis problem as a new causal inference task named intervention recognition. We proposed a novel unsupervised causal inference-based method named Causal Inference-based Root Cause Analysis (CIRCA).  (基于因果推断的RCA方法) 

**[Causal Inference] Interference, Bias, and Variance in Two-Sided Marketplace Experimentation: Guidance for Platforms**. (2022-WWW) Hannah Li, Geng Zhao, Ramesh Johari, Gabriel Weintraub. 
**TLDR**: We develop a simple, tractable market model to study bias and variance in these experiments with interference (分析偏差和方差来指导系统的决策) 

**[Causal Inference] Assessing the Causal Impact of COVID-19 Related Policies on Outbreak Dynamics: A Case Study in the US**. (2022-WWW) Jing Ma, Yushun Dong, Zheng Huang, Daniel Mietchen, Jundong Li. 
**TLDR**: In this paper, we study the problem of assessing the causal effects of different COVID-19 related policies on the outbreak dynamics in different counties at any given time period (研究COVID-19政策在不同国家的因果效应) 

**[Causal Inference] LBCF: A Large-Scale Budget-Constrained Causal Forest Algorithm**. (2022-WWW) Meng Ai, Biao Li, Heyang Gong, Qingwei Yu, Shengjie Xue, Yuan Zhang, Yunzhou Zhang, Peng Jiang. 
**TLDR**: We propose a novel tree-based treatment selection technique under budget constraints, called Large-Scale Budget-Constrained Causal Forest (LBCF) algorithm, which is also an efficient treatment selection algorithm suitable for modern distributed computing systems. (在线平台高效的干预选择) 

**[Causal Inference] Learning and Evaluating Graph Neural Network Explanations based on Counterfactual and Factual Reasoning**. (2022-WWW) Juntao Tan, Shijie Geng, Zuohui Fu, Yingqiang Ge, Shuyuan Xu, Yunqi Li,  Yongfeng Zhang. 
**TLDR**: In this paper, we take insights of Counterfactual and Factual (CF2) reasoning from causal inference theory, to solve both the learning and evaluation problems in explainable GNNs. (反事实推断生成图神经网络解释) 

**[Causal Inference] Generalizing to the Future: Mitigating Entity Bias in Fake News Detection**. (2022-SIGIR) Yongchun Zhu, Qiang Sheng, Juan Cao, Shuokai Li, Danding Wang, Fuzhen Zhuang. 
**TLDR**: we propose an entity debiasing framework (ENDEF) which generalizes fake news detection models to the future data by mitigating entity bias from a cause-effect perspective (利用因果图对虚假新闻检测去偏) 

### Causal Discovery

**[Causal Discovery] Rhino: Deep Causal Temporal Relationship Learning with History-dependent Noise**. (2023-ICLR) Wenbo Gong, Joel Jennings, Cheng Zhang, Nick Pawlowski. 
**TLDR**: We propose a causal discovery method for time series, which combines deep learning and variational inference to model instantaneous effect and history-dependent noise with structure identifiability guarantee. (时序上的因果发现算法) 

**[Causal Discovery] GRACE-C: Generalized Rate Agnostic Causal Estimation via Constraints**. (2023-ICLR) Mohammadsajad Abavisani, David Danks, Sergey Plis. 
**TLDR**: A novel method for causal structure discovery in undersampled time-series with three orders of magnitude speedup under the same theoretical guarantees. (时序上的因果发现算法) 

**[Causal Discovery] Boosting Causal Discovery via Adaptive Sample Reweighting**. (2023-ICLR) An Zhang, Fangfu Liu, Wenchang Ma, Zhibo Cai, Xiang Wang, Tat-Seng Chua. 
**TLDR**: Automatically learn the adaptive weights for each observation to boost score-based causal discovery performance.  (学习权重以优化基于评分的因果发现算法) 

**[Causal Discovery] Causal Reasoning in the Presence of Latent Confounders via Neural ADMG Learning**. (2023-ICLR) Matthew Ashman, Chao Ma, Agrin Hilmkil, Joel Jennings, Cheng Zhang. 
**TLDR**: Develop a novel gradient-based approach to learning an ADMG with nonlinear functional relations from observational data.  (基于梯度学习ADMG) 

**[Causal Discovery] Learning to Induce Causal Structure**. (2023-ICLR) Nan Rosemary Ke, Silvia Chiappa, Jane X Wang, Jorg Bornschein, Anirudh Goyal, Melanie Rey, Theophane Weber, Matthew Botvinick, Michael Curtis Mozer, Danilo Jimenez Rezende. 
**TLDR**: We tackle causal structure induction with a supervised approach (CSIvA) that maps datasets composed of both observational and interventional samples to structures. (因果结构归纳) 

**[Causal Discovery] Optimal Transport for Causal Discovery**. (2022-ICLR) Ruibo Tu, Kun Zhang, Hedvig Kjellstrom, Cheng Zhang. 
**TLDR**: We provide a novel dynamical-system view of FCMs and propose a new framework for identifying causal direction in the bivariate case. (基于动态系统分析FCM模型并提出双变量的因果方向推断框架) 

**[Causal Discovery] Graph-Augmented Normalizing Flows for Anomaly Detection of Multiple Time Series**. (2022-ICLR) Enyan Dai, Jie Chen. 
**TLDR**:  We propose a novel flow model by imposing a Bayesian network among constituent series. (在一致序列中提出了新的贝叶斯网络学习) 

**[Causal Discovery] Granger causal inference on DAGs identifies genomic loci regulating transcription**. (2022-ICLR) Alexander P Wu, Rohit Singh, Bonnie Berger. 
**TLDR**: We show how to extend Granger causality to DAG-structured dynamical systems using graph neural networks, applying it to infer noncoding regions involved in gene regulation. (通过GNN将Granger因果引入DAG结构的动态系统中) 

**[Causal Discovery] Learning Temporally Causal Latent Processes from General Temporal Data**. (2022-ICLR) Weiran Yao, Yuewen Sun, Alex Ho, Changyin Sun, Kun Zhang. 
**TLDR**: Propose two provable conditions and training framework with which temporally latent causal processes are identifiable from observed variables. (从观测数据中识别时序隐因果过程) 

**[Causal Discovery] Efficient Neural Causal Discovery without Acyclicity Constraints**. (2022-ICLR) Phillip Lippe, Taco Cohen, Efstratios Gavves. 
**TLDR**: We present ENCO, an efficient structure learning method that leverages observational and interventional data and scales to graphs with a thousand variables. (用观测数据和干涉数据来高效进行因果发现) 

**[Causal Discovery] Causal Discovery in Heterogeneous Environments Under the Sparse Mechanism Shift Hypothesis**. (2022-NIPS) Ronan Perry, Julius Von Kügelgen, Bernhard Schölkopf. 
**TLDR**: We theoretically prove and empirically demonstrate the value of the sparse mechanism shift hypothesis for learning causal graphs from heterogenous data. (异质图上的因果发现) 

**[Causal Discovery] Active Bayesian Causal Inference**. (2022-NIPS) Christian Toth, Lars Lorch, Christian Knoll, Andreas Krause, Franz Pernkopf, Robert Peharz, Julius Von Kügelgen. 
**TLDR**: We propose Active Bayesian Causal Inference (ABCI), a fully Bayesian active learning framework for integrated causal discovery and reasoning with experimental design. (主动贝叶斯因果发现推断) 

**[Causal Discovery] Causal Discovery in Linear Latent Variable Models Subject to Measurement Error**. (2022-NIPS) Yuqin Yang, AmirEmad Ghassami, Mohamed S Nafea, Negar Kiyavash, Kun Zhang, Ilya Shpitser. 
**TLDR**: Measurement error in linear systems where the mixing matrix is identified up to permutation and scaling of the columns. (因果发现与线性系统中的测量误差) 

**[Causal Discovery] Root Cause Analysis of Failures in Microservices through Causal Discovery**. (2022-NIPS) Muhammad Azam Ikram, Sarthak Chakraborty, Subrata Mitra, Shiv Saini, Saurabh Bagchi, Murat Kocaoglu. 
**TLDR**: We create a solution for root cause diagnosis in microservice-based cloud computing applications by a scalable intervention-based causal discovery algorithm. (云计算中的因果发现) 

**[Causal Discovery] Causal Identification under Markov equivalence: Calculus, Algorithm, and Completeness**. (2022-NIPS) Amin Jaber, Adele H Ribeiro, Jiji Zhang, Elias Bareinboim. 
**TLDR**: We close the problem of conditional effect identification under Markov equivalence in terms of delineating the theoretical boundaries of what is computable from non-experimental data. (关于观测数据在马尔科夫等价类中条件效应识别的理论) 

**[Causal Discovery] Adaptively Exploiting d-Separators with Causal Bandits**. (2022-NIPS) Blair Bilodeau, Linbo Wang, Daniel M. Roy. 
**TLDR**: We provide a novel algorithm that exploits causal structure when it exists while simultaneously achieving sub-linear regret in the worst case. (因果Bandit的因果发现算法) 

**[Causal Discovery] Bivariate Causal Discovery for Categorical Data via Classification with Optimal Label Permutation**. (2022-NIPS) Yang Ni. 
**TLDR**: Causal discovery for bivariate categorical data (二元分类数据中的因果发现) 

**[Causal Discovery] Amortized Inference for Causal Structure Learning**. (2022-NIPS) Lars Lorch, Scott Sussex, Jonas Rothfuss, Andreas Krause, Bernhard Schölkopf. 
**TLDR**: Amortized causal discovery for learning realistic, domain-specific inductive bias (分摊式因果发现) 

**[Causal Discovery] Causality Preserving Chaotic Transformation and Classification using Neurochaos Learning**. (2022-NIPS) Harikrishnan N B, Aditi Kathpalia, Nithin Nagaraj. 
**TLDR**: Brain inspired learning algorithm used for the classification of cause and effect time series. (大脑启发式因果学习) 

**[Causal Discovery] Independence Testing-Based Approach to Causal Discovery under Measurement Error and Linear Non-Gaussian Models**. (2022-NIPS) Haoyue Dai, Peter Spirtes, Kun Zhang. 
**TLDR**: In this work, we propose the Transformed Independent Noise (TIN) condition, which checks for independence between a specific linear transformation of some measured variables and certain other measured variables. (在测量误差和非高斯线性模型下基于独立测试的因果发现) 

**[Causal Discovery] Interventions, Where and How? Experimental Design for Causal Models at Scale**. (2022-NIPS) Panagiotis Tigas, Yashas Annadani, Andrew Jesson, Bernhard Schölkopf, Yarin Gal, Stefan Bauer. 
**TLDR**: We incorporate recent advances in Bayesian causal discovery into the Bayesian optimal experimental design framework, which allows for active causal discovery of nonlinear, large SCMs, while selecting both the target and the value to intervene with. (主动贝叶斯因果发现) 

**[Causal Discovery] Large-Scale Differentiable Causal Discovery of Factor Graphs**. (2022-NIPS) Romain Lopez, Jan-Christian Huetter, Jonathan Pritchard, Aviv Regev. 
**TLDR**: We propose to use factor graphs for large-scale causal discovery learning with interventional data. (使用因子图来实现基于干涉数据的大规模因果发现) 

**[Causal Discovery] Conditional Independence Testing with Heteroskedastic Data and Applications to Causal Discovery**. (2022-NIPS) Wiebke Günther, Urmi Ninad, Jonas Wahl, Jakob Runge. 
**TLDR**: We frame heteroskedasticity in a structural causal model framework and present an adaptation of the partial correlation CI test that works well in the presence of heteroskedastic noise, given that expert knowledge about the heteroskedastic relationships is available. (异质性下的条件独立测试) 

**[Causal Discovery] MissDAG: Causal Discovery in the Presence of Missing Data with Continuous Additive Noise Models**. (2022-NIPS) Erdun Gao, Ignavier Ng, Mingming Gong, Li Shen, Wei Huang, Tongliang Liu, Kun Zhang, Howard Bondell. 
**TLDR**: We develop a general method, which we call MissDAG, to perform causal discovery from data with incomplete observations. (基于非完全观测数据的因果发现算法) 

**[Causal Discovery] Latent Hierarchical Causal Structure Discovery with Rank Constraints**. (2022-NIPS) Biwei Huang, Charles Low, Feng Xie, Clark Glymour, Kun Zhang. 
**TLDR**: We proposed an estimation procedure, together with theoretical identifiability conditions, to identify latent hierarchical causal graphs by making use of rank deficiency constraints. (基于秩亏损限制的因果结构发现) 

**[Causal Discovery] Truncated Matrix Power Iteration for Differentiable DAG Learning **. (2022-NIPS) Zhen Zhang, Ignavier Ng, Dong Gong, Yuhang Liu, Ehsan M Abbasnejad, Mingming Gong, Kun Zhang, Javen Qinfeng Shi. 
**TLDR**: Truncated Matrix Power Iteration for DAG Learning (基于截尾矩阵幂迭代的可微DAG学习) 

**[Causal Discovery] DAGMA: Learning DAGs via M-matrices and a Log-Determinant Acyclicity Characterization**. (2022-NIPS) Kevin Bello, Bryon Aragam, Pradeep Kumar Ravikumar. 
**TLDR**: Faster and more accurate score-based learning for directed acyclic graphs through a new acyclicity characterization based on log-det constraints and M-matrices (更快更好的基于分数的DAG学习) 

**[Causal Discovery] Neuron Dependency Graphs: A Causal Abstraction of Neural Networks**. (2022-ICML) Yaojie Hu, Jin Tian. 
**TLDR**: We discover that neural networks exhibit approximate logical dependencies among neurons, and we introduce Neuron Dependency Graphs (NDG) that extract and present them as directed graphs. (神经元依赖图) 

**[Causal Discovery] IDYNO: Learning Nonparametric DAGs from Interventional Dynamic Data**. (2022-ICML) Tian Gao, Debarun Bhattacharjya, Elliot Nelson, Miao Liu, Yue Yu. 
**TLDR**: The paper proposes IDYNO, a new algorithm for learning the DAG structure from potentially nonlinear time series data, which can handle both observational and interventional time series data and achieve promising performance on synthetic benchmark datasets. (从潜在非线性时间序列数据中学习DAG结构) 

**[Causal Discovery] Inferring Cause and Effect in the Presence of Heteroscedastic Noise**. (2022-ICML) Sascha Xu, Osman A Mian, Alexander Marx, Jilles Vreeken. 
**TLDR**: The paper proposes a method to identify the causal direction between two variables with heteroscedastic noise, achieving improved performance on synthetic and real-world datasets. (识别具有异方差噪声的两个变量之间的因果方向) 

**[Causal Discovery] Score Matching Enables Causal Discovery of Nonlinear Additive Noise Models**. (2022-ICML) Paul Rolland, Volkan Cevher, Matthäus Kleindessner, Chris Russell, Dominik Janzing, Bernhard Schölkopf, Francesco Locatello. 
**TLDR**: This paper demonstrates how to recover causal graphs from the score of the data distribution in non-linear additive (Gaussian) noise models. (从非线性加性高斯噪声模型中数据分布的分数中恢复因果图) 

**[Causal Discovery] Causal Discovery on Non-Euclidean Data**. (2022-SIGKDD) Jing Yang, Kai Xie, Ning An. 
**TLDR**: We propose the non-Euclidean Hybrid Learning (NEHL) method, a causal discovery algorithm relying on the concept of the ball covariance recently introduced in the statistics field. (非欧式数据的因果发现) 

**[Causal Discovery] ML4S: Learning Causal Skeleton from Vicinal Graphs**. (2022-SIGKDD) Pingchuan Ma, Rui Ding, Haoyue Dai, Yuanyuan Jiang, Shuai Wang, Shi Han, Dongmei Zhang. 
**TLDR**: This paper, for the first time, advocates for learning a causal skeleton in a supervision-based setting, where the algorithm learns from additional datasets associated with the ground-truth BNs (complementary to input observational data). (监督环境下的因果框架学习) 

**[Causal Discovery] Discovering Invariant and Changing Mechanisms from Data**. (2022-SIGKDD) Sarah Mameche, David Kaltenpoth, Jilles Vreeken. 
**TLDR**: To discover invariant and changing mechanisms from data, we propose extending the algorithmic model for causation to mechanism changes and instantiating it using Minimum Description Length (数据中发现不变与改变的因果机制) 

**[Causal Discovery] Learning to Discover Causes of Traffic Congestion with Limited Labeled Data**. (2022-SIGKDD) Mudan Wang, Huan Yan, Hongjie Sui, Fan Zuo, Yue Liu, Yong Li. 
**TLDR**: we design a congestion cause discovery system consisting of two modules: 1) congestion feature extraction, which extracts the important features influencing congestion; and 2) congestion cause discovery, which utilize a deep semi-supervised learning based method to discover the causes of traffic congestion with limited labeled causes. (发现交通拥堵的原因) 

**[Causal Discovery] CausPref: Causal Preference Learning for Out-of-Distribution Recommendation**. (2022-WWW) Yue He, Zimu Wang, Peng Cui, Hao Zou, Yafeng Zhang, Qiang Cui, Yong Jiang. 
**TLDR**: we propose to incorporate the recommendation-specific DAG learner into a novel causal preference-based recommendation framework named CausPref, mainly consisting of causal learning of invariant user preference and anti-preference negative sampling to deal with implicit feedback. (学习因果图解决推荐中的OOD问题) 

**[Causal Discovery] Towards Event-level Causal Relation Identification**. (2022-SIGIR) Chuang Fan, Daoxing Liu, Libo Qin, Yue Zhang, Ruifeng Xu. 
**TLDR**: We propose to identify causal relations in a more realistic setting, where event-level causality identification can be made (在事件级别识别因果关系) 

### Causal Representation Learning

**[Causal Representation Learning] Efficient Conditionally Invariant Representation Learning**. (2023-ICLR) Roman_Pogodin, Namrata Deka, Yazhe Li, Danica J. Sutherland, Victor Veitch, Arthur Gretton. 
**TLDR**: Batch-efficient conditional independence regularization. (高效的条件独立方法) 

**[Causal Representation Learning] Pareto Invariant Risk Minimization**. (2023-ICLR) Yongqiang Chen, Kaiwen Zhou, Yatao Bian, Binghui Xie, Bingzhe Wu, Yonggang Zhang, MA KAILI, Han Yang, Peilin Zhao, Bo Han, James Cheng. 
**TLDR**: We introduce a novel Multi-Objective Optimization perspective to understand and allieviate the optimization delimma in Out-of-Distribution generalization. (基于多目标优化解决分布偏移问题) 

**[Causal Representation Learning] Identifiability Results for Multimodal Contrastive Learning**. (2023-ICLR) Imant Daunhawer, Alice Bizeul, Emanuele Palumbo, Alexander Marx, Julia E Vogt. 
**TLDR**: We show that multimodal contrastive learning can block-identify latent factors shared between heterogenous modalities (e.g., images and captions), even in the presence of nontrivial statistical and causal dependencies. (多模态对比学习) 

**[Causal Representation Learning] What Is Missing in IRM Training and Evaluation? Challenges and Solutions**. (2023-ICLR) Yihua Zhang, Pranay Sharma, Parikshit Ram, Mingyi Hong, Kush R. Varshney, Sijia Liu. 
**TLDR**: We propose a new IRM variant to address limitation based on a novel viewpoint of ensemble IRM games as consensus-constrained bi-level optimization. (IRM 变体) 

**[Causal Representation Learning] Asymmetry Learning for Counterfactually-invariant Classification in OOD Tasks**. (2022-ICLR) S Chandra Mouli, Bruno Ribeiro. 
**TLDR**:  We then propose a new learning paradigm, asymmetry learning, that identifies which symmetries the classifier must break in order to correctly predict 
 in both train and test. (解决OOD鲁棒问题的反事实不变学习) 

**[Causal Representation Learning] Discovering Invariant Rationales for Graph Neural Networks**. (2022-ICLR) Yingxin Wu, Xiang Wang, An Zhang, Xiangnan He, Tat-Seng Chua. 
**TLDR**: We propose a novel invariant learning algorithm, Discovering Invariant Rationale (DIR), for intrinsically interpretable models. (用不变表示学习来解释GNN) 

**[Causal Representation Learning] Invariant Causal Representation Learning for Out-of-Distribution Generalization**. (2022-ICLR) Chaochao Lu, Yuhuai Wu, José Miguel Hernández-Lobato, Bernhard Schölkopf. 
**TLDR**: We propose invariant Causal Representation Learning (iCaRL), an approach that enables out-of-distribution (OOD) generalization in the nonlinear setting (i.e., nonlinear representations and nonlinear classifiers). (因果不变表示学习解决OOD泛化问题) 

**[Causal Representation Learning] Weakly supervised causal representation learning**. (2022-NIPS) Johann Brehmer, Pim De Haan, Phillip Lippe, Taco Cohen. 
**TLDR**: We show that causal factors and their causal structure can be identified from low-level data (e.g. pixels) observed before and after interventions. (因果效应能够被低层次数据识别) 

**[Causal Representation Learning] Multi-Instance Causal Representation Learning for Instance Label Prediction and Out-of-Distribution Generalization**. (2022-NIPS) Weijia Zhang, Xuanhui Zhang, Han-Wen Deng, Min-Ling Zhang. 
**TLDR**: Learning invariant causal representation from multi-instance bags benefits instance label prediction and OOD generalization. (因果不变表示与多实体学习) 

**[Causal Representation Learning] Learning Causally Invariant Representations for Out-of-Distribution Generalization on Graphs **. (2022-NIPS) Yongqiang Chen, Yonggang Zhang, Yatao Bian, Han Yang, MA KAILI, Binghui Xie, Tongliang Liu, Bo Han, James Cheng. 
**TLDR**: We formulate, generalize and instantiate the invariance principle from causality to tackle out-of-distribution generalization problem on graphs. (在OOD图上的因果不变表示学习) 

**[Causal Representation Learning] In the Eye of the Beholder: Robust Prediction with Causal User Modeling**. (2022-NIPS) . 
**TLDR**: We propose a learning framework for relevance prediction that is robust to distributional changes by accounting for users' causal perceptions. (基于用户因果感知的分布鲁棒架构) 

**[Causal Representation Learning] Temporally Disentangled Representation Learning**. (2022-NIPS) Weiran Yao, Guangyi Chen, Kun Zhang. 
**TLDR**: This paper establishes the identifiability theories of unsupervised causal representation learning for sequential data and propose an implementation of the assumed causal model as a sequential deep generative model. (时序因果表示学习) 

**[Causal Representation Learning] Invariant and Transportable Representations for Anti-Causal Domain Shifts**. (2022-NIPS) Yibo Jiang, Victor Veitch. 
**TLDR**: Formalize anti-causal domain shifts and leverage causal assumptions to learn invariant and transportable representations. (建立反因果域偏移并使用因果假设来学习不变和迁移表示) 

**[Causal Representation Learning] Improving Multi-Task Generalization via Regularizing Spurious Correlation**. (2022-NIPS) Ziniu Hu, Zhe Zhao, Xinyang Yi, Tiansheng Yao, Lichan Hong, Yizhou Sun, Ed H. Chi. 
**TLDR**: We point out the unique challenges of spurious correlation problem in multi-task learning and propose MT-CRL framework to improve multi-task generalization via regularizing spurious correlation. (多任务学习与因果表示学习) 

**[Causal Representation Learning] Generative multitask learning mitigates target-causing confounding**. (2022-NIPS) Taro Makino, Krzysztof J. Geras, Kyunghyun Cho. 
**TLDR**: We use ideas from causality to develop an inference objective for MTL that improves robustness to target shift. (基于因果推断提升多任务学习的鲁棒性) 

**[Causal Representation Learning] Environment Diversification with Multi-head Neural Network for Invariant Learning**. (2022-NIPS) . 
**TLDR**: This work proposes EDNIL, an invariant learning framework containing a multi-head neural network to absorb data biases. (多头神经网络与不变学习) 

**[Causal Representation Learning] LOG: Active Model Adaptation for Label-Efficient OOD Generalization**. (2022-NIPS) Jie-Jing Shao, Lan-Zhe Guo, Xiao-wen Yang, Yu-Feng Li. 
**TLDR**: We propose Log, an interactive model adaptation framework, with two sub-modules: active sample selection and causal invariant learning. (主动样本选择与因果不变学习) 

**[Causal Representation Learning] ZIN: When and How to Learn Invariance Without Environment Partition?**. (2022-NIPS) LIN Yong, Shengyu Zhu, Lu Tan, Peng Cui. 
**TLDR**: We propose a framework to provably learn invariant feature without environment partition.  (无需环境分割的不变特征学习) 

**[Causal Representation Learning] Partial disentanglement for domain adaptation**. (2022-ICML) Lingjing Kong, Shaoan Xie, Weiran Yao, Yujia Zheng, Guangyi Chen, Petar Stojanov, Victor Akinwande, Kun Zhang. 
**TLDR**: The paper proposes a framework called invariant minimal domain shift adaptation (iMSDA) that addresses unsupervised domain adaptation by exploiting the minimal changes of causal mechanisms across domains. (无监督域适应问题) 

**[Causal Representation Learning] CITRIS: Causal Identifiability from Temporal Intervened Sequences**. (2022-ICML) Phillip Lippe, Sara Magliacane, Sindy Löwe, Yuki M Asano, Taco Cohen, Stratis Gavves. 
**TLDR**: The paper presents CITRIS, a variational autoencoder framework that learns causal representations from temporal sequences of images with interventions, identifying scalar and multidimensional causal factors using a normalizing flow and achieving better performance on recovering underlying causal variables. (变分自编码器框架从带有干预的图像时间序列中学习因果表示) 

**[Causal Representation Learning] Deep Causal Metric Learning**. (2022-ICML) Xiang Deng, Zhongfei Zhang. 
**TLDR**: The paper proposes a deep causal metric learning (DCML) approach to address the issue of learning spurious distances in deep metric learning, which explicitly learns environment-invariant attention and task-invariant embedding based on causal inference, achieving superior performance on benchmark datasets. (深度度量学习) 

**[Causal Representation Learning] Causal Imitation Learning under Temporally Correlated Noise**. (2022-ICML) Gokul Swamy, Sanjiban Choudhury, Drew Bagnell, Steven Wu. 
**TLDR**: We develop algorithms for imitation learning from policy data that was corrupted by temporally correlated noise in expert actions. (从专家行动中被时间相关噪声损坏的策略数据中模仿学习) 

**[Causal Representation Learning] Causal Attention for Interpretable and Generalizable Graph Classification**. (2022-SIGKDD) Yongduo Sui, Xiang Wang, Jiancan Wu, Min Lin, Xiangnan He, Tat-Seng Chua. 
**TLDR**: We propose the Causal Attention Learning (CAL) strategy, which discovers the causal patterns and mitigates the confounding effect of shortcuts (图分类的因果注意力学习策略) 

**[Causal Representation Learning] Causal Representation Learning for Out-of-Distribution Recommendation**. (2022-WWW) Wenjie Wang, Xinyu Lin, Fuli Feng, Xiangnan He, Min Lin, Tat-Seng Chua. 
**TLDR**: We devise a new Variational Auto-Encoder for causal modeling by incorporating an encoder to infer unobserved user features from historical interactions, and further perform counterfactual inference to mitigate the effect of out-of-date interactions. (推荐OOD下的因果表征学习) 

**[Causal Representation Learning] A Model-Agnostic Causal Learning Framework for Recommendation using Search Data**. (2022-WWW) Zihua Si, Xueran Han, Xiao Zhang, Jun Xu, Yue Yin, Yang Song, Ji-Rong Wen. 
**TLDR**: we propose a model-agnostic framework named IV4Rec that can effectively decompose the embedding vectors into causal and non-causal parts, hence enhancing recommendation results. (推荐场景下解耦因果和非因果关系以增强推荐效果) 

**[Causal Representation Learning] Learning Disentangled Representations for Counterfactual Regression via Mutual Information Minimization**. (2022-SIGIR) Mingyuan Cheng, Xinru Liao, Quan Liu, Bin Ma, Jian Xu, Bo Zheng. 
**TLDR**: we propose Disentangled Representations for Counterfactual Regression via Mutual Information Minimization (MIM-DRCFR), which uses a multi-task learning framework to share information when learning the latent factors and incorporates MI minimization learning criteria to ensure the independence of these factors. (利用互信息学习协变量的解耦表征) 

### Counterfactual Inference

**[Counterfactual Inference] Neural Causal Models for Counterfactual Identification and Estimation**. (2023-ICLR) Kevin Muyuan Xia, Yushu Pan, Elias Bareinboim. 
**TLDR**: We solve the two problems of counterfactual identification and estimation from arbitrary surrogate experiments using a Generative Adversarial Network implementation of the Neural Causal Model. (反事实识别与评估) 

**[Counterfactual Inference] Filtered-CoPhy: Unsupervised Learning of Counterfactual Physics in Pixel Space**. (2022-ICLR) Steeven JANNY, Fabien Baradel, Natalia Neverova, Madiha Nadri, Greg Mori, Christian Wolf. 
**TLDR**: We present a method for learning counterfactual reasoning of physical processes in pixel space, which requires the prediction of the impact of interventions on initial conditions. (像素空间的无监督反事实学习) 

**[Counterfactual Inference] Counterfactual Fairness with Partially Known Causal Graph**. (2022-NIPS) . 
**TLDR**:  This paper proposes a general method to achieve the notion of counterfactual fairness when the true causal graph is unknown. (不完全因果图上的反事实公平性) 

**[Counterfactual Inference] CLEAR: Generative Counterfactual Explanations on Graphs**. (2022-NIPS) Jing Ma, Ruocheng Guo, Saumitra Mishra, Aidong Zhang, Jundong Li. 
**TLDR**: This paper proposes a model-agnostic framework for counterfactual explanations on graphs, facilitating the optimization, generalization, and causality in counterfactual explanation generation. (图上的反事实解释) 

**[Counterfactual Inference] Counterfactual Neural Temporal Point Process for Estimating Causal Influence of Misinformation on Social Media**. (2022-NIPS) Yizhou Zhang, Defu Cao, Yan Liu. 
**TLDR**: Yizhou ZhWe develop a machine learning based counterfactual analysis framework to examine the misinformation's causal influence on people.ang, Defu Cao, Yan Liu (用反事实分析框架来测定错误信息对人们的因果影响) 

**[Counterfactual Inference] Deep Counterfactual Estimation with Categorical Background Variables**. (2022-NIPS) Edward De Brouwer. 
**TLDR**: We propose to estimate counterfactuals of high-dimensional data (time series and images) using a categorical backward variables assumption. (基于分类背景变量假设评估高维数据的反事实) 

**[Counterfactual Inference] Counterfactual Temporal Point Processes**. (2022-NIPS) Kimia Noorbakhsh, Manuel Gomez Rodriguez. 
**TLDR**: The paper introduces a method to simulate counterfactual realizations of the temporal point process under a given alternative intensity function. (时序过程下的反事实解释) 

**[Counterfactual Inference] Doubly Robust Counterfactual Classification**. (2022-NIPS) Kwangho Kim, Edward Kennedy, Jose Ramon Zubizarreta. 
**TLDR**: We study classification problem under counterfactual scenarios where we can incorporate flexible constraints. (反事实情况下的分类问题) 

**[Counterfactual Inference] Fast Instrument Learning with Faster Rates**. (2022-NIPS) Ziyu Wang, Yuhao Zhou, Jun Zhu. 
**TLDR**: We propose a simple algorithm which combines kernelized IV methods and an arbitrary, adaptive regression algorithm, accessed as a black box. (更快收敛的工具学习) 

**[Counterfactual Inference] Cluster Randomized Designs for One-Sided Bipartite Experiments**. (2022-NIPS) Jennifer Rogers Brennan, Vahab Mirrokni, Jean Pouget-Abadie. 
**TLDR**: We present a new clustering objective for cluster-randomized experimental design in marketplace experiments. (随机聚类实验) 

**[Counterfactual Inference] On the Adversarial Robustness of Causal Algorithmic Recourse**. (2022-ICML) Ricardo Dominguez-Olmedo, Amir H Karimi, Bernhard Schölkopf. 
**TLDR**: The paper presents methods for generating adversarially robust recourse for decision-making systems, showing that regularizing the decision-making classifier can facilitate the existence of robust recourse. (提供对抗鲁棒的算法补救) 

**[Counterfactual Inference] Partial Counterfactual Identification from Observational and Experimental Data**. (2022-ICML) Junzhe Zhang, Jin Tian, Elias Bareinboim. 
**TLDR**: This paper proposes a method to estimate counterfactual queries from a combination of observational and experimental data, along with qualitative knowledge, using a canonical family of structural causal models and Monte Carlo algorithms. (从观察和实验数据以及定性知识的组合中估计反事实查询) 

**[Counterfactual Inference] Learning from Counterfactual Links for Link Prediction**. (2022-ICML) Tong Zhao, Gang Liu, Daheng Wang, Wenhao Yu, Meng Jiang. 
**TLDR**: The paper proposes a novel data augmentation-based link prediction method that creates counterfactual links and learns representations from both the observed and counterfactual links by using causal models, achieving state-of-the-art performance on the task of link prediction. (基于数据增强的链接预测方法) 

**[Counterfactual Inference] Causal Transformer for Estimating Counterfactual Outcomes**. (2022-ICML) Valentyn Melnychuk, Dennis Frauen, Stefan Feuerriegel. 
**TLDR**: The paper proposes a novel Causal Transformer model designed to estimate counterfactual outcomes over time from observational data, which is specifically designed to capture complex, long-range dependencies among time-varying confounders, and achieves superior performance over current baselines. (从观测数据中估计一段时间内的反事实结果) 

**[Counterfactual Inference] Causal Inference Through the Structural Causal Marginal Problem**. (2022-ICML) Luigi Gresele, Julius Von Kügelgen, Jonas Kübler, Elke Kirschbaum, Bernhard Schölkopf, Dominik Janzing. 
**TLDR**: The paper proposes an approach to counterfactual inference based on merging information from multiple datasets, reducing the space of allowed SCMs. (基于合并多个数据集信息的反事实推理方法) 

**[Counterfactual Inference] Counterfactual Transportability: A Formal Approach**. (2022-ICML) Juan D Correa, Sanghack Lee, Elias Bareinboim. 
**TLDR**: The paper proposes an algorithm for transporting counterfactual quantities across domains in nonparametric settings to generalize causal knowledge. (非参数设置中跨域传输反事实量) 

**[Counterfactual Inference] Continuous-Time Modeling of Counterfactual Outcomes Using Neural Controlled Differential Equations**. (2022-ICML) Nabeel Seedat, Fergus Imrie, Alexis Bellot, Zhaozhi Qian, Mihaela van der Schaar. 
**TLDR**: The paper proposes TE-CDE, a method that models the latent trajectory of a continuous-time process using controlled differential equations to estimate counterfactual outcomes over time, and utilizes adversarial training to adjust for time-dependent confounding in longitudinal settings. (估计随时间推移的反事实结果) 

**[Counterfactual Inference] Framing Algorithmic Recourse for Anomaly Detection**. (2022-SIGKDD) Debanjan Datta, Feng Chen, Naren Ramakrishnan. 
**TLDR**: We present an approach -- Context preserving Algorithmic Recourse for Anomalies in Tabular data (CARAT), that is effective, scalable, and agnostic to the underlying anomaly detection model. CARAT uses a transformer based encoder-decoder model to explain an anomaly by finding features with low likelihood. Subsequently semantically coherent counterfactuals are generated by modifying the highlighted features, using the overall context of features in the anomalous instance(s). (反事实异常检测) 

**[Counterfactual Inference] Counterfactual Phenotyping with Censored Time-to-Events**. (2022-SIGKDD) Chirag Nagpal, Mononito Goswami, Keith Dufendach, Artur Dubrawski. 
**TLDR**: we present a latent variable approach to model heterogeneous treatment effects by proposing that an individual can belong to one of latent clusters with distinct response characteristics. (潜变量方法模拟异质治疗效果) 

**[Counterfactual Inference] Counterfactual Learning To Rank for Utility-Maximizing Query Autocompletion**. (2022-SIGIR) Adam Block, Rahul Kidambi, Daniel Hill, Thorsten Joachims, Inderjit Dhillon. 
**TLDR**: We proposed a counterfactual learning approach that is able to leverage feedback on the items (e.g., clicks, purchases) to evaluate query suggestions through an unbiased estimator, thus avoiding the assumption that users write or select optimal queries. (反事实提升查询补全任务质量) 

**[Counterfactual Inference] Implicit Feedback for Dense Passage Retrieval: A Counterfactual Approach**. (2022-SIGIR) Shengyao Zhuang, Hang Li, Guido Zuccon. 
**TLDR**: We propose the Counterfactual Rocchio (CoRocchio) algorithm to overcome bias for exploiting implicit feedback in Dense Retrievers (稠密检索中去偏) 

**[Counterfactual Inference] Alleviating Spurious Correlations in Knowledge-aware Recommendations through Counterfactual Generator**. (2022-SIGIR) Shanlei Mu, Yaliang Li, Wayne Xin Zhao, Jingyuan Wang, Bolin Ding and Ji-Rong Wen. 
**TLDR**: we present a novel approach to discovering and alleviating the potential spurious correlations from a counterfactual perspective (反事实增强去除虚假关联) 

### Causal in RecSys

**[Causal in RecSys] StableDR: Stabilized Doubly Robust Learning for Recommendation on Data Missing Not at Random**. (2023-ICLR) Haoxuan Li, Chunyuan Zheng, Peng Wu. 
**TLDR**: This paper proposes a theoretically guaranteed stabilized doubly robust learning approach that overcomes the shortcomings due to the presence of extremely small propensities in debiased recommendations. (双鲁棒学习) 

**[Causal in RecSys] TDR-CL: Targeted Doubly Robust Collaborative Learning for Debiased Recommendations**. (2023-ICLR) Haoxuan Li, Yan Lyu, Chunyuan Zheng, Peng Wu. 
**TLDR**: This paper proposes a principled approach that can effectively reduce the bias and variance simultaneously compared to existing DR estimators for debiased recommendations. (双鲁棒学习) 

**[Causal in RecSys] From Intervention to Domain Transportation: A Novel Perspective to Optimize Recommendation**. (2022-ICLR) Da Xu, Yuting Ye, Chuanwei Ruan, Evren Korpeoglu, Sushant Kumar, Kannan Achan. 
**TLDR**: We propose and study a novel domain-transportation view for optimizing recommendation for information retrieval systems. (域迁移视角看推荐系统优化) 

**[Causal in RecSys] Towards Out-of-Distribution Sequential Event Prediction: A Causal Treatment**. (2022-NIPS) Chenxiao Yang, Qitian Wu, Qingsong Wen, Zhiqiang Zhou, Liang Sun, Junchi Yan. 
**TLDR**: We handle temporal distribution shift in sequential event prediction tasks (时序推荐的下分布偏差问题) 

**[Causal in RecSys] Addressing Unmeasured Confounder for Recommendation with Sensitivity Analysis**. (2022-SIGKDD) Sihao Ding, Peng Wu, Fuli Feng, Yitong Wang, Xiangnan He, Yong Liao, Yongdong Zhang. 
**TLDR**: We propose Robust Deconfounder (RD) that accounts for the effect of unmeasured confounders on propensities, under the mild assumption that the effect is bounded. It estimates the bound with sensitivity analysis, learning a recommender model robust to unmeasured confounders within the bound by adversarial learning. (通过敏感性分析解决推荐的未测量混杂因素) 

**[Causal in RecSys] Invariant Preference Learning for General Debiasing in Recommendation**. (2022-SIGKDD) Zimu Wang, Yue He, Jiashuo Liu, Wenchao Zou, Philip S. Yu, Peng Cui. 
**TLDR**: We propose a novel recommendation framework called InvPref which iteratively decomposes the invariant preference and variant preference from biased observational user behaviors by estimating heterogeneous environments corresponding to different types of latent bias (推荐系统去偏) 

**[Causal in RecSys] Practical Counterfactual Policy Learning for Top-K Recommendations**. (2022-SIGKDD) Yaxu Liu, Jui-Nan Yen, Bowen Yuan, Rundong Shi, Peng Yan, Chih-Jen Lin. 
**TLDR**: This work studies policy learning approaches for top-k recommendations with a large item space and points out several difficulties related to importance weight explosion, observation insufficiency, and training efficiency. A practical frameworkfor policy learning is then proposed to overcome these difficulties (反事实topk推荐去偏) 

**[Causal in RecSys] Deconfounding Duration Bias in Watch-time Prediction for Video Recommendation**. (2022-SIGKDD) Ruohan Zhan, Changhua Pei, Qiang Su, Jianfeng Wen, Xueliang Wang, Guanyu Mu, Dong Zheng, Peng Jiang, Kun Gai. 
**TLDR**: To remove the undesired bias but leverage the natural effect, we propose a Duration-Deconfounded Quantile-based (D2Q) watch-time prediction framework, which allows for scalability to perform on industry production systems. (消除视频推荐中视频时长(混杂因子)的影响) 

**[Causal in RecSys] CausalMTA: Eliminating the User Confounding Bias for Causal Multi-touch Attribution**. (2022-SIGKDD) Di Yao, Chang Gong, Lei Zhang, Sheng Chen, Jingping Bi. 
**TLDR**: we define the causal MTA task and propose CausalMTA to solve this problem. It systemically eliminates the confounding bias from both static and dynamic perspectives and learn an unbiased conversion prediction model using historical data. (消除多触点归因的混杂偏差) 

**[Causal in RecSys] Modeling the Effect of Persuasion Factor on User Decision for Recommendation**. (2022-SIGKDD) Chang Liu, Chen Gao, Yuan Yuan, Chen Bai, Lingrui Luo, Xiaoyi Du, Xinlei Shi, Hengliang Luo, Depeng Jin, Yong Li. 
**TLDR**: We first propose the persuasion-factor graph convolutional layers for encoding and learning representations from the persuasion-aware interaction data. Then we develop a prediction layer that fully considers the user sensitivity to the persuasion factors. Finally, to address the data-sparsity issue, we propose a counterfactual learning-based data augmentation method to enhance the supervision signal.  (用户推荐说服因素的建模(利用了反事实因果数据增强)) 

**[Causal in RecSys] ASPIRE: Air Shipping Recommendation for E-commerce Products via Causal Inference Framework**. (2022-SIGKDD) Abhirup Mondal, Anirban Majumder, Vineet Chaoji. 
**TLDR**: We develop a causal inference framework (referred to as Air Shipping Recommendation or ASPIRE) that balances the trade-off between revenue or conversion and delivery cost to decide whether a product should be shipped via air. We propose a doubly-robust estimation technique followed by an optimization algorithm to determine air eligibility of products and calculate the uplift in revenue and shipping cost. (因果推断框架权衡是否空运商品) 

**[Causal in RecSys] CausalInt: Causal Inspired Intervention for Multi-Scenario Recommendation**. (2022-SIGKDD) Yichao Wang, Huifeng Guo, Bo Chen, Weiwen Liu, Zhirong Liu, Qi Zhang, Zhicheng He, Hongkun Zheng, Weiwei Yao, Muyu Zhang, Zhenhua Dong, Ruiming Tang. 
**TLDR**: we first do analysis on multi-scenario modeling with causal graph from the perspective of users and modeling processes, and then propose the Causal Inspired Intervention (CausalInt) framework for multi-scenario recommendation. (多场景推荐的因果干预) 

**[Causal in RecSys] Unbiased Sequential Recommendation with Latent Confounders**. (2022-WWW) Zhenlei Wang, Shiqi Shen, Zhipeng Wang, Bo Chen, Xu Chen, Ji-Rong Wen. 
**TLDR**: we propose to reformulate the sequential recommendation task with the potential outcome framework and remove the sample selection bias (序列化推荐去偏) 

**[Causal in RecSys] Bilateral Self-unbiased Learning from Biased Implicit Feedback**. (2022-SIGIR) Jae-woong Lee, Seongmin Park, Joonseok Lee, Jongwuk Lee. 
**TLDR**: we propose a novel unbiased recommender learning model, namely BIlateral SElf-unbiased Recommender (BISER), to eliminate the exposure bias of items caused by recommender models (推荐中物品曝光偏差问题) 

### Causal in RL

**[Causal in RL] Combinatorial Pure Exploration of Causal Bandits**. (2023-ICLR) Nuoya Xiong, Wei Chen. 
**TLDR**: Combinatorial pure exploration algorithm of causal bandits on two different models. (因果Bandit的探索算法) 

**[Causal in RL] Causal Contextual Bandits with Targeted Interventions**. (2022-ICLR) Chandrasekar Subramanian, Balaraman Ravindran. 
**TLDR**: A new, more realistic, formalism of contextual bandits involving causal side-information and targeted interventions, along with a novel algorithm that exploits features of the new setting such as information leakage to learn good policies quickly. (引入因果信息的上下文老虎机) 

**[Causal in RL] On Covariate Shift of Latent Confounders in Imitation and Reinforcement Learning**. (2022-ICLR) Guy Tennenholtz, Assaf Hallak, Gal Dalal, Shie Mannor, Gal Chechik, Uri Shalit. 
**TLDR**: We use expert data with unobserved confounders for both imitation and reinforcement learning. Such hidden confounding is prone to a shifted distribution, which may severely hurt performance unless accounted for. (在模仿学习和强化学习中隐混淆因子产生的分布偏移影响) 

**[Causal in RL] Causality-driven Hierarchical Structure Discovery for Reinforcement Learning**. (2022-NIPS) Shaohui Peng, Xing Hu, Rui Zhang, Ke Tang, Jiaming Guo, Qi Yi, Ruizhi Chen, Xishan Zhang, Zidong Du, Ling Li, Qi Guo, Yunji Chen. 
**TLDR**: We propose CDHRL, a causality-driven hierarchical reinforcement learning framework, to build high-quality hierarchical structures efficiently in complicated environments (基于因果优化层次强化学习) 

**[Causal in RL] Generalizing Goal-Conditioned Reinforcement Learning with Variational Causal Reasoning**. (2022-NIPS) Wenhao Ding, Haohong Lin, Bo Li, Ding Zhao. 
**TLDR**: We provably improve the generalization of goal-conditioned reinfocement learning by discovering a causal graph and using it to guide the policy learning. (发掘因果图并以此引导策略学习) 

**[Causal in RL] Explainability Via Causal Self-Talk**. (2022-NIPS) Nicholas Andrew Roy, Junkyung Kim, Neil Charles Rabinowitz. 
**TLDR**: For explainability and control, we train agents to build a causal model of themselves. (因果自对话与可解释) 

**[Causal in RL] Direct Advantage Estimation**. (2022-NIPS) Hsiao-Ru Pan, Nico Gürtler, Alexander Neitz, Bernhard Schölkopf. 
**TLDR**: We propose a novel method to estimate the advantage function and show empirically that it outperforms generalized advantage estimation in various tasks. (基于因果效应的增强函数评估) 

**[Causal in RL] Factored Adaptation for Non-Stationary Reinforcement Learning**. (2022-NIPS) Fan Feng, Biwei Huang, Kun Zhang, Sara Magliacane. 
**TLDR**: We introduce a factored adaptation framework for nonstationary RL and show that learned factored representations improve the rewards and robustness under non-stationarity. (因子自适应框架的不动RL学习) 

**[Causal in RL] Online Reinforcement Learning for Mixed Policy Scopes**. (2022-NIPS) Junzhe Zhang, Elias Bareinboim. 
**TLDR**: This paper investigates the online reinforcement learning setting for optimizing policies with mixed state-action spaces. (在线强化学习下优化策略与混合状态-动作空间) 

**[Causal in RL] Deconfounded Value Decomposition for Multi-Agent Reinforcement Learning**. (2022-ICML) Jiahui Li, Kun Kuang, Baoxiang Wang, Furui Liu, Long Chen, Changjie Fan, Fei Wu, Jun Xiao. 
**TLDR**: The paper proposes a deconfounded value decomposition (DVD) approach for cooperative multi-agent reinforcement learning, which cuts off confounding bias on learning credit assignment, using the trajectory graph as a proxy confounder and achieving better performance. (合作多智能体强化学习) 

**[Causal in RL] Causal Dynamics Learning for Task-Independent State Abstraction**. (2022-ICML) Zizhao Wang, Xuesu Xiao, Zifan Xu, Yuke Zhu, Peter Stone. 
**TLDR**: We introduce Causal Dynamics Learning for Task-Independent State Abstraction (CDL), which first learns a theoretically proved causal dynamics model that removes unnecessary dependencies between state variables and the action, thus generalizing well to unseen states. (因果动态学习) 

**[Causal in RL] Tell me why! Explanations support learning relational and causal structure**. (2022-ICML) Andrew K Lampinen, Nicholas Roy, Ishita Dasgupta, Stephanie Cy Chan, Allison Tam, James Mcclelland, Chen Yan, Adam Santoro, Neil C Rabinowitz, Jane Wang, Felix Hill. 
**TLDR**: The paper explores the role of language in improving deep reinforcement learning agents' ability to acquire abstract relational and causal knowledge and shows that language descriptions and explanations can help agents to learn challenging tasks and infer causal structures. (语言描述和解释可以帮助智能体学习和推断因果结构) 

**[Causal in RL] Deconfounding Actor-Critic Network with Policy Adaptation for Dynamic Treatment Regimes**. (2022-SIGKDD) Changchang Yin, Ruoqi Liu, Jeffrey Caterino, Ping Zhang. 
**TLDR**: we develop a new deconfounding actor-critic network (DAC) to learn optimal DTR policies for patients. To alleviate confounding issues, we incorporate a patient resampling module and a confounding balance module into our actor-critic framework. (动态治疗制度中去混杂因素) 

### Causal in NLP

**[Causal in NLP] WikiWhy: Answering and Explaining Cause-and-Effect Questions**. (2023-ICLR) Matthew Ho, Aditya Sharma, Justin Chang, Michael Saxon, Sharon Levy, Yujie Lu, William Yang Wang. 
**TLDR**: We propose WikiWhy, a dataset containing 9000+ "why" question-answer-rationale triplets to assess Large Language Models' cause-effect reasoning capability. (问答与因果效应) 

**[Causal in NLP] Causal Estimation for Text Data with (Apparent) Overlap Violations**. (2023-ICLR) Lin Gui, Victor Veitch. 
**TLDR**: The purpose of this paper is to show how to handle causal identification and obtain robust causal estimation in the presence of apparent overlap violations. (文本因果效应估计) 

**[Causal in NLP] CEBaB: Estimating the Causal Effects of Real-World Concepts on NLP Model Behavior**. (2022-NIPS) Eldar David Abraham, Karel D'Oosterlinck, Amir Feder, Yair Ori Gat, Atticus Geiger, Christopher Potts, Roi Reichart, Zhengxuan Wu. 
**TLDR**: Casting model explanation as a causal inference problem, we introduce CEBaB, a new benchmark dataset for assessing explanation methods in NLP. (将模型解释作为因果推断问题) 

**[Causal in NLP] Certified Robustness Against Natural Language Attacks by Causal Intervention**. (2022-ICML) Haiteng Zhao, Chang Ma, Xinshuai Dong, Anh Tuan Luu, Zhi-Hong Deng, Hanwang Zhang. 
**TLDR**: CISS achieves robustness against natural language attacks by learning causal effects via semantic smoothing, avoiding customized perturbations for specific attacks. (语义平滑学习因果效应提升对自然语言攻击的鲁棒性) 

**[Causal in NLP] ROCK: Causal Inference Principles for Reasoning about Commonsense Causality**. (2022-ICML) Jiayao Zhang, Hongming Zhang, Weijie Su, Dan Roth. 
**TLDR**: ROCK identifies plausible causes and effects in natural language using classical causal principles and balances confounding effects with temporal signals as a form of incidental supervision, analogous to propensity scores. (自然语言中因果识别) 

**[Causal in NLP] Ask to Know More:Generating Counterfactual Explanations for Fake Claims**. (2022-SIGKDD) Shih-Chieh Dai, Yi-Li Hsu, Aiping Xiong, Lun-Wei Ku. 
**TLDR**: we propose elucidating fact checking predictions using counterfactual explanations to help people understand why a specific piece of news was identified as fake. In this work, generating counterfactual explanations for fake news involves three steps: asking good questions, finding contradictions, and reasoning appropriately. We frame this research question as contradicted entailment reasoning through question answering (QA). (生成反事实的虚假新闻解释) 

**[Causal in NLP] DeSCoVeR: Debiased Semantic Context Prior for Venue Recommendation**. (2022-SIGIR) Sailaja Rajanala, Arghya Pal, Manish Singh, Raphael Phan, Wong Koksheik. 
**TLDR**: We proposed a methodology that we call DeSCoVeR at first elicits these semantic and syntactic features using a Neural Topic Model and text classifier respectively, and then mitigates the document-level label bias using a Causal back-door path criterion and a sentence-level keyword bias removal technique. (利用后门调整消除关键词偏差) 

### Causal in CV

**[Causal in CV] Measuring axiomatic soundness of counterfactual image models**. (2023-ICLR) Miguel Monteiro, Fabio De Sousa Ribeiro, Nick Pawlowski, Daniel C. Castro, Ben Glocker. 
**TLDR**: We use the axiomatic definition of counterfactual to derive metrics that enable quantifying the correctness of approximate counterfactual inference models. (图像反事实评估) 

**[Causal in CV] ConfounderGAN: Protecting Image Data Privacy with Causal Confounder**. (2022-NIPS) Qi Tian, Kun Kuang, Kelu Jiang, Furui Liu, Zhihua Wang, Fei Wu. 
**TLDR**: We propose a causality inspired method, named ConfounderGAN, a generative adversarial network (GAN) to make personal image data unlearnable for protecting the data privacy of its owners. (基于因果方法保护用户的图片隐私) 

**[Causal in CV] Unsupervised Causal Generative Understanding of Images**. (2022-NIPS) Titas Anciukevičius, Patrick Fox-Roberts, Edward Rosten, Paul Henderson. 
**TLDR**: A framework for unsupervised object-centric 3D scene understanding that generalizes robustly to out-of-distribution images.  (非监督的因果图像生成) 

### Causal in Bio

**[Causal in Bio] GEASS: Neural causal feature selection for high-dimensional biological data**. (2023-ICLR) Mingze Dong, Yuval Kluger. 
**TLDR**: We propose a new method (GEASS) to identify causally interacting features for high-dimensional spatial/temporal structured data, and apply it to several biological data to infer causal regulatory patterns. (在高维空间中识别因果交互特征) 

**[Causal in Bio] Predicting Cellular Responses with Variational Causal Inference and Refined Relational Information**. (2023-ICLR) Yulun Wu, Rob Barton, Zichen Wang, Vassilis N. Ioannidis, Carlo De Donno, Layne C Price, Luis F. Voloch, George Karypis. 
**TLDR**: We predict single-cell perturbation responses using a graph variational Bayesian causal inference framework with distilled gene regulatory networks. (预测单细胞扰动) 

**[Causal in Bio] DeepMed: Semiparametric Causal Mediation Analysis with Debiased Deep Learning**. (2022-NIPS) Siqi Xu, Lin Liu, Zhonghua Liu. 
**TLDR**: Causal mediation analysis with deep learning (生物医学中的因果学习) 

**[Causal in Bio] Debiased, Longitudinal and Coordinated Drug Recommendation through Multi-Visit Clinic Records**. (2022-NIPS) Hongda Sun, Shufang Xie, Shuqi Li, Yuhan Chen, Ji-Rong Wen, Rui Yan. 
**TLDR**: This paper proposes a causal inference based method for debiased, longitudinal and coordinated drug recommendation. (基于因果推断的药物推荐) 

### Causal in IR

**[Causal in IR] Using Embeddings for Causal Estimation of Peer Influence in Social Networks**. (2022-NIPS) Irina Cristali, Victor Veitch. 
**TLDR**: We propose a nonparametric method of causally estimating peer influence from observational data, in the presence of unobserved confounding.  (基于非参数化的因果方法评估同伴影响) 


### Contributors

Zeyu Zhang: `ICLR'23`, `NIPS'22`, `ICLR'22`

Heyang Gao: `ICLR'23`, `ICML'22`

Xueyang Feng: `SIGKDD'22`

Hao Yang: `WWW'22`, `SIGIR'22`
