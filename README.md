# Awesome Language Model Analysis [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

This paper list focuses on the **theoretical and empirical analysis** of language models, especially **large language models** (LLMs).
The papers in this list investigate the learning behavior, generalization ability, and other properties of language models through theoretical analysis, empirical analysis, or a combination of both.

Scope of this list:
- Currently, this list focuses on **transformer-based** models.
- We hope to collect papers that only focus on the theoretical and empirical analysis of language models, instead of papers that aim to improve the performance of language models.

Limitations of this list:
- This list is not exhaustive, and we may miss some very important papers.
- This list is not well-organized yet, and we may need to reorganize the list in the future.
- Some popular topics are not well-covered yet, such as mechanistic engineering, probing, and interpretability.

Statistics of This paper list:
- Total number of different papers: **571**
- For more detailed statistics, please refer to the end of this page.

If you have any suggestions or want to contribute, please feel free to open an issue or a pull request.

For details on how to contribute, please refer to the [contribution guidelines](CONTRIBUTING.md).

You can also share your thoughts and discuss with others in the [Discussions](https://github.com/Furyton/awesome-language-model-analysis/discussions).

> [!NOTE]  
> For uncategorized version, please refer to [here](README.uncategorized.md).

Table of Content
====================
<!--ts-->
- [Awesome Language Model Analysis](#awesome-language-model-analysis-)
- [Table of Content](#table-of-content)
  - [**Phenomena of Interest**](#phenomena-of-interest)
    - [**In-Context Learning**](#in-context-learning)
    - [**Chain-of-Thought**](#chain-of-thought)
    - [**Hallucination**](#hallucination)
    - [**Reversal Curse**](#reversal-curse)
    - [**Scaling Laws / Emergent Abilities / Grokking / etc.**](#scaling-laws--emergent-abilities--grokking--etc)
    - [**Knowledge / Memory Mechanisms**](#knowledge--memory-mechanisms)
    - [**Training Dynamics / Landscape / Optimization / Fine-tuning / etc.**](#training-dynamics--landscape--optimization--fine-tuning--etc)
    - [**Learning / Generalization / Reasoning / Weak to Strong Generalization**](#learning--generalization--reasoning--weak-to-strong-generalization)
    - [**Other Phenomena / Discoveries**](#other-phenomena--discoveries)
  - [**Representational Capacity**](#representational-capacity)
    - [**What Can Transformer Do? / Properties of Transformer**](#what-can-transformer-do--properties-of-transformer)
    - [**What Can Transformer Not Do? / Limitation of Transformer**](#what-can-transformer-not-do--limitation-of-transformer)
  - [**Architectural Effectivity**](#architectural-effectivity)
    - [**Layer-normalization**](#layer-normalization)
    - [**Tokenization / Embedding**](#tokenization--embedding)
    - [**Linear Attention / State Space Models / Recurrent Language Models / etc.**](#linear-attention--state-space-models--recurrent-language-models--etc)
  - [**Training Paradigms**](#training-paradigms)
  - [**Mechanistic Engineering / Probing / Interpretability**](#mechanistic-engineering--probing--interpretability)
  - [**Miscellanea**](#miscellanea)
<!--te-->


## **Phenomena of Interest**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Categories focusing on different phenomena, properties, and behaviors observed in large language models (LLMs) and transformer-based models.

### **In-Context Learning**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers focusing on the theoretical and empirical analysis of in-context learning in large language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Transformers are Deep Optimizers: Provable In-Context Learning for Deep Model Training** [[paper link]](http://arxiv.org/abs/2411.16549) 2024-11-25  
Weimin Wu; Maojiang Su; Jerry Yao-Chieh Hu; Zhao Song; Han Liu



- **Can a Large Language Model Learn Matrix Functions In Context?** [[paper link]](http://arxiv.org/abs/2411.15675) 2024-11-24  
Paimon Goulart; Evangelos E. Papalexakis



- **Transformers as Game Players: Provable In-context Game-playing Capabilities of Pre-trained Models** [[paper link]](http://arxiv.org/abs/2410.09701) 2024-11-13  
Chengshuai Shi; Kun Yang; Jing Yang; Cong Shen



- **Adversarial Robustness of In-Context Learning in Transformers for Linear Regression** [[paper link]](http://arxiv.org/abs/2411.05189) 2024-11-07  
Usman Anwar; Johannes Von Oswald; Louis Kirsch; David Krueger; Spencer Frei



- **Provable In-Context Learning with Transformers: A Case Study on Linear Regression** [[paper link]](http://arxiv.org/abs/2411.02199) 2024-11-04  
Dake Bu; Wei Huang; Andi Han; Atsushi Nitanda; Taiji Suzuki; Qingfu Zhang; Hau-San Wong



- **Pretrained transformer efficiently learns low-dimensional target functions in-context** [[paper link]](http://arxiv.org/abs/2411.02544) 2024-11-04  
Kazusato Oko; Yujin Song; Taiji Suzuki; Denny Wu



- **Toward Understanding In-context vs. In-weight Learning** [[paper link]](http://arxiv.org/abs/2410.23042) 2024-10-30  
Bryan Chan; Xinyi Chen; András György; Dale Schuurmans



- **On the Role of Depth and Looping for In-Context Learning with Task Diversity** [[paper link]](http://arxiv.org/abs/2410.21698) 2024-10-29  
Khashayar Gatmiry; Nikunj Saunshi; Sashank J. Reddi; Stefanie Jegelka; Sanjiv Kumar



- **Mechanisms of Symbol Processing for In-Context Learning in Transformer Networks** [[paper link]](http://arxiv.org/abs/2410.17498) 2024-10-23  
Paul Smolensky; Roland Fernandez; Zhenghao Herbert Zhou; Mattia Opper; Jianfeng Gao



- **Can Transformers In-Context Learn Behavior of a Linear Dynamical System?** [[paper link]](http://arxiv.org/abs/2410.16546) 2024-10-21  
Usman Akram; Haris Vikalo



- **Bayesian scaling laws for in-context learning** [[paper link]](http://arxiv.org/abs/2410.16531) 2024-10-21  
Aryaman Arora; Dan Jurafsky; Christopher Potts; Noah D. Goodman



- **Provable In-context Learning for Mixture of Linear Regressions using Transformers** [[paper link]](http://arxiv.org/abs/2410.14183) 2024-10-18  
Yanhao Jin; Krishnakumar Balasubramanian; Lifeng Lai



- **In-context learning and Occam's razor** [[paper link]](http://arxiv.org/abs/2410.14086) 2024-10-17  
Eric Elmoznino; Tom Marty; Tejas Kasetty; Leo Gagnon; Sarthak Mittal; Mahan Fathi; Dhanya Sridhar; Guillaume Lajoie



- **Context-Scaling versus Task-Scaling in In-Context Learning** [[paper link]](http://arxiv.org/abs/2410.12783) 2024-10-16  
Amirhesam Abedsoltan; Adityanarayanan Radhakrishnan; Jingfeng Wu; Mikhail Belkin



- **Bypassing the Exponential Dependency: Looped Transformers Efficiently Learn In-context by Multi-step Gradient Descent** [[paper link]](http://arxiv.org/abs/2410.11268) 2024-10-15  
Bo Chen; Xiaoyu Li; Yingyu Liang; Zhenmei Shi; Zhao Song



- **How Transformers Implement Induction Heads: Approximation and Optimization Analysis** [[paper link]](http://arxiv.org/abs/2410.11474) 2024-10-15  
Mingze Wang; Ruoxi Yu; Weinan E; Lei Wu



- **On the Training Convergence of Transformers for In-Context Classification** [[paper link]](http://arxiv.org/abs/2410.11475) 2024-10-15  
Wei Shen; Ruida Zhou; Jing Yang; Cong Shen



- **Transformers learn variable-order Markov chains in-context** [[paper link]](http://arxiv.org/abs/2410.05493) 2024-10-07  
Ruida Zhou; Chao Tian; Suhas Diggavi



- **Revisiting In-context Learning Inference Circuit in Large Language Models** [[paper link]](http://arxiv.org/abs/2410.04468) 2024-10-06  
Hakaze Cho; Mariko Kato; Yoshihiro Sakai; Naoya Inoue



- **Trained Transformer Classifiers Generalize and Exhibit Benign Overfitting In-Context** [[paper link]](http://arxiv.org/abs/2410.01774) 2024-10-02  
Spencer Frei; Gal Vardi



- **Transformers Handle Endogeneity in In-Context Linear Regression** [[paper link]](http://arxiv.org/abs/2410.01265) 2024-10-02  
Haodong Liang; Krishnakumar Balasubramanian; Lifeng Lai



- **Unveiling Induction Heads: Provable Training Dynamics and Feature Learning in Transformers** [[paper link]](http://arxiv.org/abs/2409.10559) 2024-09-10  
Siyu Chen; Heejune Sheen; Tianhao Wang; Zhuoran Yang



- **Learning vs Retrieval: The Role of In-Context Examples in Regression with LLMs** [[paper link]](http://arxiv.org/abs/2409.04318) 2024-09-06  
Aliakbar Nafar; Kristen Brent Venable; Parisa Kordjamshidi



- **Transformers are Minimax Optimal Nonparametric In-Context Learners** [[paper link]](http://arxiv.org/abs/2408.12186) 2024-08-22  
Juno Kim; Tai Nakamaki; Taiji Suzuki



- **Memorisation In In-Context Learning** [[paper link]](http://arxiv.org/abs/2408.11546) 2024-08-21  
Shahriar Golchin; Mihai Surdeanu; Steven Bethard; Eduardo Blanco; Ellen Riloff



- **In-Context Learning with Representations: Contextual Generalization of Trained Transformers** [[paper link]](http://arxiv.org/abs/2408.10147) 2024-08-19  
Tong Yang; Yu Huang; Yingbin Liang; Yuejie Chi



- **Fast Training Dataset Attribution via In-Context Learning** [[paper link]](http://arxiv.org/abs/2408.11852) 2024-08-14  
Milad Fotouhi; Mohammad Taha Bahadori; Oluwaseyi Feyisetan; Payman Arabshahi; David Heckerman



- **How Transformers Utilize Multi-Head Attention in In-Context Learning? A Case Study on Sparse Linear Regression** [[paper link]](http://arxiv.org/abs/2408.04532) 2024-08-08  
Xingwu Chen; Lei Zhao; Difan Zou



- **Transformers are Universal In-context Learners** [[paper link]](http://arxiv.org/abs/2408.01367) 2024-08-02  
Takashi Furuya; Maarten V. de Hoop; Gabriel Peyré



- **Polynomial Regression as a Task for Understanding In-context Learning Through Finetuning and Alignment** [[paper link]](http://arxiv.org/abs/2407.19346) 2024-07-27  
Max Wilcoxson; Morten Svendgård; Ria Doshi; Dylan Davis; Reya Vir; Anant Sahai



- **Unveiling In-Context Learning: A Coordinate System to Understand Its Working Mechanism** [[paper link]](http://arxiv.org/abs/2407.17011) 2024-07-24  
Anhao Zhao; Fanghua Ye; Jinlan Fu; Xiaoyu Shen



- **One-Layer Transformer Provably Learns One-Nearest Neighbor In Context** [[paper link]](https://klusowski.princeton.edu/sites/g/files/toruqf5901/files/documents/li2024one.pdf) 2024-07-24  
Zihao Li; Yuan Cao; Cheng Gao; Yihan He; Han Liu; Jason M. Klusowski; Jianqing Fan; Mengdi Wang



- **When can transformers compositionally generalize in-context?** [[paper link]](http://arxiv.org/abs/2407.12275) 2024-07-17  
Seijin Kobayashi; Simon Schug; Yassir Akram; Florian Redhardt; Johannes von Oswald; Razvan Pascanu; Guillaume Lajoie; João Sacramento



- **In-Context In-Context Learning with Transformer Neural Processes** [[paper link]](http://arxiv.org/abs/2406.13493) 2024-06-19  
Matthew Ashman; Cristiana Diaconu; Adrian Weller; Richard E. Turner



- **Probing the Decision Boundaries of In-context Learning in Large Language Models** [[paper link]](http://arxiv.org/abs/2406.11233) 2024-06-17  
Siyan Zhao; Tung Nguyen; Aditya Grover



- **State Soup: In-Context Skill Learning, Retrieval and Mixing** [[paper link]](http://arxiv.org/abs/2406.08423) 2024-06-12  
Maciej Pióro; Maciej Wołczyk; Razvan Pascanu; Johannes von Oswald; João Sacramento



- **Estimating the Hallucination Rate of Generative AI** [[paper link]](http://arxiv.org/abs/2406.07457) 2024-06-11  
Andrew Jesson; Nicolas Beltran-Velez; Quentin Chu; Sweta Karlekar; Jannik Kossen; Yarin Gal; John P. Cunningham; David Blei



- **BERTs are Generative In-Context Learners** [[paper link]](http://arxiv.org/abs/2406.04823) 2024-06-07  
David Samuel



- **Enhancing In-Context Learning Performance with just SVD-Based Weight Pruning: A Theoretical Perspective** [[paper link]](http://arxiv.org/abs/2406.03768) 2024-06-06  
Xinhao Yao; Xiaolin Hu; Shenzhi Yang; Yong Liu



- **What Do Language Models Learn in Context? The Structured Task Hypothesis** [[paper link]](http://arxiv.org/abs/2406.04216) 2024-06-06  
Jiaoda Li; Yifan Hou; Mrinmaya Sachan; Ryan Cotterell



- **Exact Conversion of In-Context Learning to Model Weights in Linearized-Attention Transformers** [[paper link]](http://arxiv.org/abs/2406.02847) 2024-06-05  
Brian K Chen; Tianyang Hu; Hui Jin; Hwee Kuan Lee; Kenji Kawaguchi



- **Learning to grok: Emergence of in-context learning and skill composition in modular arithmetic tasks** [[paper link]](http://arxiv.org/abs/2406.02550) 2024-06-04  
Tianyu He; Darshil Doshi; Aritra Das; Andrey Gromov



- **Why Larger Language Models Do In-context Learning Differently?** [[paper link]](http://arxiv.org/abs/2405.19592) 2024-05-30  
Zhenmei Shi; Junyi Wei; Zhuoyan Xu; Yingyu Liang



- **Is In-Context Learning Sufficient for Instruction Following in LLMs?** [[paper link]](http://arxiv.org/abs/2405.19874) 2024-05-30  
Hao Zhao; Maksym Andriushchenko; Francesco Croce; Nicolas Flammarion



- **Does learning the right latent variables necessarily improve in-context learning?** [[paper link]](http://arxiv.org/abs/2405.19162) 2024-05-29  
Sarthak Mittal; Eric Elmoznino; Leo Gagnon; Sangnie Bhardwaj; Dhanya Sridhar; Guillaume Lajoie



- **A Theory of In-Context Learning in Transformers** [[paper link]](http://arxiv.org/abs/2405.18634) 2024-05-29  
Yifei Wang; Yuyang Wu; Zeming Wei; Stefanie Jegelka; Yisen Wang



- **On Mesa-Optimization in Autoregressively Trained Transformers: Emergence and Capability** [[paper link]](http://arxiv.org/abs/2405.16845) 2024-05-27  
Chenyu Zheng; Wei Huang; Rongzhen Wang; Guoqiang Wu; Jun Zhu; Chongxuan Li



- **Transformer In-Context Learning for Categorical Data** [[paper link]](http://arxiv.org/abs/2405.17248) 2024-05-27  
Aaron T. Wang; Ricardo Henao; Lawrence Carin



- **Automatic Domain Adaptation by Transformers in In-Context Learning** [[paper link]](http://arxiv.org/abs/2405.16819) 2024-05-27  
Ryuichiro Hataya; Kota Matsui; Masaaki Imaizumi



- **Unifying Demonstration Selection and Compression for In-Context Learning** [[paper link]](http://arxiv.org/abs/2405.17062) 2024-05-27  
Jun Gao



- **On the Noise Robustness of In-Context Learning for Text Generation** [[paper link]](http://arxiv.org/abs/2405.17264) 2024-05-27  
Hongfu Gao; Feipeng Zhang; Wenyu Jiang; Jun Shu; Feng Zheng; Hongxin Wei



- **MLPs Learn In-Context** [[paper link]](http://arxiv.org/abs/2405.15618) 2024-05-24  
William L. Tong; Cengiz Pehlevan



- **Towards Better Understanding of In-Context Learning Ability from In-Context Uncertainty Quantification** [[paper link]](http://arxiv.org/abs/2405.15115) 2024-05-24  
Shang Liu; Zhongze Cai; Guanting Chen; Xiaocheng Li



- **Can Looped Transformers Learn to Implement Multi-step Gradient Descent for In-context Learning?** [[paper link]](https://openreview.net/pdf?id=o8AaRKbP9K) 2024-05-02  
Khashayar Gatmiry; Nikunj Saunshi; Sashank J. Reddi; Stefanie Jegelka; Sanjiv Kumar



- **In-context Learning on Function Classes Unveiled for Transformers** [[paper link]](https://openreview.net/pdf?id=rJkGOARXns) 2024-05-02  
Zhijie Wang; Bo Jiang; Shuai Li



- **In-Context Learning with Long-Context Models: An In-Depth Exploration** [[paper link]](http://arxiv.org/abs/2405.00200) 2024-04-30  
Amanda Bertsch; Maor Ivgi; Uri Alon; Jonathan Berant; Matthew R. Gormley; Graham Neubig



- **What needs to go right for an induction head? A mechanistic study of in-context learning circuits and their formation** [[paper link]](http://arxiv.org/abs/2404.07129) 2024-04-10  
Aaditya K. Singh; Ted Moskovitz; Felix Hill; Stephanie C. Y. Chan; Andrew M. Saxe



- **Is attention required for ICL? Exploring the Relationship Between Model Architecture and In-Context Learning Ability** [[paper link]](http://arxiv.org/abs/2310.08049) 2024-04-01  
Ivan Lee; Nan Jiang; Taylor Berg-Kirkpatrick



- **Training Dynamics of Multi-Head Softmax Attention for In-Context Learning: Emergence, Convergence, and Optimality** [[paper link]](http://arxiv.org/abs/2402.19442) 2024-02-29  
Siyu Chen; Heejune Sheen; Tianhao Wang; Zhuoran Yang



- **How Transformers Learn Causal Structure with Gradient Descent** [[paper link]](http://arxiv.org/abs/2402.14735) 2024-02-22  
Eshaan Nichani; Alex Damian; Jason D. Lee



- **In-Context Learning of a Linear Transformer Block: Benefits of the MLP Component and One-Step GD Initialization** [[paper link]](http://arxiv.org/abs/2402.14951) 2024-02-22  
Ruiqi Zhang; Jingfeng Wu; Peter L. Bartlett



- **Identifying Semantic Induction Heads to Understand In-Context Learning** [[paper link]](http://arxiv.org/abs/2402.13055) 2024-02-20  
Jie Ren; Qipeng Guo; Hang Yan; Dongrui Liu; Xipeng Qiu; Dahua Lin



- **How do Transformers perform In-Context Autoregressive Learning?** [[paper link]](http://arxiv.org/abs/2402.05787) 2024-02-08  
Michael E. Sander; Raja Giryes; Taiji Suzuki; Mathieu Blondel; Gabriel Peyré



- **Can Mamba Learn How to Learn? A Comparative Study on In-Context Learning Tasks** [[paper link]](http://arxiv.org/abs/2402.04248) 2024-02-06  
Jongho Park; Jaeseung Park; Zheyang Xiong; Nayoung Lee; Jaewoong Cho; Samet Oymak; Kangwook Lee; Dimitris Papailiopoulos



- **An Information-Theoretic Analysis of In-Context Learning** [[paper link]](http://arxiv.org/abs/2401.15530) 2024-01-28  
Hong Jun Jeon; Jason D. Lee; Qi Lei; Benjamin Van Roy



- **The Transient Nature of Emergent In-Context Learning in Transformers** [[paper link]](http://arxiv.org/abs/2311.08360) 2023-12-11  
Aaditya K. Singh; Stephanie C. Y. Chan; Ted Moskovitz; Erin Grant; Andrew M. Saxe; Felix Hill



- **In-Context Learning Functions with Varying Number of Minima** [[paper link]](http://arxiv.org/abs/2311.12538) 2023-11-21  
David Oniani; Yanshan Wang



- **Exploring the Relationship between In-Context Learning and Instruction Tuning** [[paper link]](http://arxiv.org/abs/2311.10367) 2023-11-17  
Hanyu Duan; Yixuan Tang; Yi Yang; Ahmed Abbasi; Kar Yan Tam



- **When does In-context Learning Fall Short and Why? A Study on Specification-Heavy Tasks** [[paper link]](http://arxiv.org/abs/2311.08993) 2023-11-15  
Hao Peng; Xiaozhi Wang; Jianhui Chen; Weikai Li; Yunjia Qi; Zimu Wang; Zhili Wu; Kaisheng Zeng; Bin Xu; Lei Hou; Juanzi Li



- **In-context Learning Generalizes, But Not Always Robustly: The Case of Syntax** [[paper link]](http://arxiv.org/abs/2311.07811) 2023-11-13  
Aaron Mueller; Albert Webson; Jackson Petty; Tal Linzen



- **Transformers learn to implement preconditioned gradient descent for in-context learning** [[paper link]](http://arxiv.org/abs/2306.00297) 2023-11-09  
Kwangjun Ahn; Xiang Cheng; Hadi Daneshmand; Suvrit Sra



- **Transformers Learn Higher-Order Optimization Methods for In-Context Learning: A Study with Linear Models** [[paper link]](https://arxiv.org/abs/2310.17086v1) 2023-10-26  
Deqing Fu; Tian-Qi Chen; Robin Jia; Vatsal Sharan



- **In-Context Learning Creates Task Vectors** [[paper link]](http://arxiv.org/abs/2310.15916) 2023-10-24  
Roee Hendel; Mor Geva; Amir Globerson



- **Function Vectors in Large Language Models** [[paper link]](http://arxiv.org/abs/2310.15213) 2023-10-23  
Eric Todd; Millicent L. Li; Arnab Sen Sharma; Aaron Mueller; Byron C. Wallace; David Bau



- **In-context Learning with Transformer Is Really Equivalent to a Contrastive Learning Pattern** [[paper link]](http://arxiv.org/abs/2310.13220) 2023-10-19  
Ruifeng Ren; Yong Liu



- **Trained Transformers Learn Linear Models In-Context** [[paper link]](http://arxiv.org/abs/2306.09927) 2023-10-19  
Ruiqi Zhang; Spencer Frei; Peter L. Bartlett



- **How Do Transformers Learn In-Context Beyond Simple Functions? A Case Study on Learning with Representations** [[paper link]](http://arxiv.org/abs/2310.10616) 2023-10-16  
Tianyu Guo; Wei Hu; Song Mei; Huan Wang; Caiming Xiong; Silvio Savarese; Yu Bai



- **Understanding In-Context Learning in Transformers and LLMs by Learning to Learn Discrete Functions** [[paper link]](https://openreview.net/forum?id=ekeyCgeRfC) 2023-10-13  
Satwik Bhattamishra; Arkil Patel; Phil Blunsom; Varun Kanade



- **How Many Pretraining Tasks Are Needed for In-Context Learning of Linear Regression?** [[paper link]](https://openreview.net/forum?id=vSh5ePa0ph) 2023-10-13  
Jingfeng Wu; Difan Zou; Zixiang Chen; Vladimir Braverman; Quanquan Gu; Peter Bartlett



- **In-Context Learning Learns Label Relationships but Is Not Conventional Learning** [[paper link]](https://openreview.net/forum?id=YPIA7bgd5y) 2023-10-13  
Jannik Kossen; Yarin Gal; Tom Rainforth



- **In-context Convergence of Transformers** [[paper link]](https://openreview.net/forum?id=kxpswbhr1r) 2023-10-13  
Yu Huang; Yuan Cheng; Yingbin Liang



- **In-Context Learning through the Bayesian Prism** [[paper link]](https://openreview.net/forum?id=HX5ujdsSon) 2023-10-13  
Madhur Panwar; Kabir Ahuja; Navin Goyal



- **Do pretrained Transformers Really Learn In-context by Gradient Descent?** [[paper link]](http://arxiv.org/abs/2310.08540) 2023-10-12  
Lingfeng Shen; Aayush Mishra; Daniel Khashabi



- **What and How does In-Context Learning Learn? Bayesian Model Averaging, Parameterization, and Generalization** [[paper link]](http://arxiv.org/abs/2305.19420) 2023-10-10  
Yufeng Zhang; Fengzhuo Zhang; Zhuoran Yang; Zhaoran Wang



- **Explaining Emergent In-Context Learning as Kernel Regression** [[paper link]](http://arxiv.org/abs/2305.12766) 2023-10-05  
Chi Han; Ziqi Wang; Han Zhao; Heng Ji



- **CausalLM is not optimal for in-context learning** [[paper link]](http://arxiv.org/abs/2308.06912) 2023-09-02  
Nan Ding; Tomer Levinboim; Jialin Wu; Sebastian Goodman; Radu Soricut



- **One Step of Gradient Descent is Provably the Optimal In-Context Learner with One Layer of Linear Self-Attention** [[paper link]](http://arxiv.org/abs/2307.03576) 2023-07-07  
Arvind Mahankali; Tatsunori B. Hashimoto; Tengyu Ma



- **Transformers as Statisticians: Provable In-Context Learning with In-Context Algorithm Selection** [[paper link]](http://arxiv.org/abs/2306.04637) 2023-07-06  
Yu Bai; Fan Chen; Huan Wang; Caiming Xiong; Song Mei



- **Transformers Learn In-Context by Gradient Descent** [[paper link]](https://openreview.net/forum?id=tHvXrFQma5) 2023-06-15  
Johannes Von Oswald; Eyvind Niklasson; Ettore Randazzo; Joao Sacramento; Alexander Mordvintsev; Andrey Zhmoginov; Max Vladymyrov



- **The Closeness of In-Context Learning and Weight Shifting for Softmax Regression** [[paper link]](http://arxiv.org/abs/2304.13276) 2023-04-26  
Shuai Li; Zhao Song; Yu Xia; Tong Yu; Tianyi Zhou



- **A Theory of Emergent In-Context Learning as Implicit Structure Induction** [[paper link]](http://arxiv.org/abs/2303.07971) 2023-03-14  
Michael Hahn; Navin Goyal



- **The Learnability of In-Context Learning** [[paper link]](http://arxiv.org/abs/2303.07895) 2023-03-14  
Noam Wies; Yoav Levine; Amnon Shashua



- **What Can Transformers Learn In-Context? A Case Study of Simple Function Classes** [[paper link]](http://arxiv.org/abs/2208.01066) 2023-01-14  
Shivam Garg; Dimitris Tsipras; Percy Liang; Gregory Valiant



- **Transformers generalize differently from information stored in context vs in weights** [[paper link]](http://arxiv.org/abs/2210.05675) 2022-10-13  
Stephanie C. Y. Chan; Ishita Dasgupta; Junkyung Kim; Dharshan Kumaran; Andrew K. Lampinen; Felix Hill



- **In-Context Learning and Induction Heads** [[paper link]](http://arxiv.org/abs/2209.11895) 2022-09-24  
Catherine Olsson; Nelson Elhage; Neel Nanda; Nicholas Joseph; Nova DasSarma; Tom Henighan; Ben Mann; Amanda Askell; Yuntao Bai; Anna Chen; Tom Conerly; Dawn Drain; Deep Ganguli; Zac Hatfield-Dodds; Danny Hernandez; Scott Johnston; Andy Jones; Jackson Kernion; Liane Lovitt; Kamal Ndousse; Dario Amodei; Tom Brown; Jack Clark; Jared Kaplan; Sam McCandlish; Chris Olah

</details>


### **Chain-of-Thought**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers analyzing the chain-of-thought phenomenon in large language models, exploring theoretical and empirical perspectives.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Rethinking Thinking Tokens: Understanding Why They Underperform in Practice** [[paper link]](http://arxiv.org/abs/2411.11371) 2024-11-18  
Sreeram Vennam; David Valente; David Herel; Ponnurangam Kumaraguru



- **What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A Gradient Perspective** [[paper link]](http://arxiv.org/abs/2410.23743) 2024-10-31  
Ming Li; Yanhong Li; Tianyi Zhou



- **A Theoretical Understanding of Chain-of-Thought: Coherent Reasoning and Error-Aware Demonstration** [[paper link]](https://arxiv.org/abs/2410.16540v1) 2024-10-21  
Yingqian Cui; Pengfei He; Xianfeng Tang; Qi He; Chen Luo; Jiliang Tang; Yue Xing



- **Transformers Provably Solve Parity Efficiently with Chain of Thought** [[paper link]](http://arxiv.org/abs/2410.08633) 2024-10-11  
Juno Kim; Taiji Suzuki



- **From Sparse Dependence to Sparse Attention: Unveiling How Chain-of-Thought Enhances Transformer Sample Efficiency** [[paper link]](http://arxiv.org/abs/2410.05459) 2024-10-07  
Kaiyue Wen; Huaqing Zhang; Hongzhou Lin; Jingzhao Zhang



- **Training Nonlinear Transformers for Chain-of-Thought Inference: A Theoretical Generalization Analysis** [[paper link]](http://arxiv.org/abs/2410.02167) 2024-10-03  
Hongkang Li; Meng Wang; Songtao Lu; Xiaodong Cui; Pin-Yu Chen



- **Autoregressive + Chain of Thought (CoT) ≃ Recurrent: Recurrence's Role in Language Models and a Revist of Recurrent Transformer** [[paper link]](http://arxiv.org/abs/2409.09239) 2024-09-14  
Xiang Zhang; Muhammad Abdul-Mageed; Laks V.S. Lakshmanan



- **Unveiling the Statistical Foundations of Chain-of-Thought Prompting Methods** [[paper link]](http://arxiv.org/abs/2408.14511) 2024-08-25  
Xinyang Hu; Fengzhuo Zhang; Siyu Chen; Zhuoran Yang



- **Deciphering the Factors Influencing the Efficacy of Chain-of-Thought: Probability, Memorization, and Noisy Reasoning** [[paper link]](http://arxiv.org/abs/2407.01687) 2024-07-01  
Akshara Prabhakar; Thomas L. Griffiths; R. Thomas McCoy



- **On the Representational Capacity of Neural Language Models with Chain-of-Thought Reasoning** [[paper link]](http://arxiv.org/abs/2406.14197) 2024-06-20  
Franz Nowak; Anej Svete; Alexandra Butoi; Ryan Cotterell



- **Iteration Head: A Mechanistic Study of Chain-of-Thought** [[paper link]](http://arxiv.org/abs/2406.02128) 2024-06-04  
Vivien Cabannes; Charles Arnal; Wassim Bouaziz; Alice Yang; Francois Charton; Julia Kempe



- **Let's Think Dot by Dot: Hidden Computation in Transformer Language Models** [[paper link]](http://arxiv.org/abs/2404.15758) 2024-04-24  
Jacob Pfau; William Merrill; Samuel R. Bowman



- **Chain of Thought Empowers Transformers to Solve Inherently Serial Problems** [[paper link]](http://arxiv.org/abs/2402.12875) 2024-02-20  
Zhiyuan Li; Hong Liu; Denny Zhou; Tengyu Ma



- **Towards Revealing the Mystery behind Chain of Thought: A Theoretical Perspective** [[paper link]](http://arxiv.org/abs/2305.15408) 2023-12-22  
Guhao Feng; Bohang Zhang; Yuntian Gu; Haotian Ye; Di He; Liwei Wang



- **Why Can Large Language Models Generate Correct Chain-of-Thoughts?** [[paper link]](http://arxiv.org/abs/2310.13571) 2023-10-20  
Rasul Tutunov; Antoine Grosnit; Juliusz Ziomek; Jun Wang; Haitham Bou-Ammar



- **How Large Language Models Implement Chain-of-Thought?** [[paper link]](https://openreview.net/forum?id=b2XfOm3RJa) 2023-10-13  
Yiqun Wang; Sile Hu; Yonggang Zhang; Xiang Tian; Xuesong Liu; Yaowu Chen; Xu Shen; Jieping Ye



- **The Expressive Power of Transformers with Chain of Thought** [[paper link]](https://openreview.net/forum?id=NjNGlPh8Wh) 2023-10-13  
William Merrill; Ashish Sabharwal

</details>


### **Hallucination**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers examining the hallucination phenomenon in language models, including both theoretical and empirical analysis.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **On the Limits of Language Generation: Trade-Offs Between Hallucination and Mode Collapse** [[paper link]](http://arxiv.org/abs/2411.09642) 2024-11-14  
Alkis Kalavasis; Anay Mehrotra; Grigoris Velegkas



- **No Free Lunch: Fundamental Limits of Learning Non-Hallucinating Generative Models** [[paper link]](http://arxiv.org/abs/2410.19217) 2024-10-24  
Changlong Wu; Ananth Grama; Wojciech Szpankowski



- **Shared Imagination: LLMs Hallucinate Alike** [[paper link]](http://arxiv.org/abs/2407.16604) 2024-07-23  
Yilun Zhou; Caiming Xiong; Silvio Savarese; Chien-Sheng Wu



- **Estimating the Hallucination Rate of Generative AI** [[paper link]](http://arxiv.org/abs/2406.07457) 2024-06-11  
Andrew Jesson; Nicolas Beltran-Velez; Quentin Chu; Sweta Karlekar; Jannik Kossen; Yarin Gal; John P. Cunningham; David Blei



- **Does Fine-Tuning LLMs on New Knowledge Encourage Hallucinations?** [[paper link]](http://arxiv.org/abs/2405.05904) 2024-05-09  
Zorik Gekhman; Gal Yona; Roee Aharoni; Matan Eyal; Amir Feder; Roi Reichart; Jonathan Herzig



- **Mechanisms of non-factual hallucinations in language models** [[paper link]](http://arxiv.org/abs/2403.18167) 2024-03-26  
Lei Yu; Meng Cao; Jackie Chi Kit Cheung; Yue Dong



- **Unfamiliar Finetuning Examples Control How Language Models Hallucinate** [[paper link]](http://arxiv.org/abs/2403.05612) 2024-03-08  
Katie Kang; Eric Wallace; Claire Tomlin; Aviral Kumar; Sergey Levine



- **In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation** [[paper link]](http://arxiv.org/abs/2403.01548) 2024-03-05  
Shiqi Chen; Miao Xiong; Junteng Liu; Zhengxuan Wu; Teng Xiao; Siyang Gao; Junxian He



- **Calibrated Language Models Must Hallucinate** [[paper link]](http://arxiv.org/abs/2311.14648) 2023-11-24  
Adam Tauman Kalai; Santosh S. Vempala



- **The Curious Case of Hallucinatory Unanswerablity: Finding Truths in the Hidden States of Over-Confident Large Language Models** [[paper link]](http://arxiv.org/abs/2310.11877) 2023-10-18  
Aviv Slobodkin; Omer Goldman; Avi Caciularu; Ido Dagan; Shauli Ravfogel

</details>


### **Reversal Curse**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers that analyze the reversal curse phenomenon in large language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Towards a Theoretical Understanding of the 'Reversal Curse' via Training Dynamics** [[paper link]](http://arxiv.org/abs/2405.04669) 2024-05-07  
Hanlin Zhu; Baihe Huang; Shaolun Zhang; Michael Jordan; Jiantao Jiao; Yuandong Tian; Stuart Russell



- **The Reversal Curse: LLMs trained on "A is B" fail to learn "B is A"** [[paper link]](http://arxiv.org/abs/2309.12288) 2024-04-04  
Lukas Berglund; Meg Tong; Max Kaufmann; Mikita Balesni; Asa Cooper Stickland; Tomasz Korbak; Owain Evans



- **An Investigation of LLMs' Inefficacy in Understanding Converse Relations** [[paper link]](https://aclanthology.org/2023.emnlp-main.429) 2023-12-01  
Chengwen Qi; Bowen Li; Binyuan Hui; Bailin Wang; Jinyang Li; Jinwang Wu; Yuanjun Laili



- **Physics of Language Models: Part 3.2, Knowledge Manipulation** [[paper link]](http://arxiv.org/abs/2309.14402) 2023-09-25  
Zeyuan Allen-Zhu; Yuanzhi Li



- **The Reversal Curse: Which Tokens You Predict Underlie the Factorization Curse and More** [[paper link]](http://arxiv.org/abs/2306.05183) 2023-06-07  
Ouail Kitouni; Niklas Nolte; Diane Bouchacourt; Adina Williams; Mike Rabbat; Mark Ibrahim

</details>


### **Scaling Laws / Emergent Abilities / Grokking / etc.**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers exploring how model performance scales with model size, data size, or computational resources, and the emergence of unexpected abilities.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Understanding Scaling Laws with Statistical and Approximation Theory for Transformer Neural Networks on Intrinsically Low-dimensional Data** [[paper link]](http://arxiv.org/abs/2411.06646) 2024-11-11  
Alex Havrilla; Wenjing Liao



- **Scaling Laws for Precision** [[paper link]](http://arxiv.org/abs/2411.04330) 2024-11-07  
Tanishq Kumar; Zachary Ankner; Benjamin F. Spector; Blake Bordelon; Niklas Muennighoff; Mansheej Paul; Cengiz Pehlevan; Christopher Ré; Aditi Raghunathan



- **Unlocking the Theory Behind Scaling 1-Bit Neural Networks** [[paper link]](http://arxiv.org/abs/2411.01663) 2024-11-03  
Majid Daliri; Zhao Song; Chiwun Yang



- **How Does Critical Batch Size Scale in Pre-training?** [[paper link]](http://arxiv.org/abs/2410.21676) 2024-10-29  
Hanlin Zhang; Depen Morwani; Nikhil Vyas; Jingfeng Wu; Difan Zou; Udaya Ghai; Dean Foster; Sham Kakade



- **An Information Theory of Compute-Optimal Size Scaling, Emergence, and Plateaus in Language Models** [[paper link]](https://arxiv.org/abs/2410.01243) 2024-10-15  
Anuj K. Nayak; Lav R. Varshney



- **A Hitchhiker's Guide to Scaling Law Estimation** [[paper link]](http://arxiv.org/abs/2410.11840) 2024-10-15  
Leshem Choshen; Yang Zhang; Jacob Andreas



- **Scaling Laws Across Model Architectures: A Comparative Analysis of Dense and MoE Models in Large Language Models** [[paper link]](https://arxiv.org/abs/2410.05661) 2024-10-08  
Siqi Wang; Zhengyu Chen; Bei Li; Keqing He; Min Zhang; Jingang Wang



- **Grokking at the Edge of Linear Separability** [[paper link]](https://arxiv.org/abs/2410.04489) 2024-10-06  
Alon Beck; Noam Levi; Yohai Bar-Sinai



- **An Empirical Study of Scaling Laws for Transfer** [[paper link]](https://arxiv.org/abs/2408.16947) 2024-08-30  
Matthew Barnett



- **A Percolation Model of Emergence: Analyzing Transformers Trained on a Formal Language** [[paper link]](http://arxiv.org/abs/2408.12578) 2024-08-22  
Ekdeep Singh Lubana; Kyogo Kawaguchi; Robert P. Dick; Hidenori Tanaka



- **Scaling Law with Learning Rate Annealing** [[paper link]](http://arxiv.org/abs/2408.11029) 2024-08-20  
Howe Tissue; Venus Wang; Lu Wang



- **Performance Law of Large Language Models** [[paper link]](http://arxiv.org/abs/2408.09895) 2024-08-19  
Chuhan Wu; Ruiming Tang



- **Information-Theoretic Progress Measures reveal Grokking is an Emergent Phase Transition** [[paper link]](http://arxiv.org/abs/2408.08944) 2024-08-16  
Kenzo Clauw; Sebastiano Stramaglia; Daniele Marinazzo



- **Large Language Monkeys: Scaling Inference Compute with Repeated Sampling** [[paper link]](http://arxiv.org/abs/2407.21787) 2024-07-31  
Bradley Brown; Jordan Juravsky; Ryan Ehrlich; Ronald Clark; Quoc V. Le; Christopher Ré; Azalia Mirhoseini



- **Emergence in non-neural models: grokking modular arithmetic via average gradient outer product** [[paper link]](http://arxiv.org/abs/2407.20199) 2024-07-29  
Neil Mallinar; Daniel Beaglehole; Libin Zhu; Adityanarayanan Radhakrishnan; Parthe Pandit; Mikhail Belkin



- **Exploring Scaling Trends in LLM Robustness** [[paper link]](http://arxiv.org/abs/2407.18213) 2024-07-25  
Nikolaus Howe; Michał Zajac; Ian McKenzie; Oskar Hollinsworth; Tom Tseng; Pierre-Luc Bacon; Adam Gleave



- **Understanding the Interplay of Scale, Data, and Bias in Language Models: A Case Study with BERT** [[paper link]](http://arxiv.org/abs/2407.21058) 2024-07-25  
Muhammad Ali; Swetasudha Panda; Qinlan Shen; Michael Wick; Ari Kobren



- **Scaling Laws with Vocabulary: Larger Models Deserve Larger Vocabularies** [[paper link]](http://arxiv.org/abs/2407.13623) 2024-07-18  
Chaofan Tao; Qian Liu; Longxu Dou; Niklas Muennighoff; Zhongwei Wan; Ping Luo; Min Lin; Ngai Wong



- **Why Do You Grok? A Theoretical Analysis of Grokking Modular Addition** [[paper link]](http://arxiv.org/abs/2407.12332) 2024-07-17  
Mohamad Amin Mohamadi; Zhiyuan Li; Lei Wu; Danica J. Sutherland



- **Predicting Emergent Capabilities by Finetuning** [[paper link]](https://openreview.net/pdf?id=vL8BIGuFTF) 2024-07-10  
Charlie Victor Snell; Eric Wallace; Dan Klein; Sergey Levine



- **Resolving Discrepancies in Compute-Optimal Scaling of Language Models** [[paper link]](http://arxiv.org/abs/2406.19146) 2024-06-25  
Tomer Porian; Mitchell Wortsman; Jenia Jitsev; Ludwig Schmidt; Yair Carmon



- **Scaling Laws for Linear Complexity Language Models** [[paper link]](http://arxiv.org/abs/2406.16690) 2024-06-24  
Xuyang Shen; Dong Li; Ruitao Leng; Zhen Qin; Weigao Sun; Yiran Zhong



- **Scaling Laws for Fact Memorization of Large Language Models** [[paper link]](http://arxiv.org/abs/2406.15720) 2024-06-22  
Xingyu Lu; Xiaonan Li; Qinyuan Cheng; Kai Ding; Xuanjing Huang; Xipeng Qiu



- **Reconciling Kaplan and Chinchilla Scaling Laws** [[paper link]](http://arxiv.org/abs/2406.12907) 2024-06-12  
Tim Pearce; Jinyeop Song



- **Deep Grokking: Would Deep Neural Networks Generalize Better?** [[paper link]](http://arxiv.org/abs/2405.19454) 2024-05-29  
Simin Fan; Razvan Pascanu; Martin Jaggi



- **Linguistic Collapse: Neural Collapse in (Large) Language Models** [[paper link]](https://arxiv.org/abs/2405.17767) 2024-05-28  
Robert Wu; Vardan Papyan



- **Scaling Laws and Compute-Optimal Training Beyond Fixed Training Durations** [[paper link]](http://arxiv.org/abs/2405.18392) 2024-05-28  
Alexander Hägele; Elie Bakouch; Atli Kosson; Loubna Ben Allal; Leandro Von Werra; Martin Jaggi



- **gzip Predicts Data-dependent Scaling Laws** [[paper link]](http://arxiv.org/abs/2405.16684) 2024-05-26  
Rohan Pandey



- **Emergence of a High-Dimensional Abstraction Phase in Language Transformers** [[paper link]](http://arxiv.org/abs/2405.15471) 2024-05-24  
Emily Cheng; Diego Doimo; Corentin Kervadec; Iuri Macocco; Jade Yu; Alessandro Laio; Marco Baroni



- **A rationale from frequency perspective for grokking in training neural network** [[paper link]](http://arxiv.org/abs/2405.17479) 2024-05-24  
Zhangchen Zhou; Yaoyu Zhang; Zhi-Qin John Xu



- **Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to the Edge of Generalization** [[paper link]](http://arxiv.org/abs/2405.15071) 2024-05-23  
Boshi Wang; Xiang Yue; Yu Su; Huan Sun



- **Data Mixing Made Efficient: A Bivariate Scaling Law for Language Model Pretraining** [[paper link]](http://arxiv.org/abs/2405.14908) 2024-05-23  
Ce Ge; Zhijian Ma; Daoyuan Chen; Yaliang Li; Bolin Ding



- **4+3 Phases of Compute-Optimal Neural Scaling Laws** [[paper link]](http://arxiv.org/abs/2405.15074) 2024-05-23  
Elliot Paquette; Courtney Paquette; Lechao Xiao; Jeffrey Pennington



- **Slaves to the Law of Large Numbers: An Asymptotic Equipartition Property for Perplexity in Generative Language Models** [[paper link]](http://arxiv.org/abs/2405.13798) 2024-05-22  
Raghu Mudumbai; Tyler Bell



- **Quantifying Emergence in Large Language Models** [[paper link]](http://arxiv.org/abs/2405.12617) 2024-05-21  
Hang Chen; Xinyu Yang; Jiaying Zhu; Wenya Wang



- **Beyond Scaling Laws: Understanding Transformer Performance with Associative Memory** [[paper link]](http://arxiv.org/abs/2405.08707) 2024-05-14  
Xueyan Niu; Bo Bai; Lei Deng; Wei Han



- **More Compute Is What You Need** [[paper link]](http://arxiv.org/abs/2404.19484) 2024-04-30  
Zhen Guo



- **An exactly solvable model for emergence and scaling laws** [[paper link]](http://arxiv.org/abs/2404.17563) 2024-04-26  
Yoonsoo Nam; Nayara Fonseca; Seok Hyeong Lee; Ard Louis



- **Why do small language models underperform? Studying Language Model Saturation via the Softmax Bottleneck** [[paper link]](http://arxiv.org/abs/2404.07647) 2024-04-11  
Nathan Godey; Éric de la Clergerie; Benoît Sagot



- **A Large-Scale Exploration of $\mu$-Transfer** [[paper link]](http://arxiv.org/abs/2404.05728) 2024-04-08  
Lucas Lingle



- **Emergent Abilities in Reduced-Scale Generative Language Models** [[paper link]](http://arxiv.org/abs/2404.02204) 2024-04-02  
Sherin Muckatira; Vijeta Deshpande; Vladislav Lialin; Anna Rumshisky



- **Understanding Emergent Abilities of Language Models from the Loss Perspective** [[paper link]](http://arxiv.org/abs/2403.15796) 2024-03-23  
Zhengxiao Du; Aohan Zeng; Yuxiao Dong; Jie Tang



- **Unraveling the Mystery of Scaling Laws: Part I** [[paper link]](http://arxiv.org/abs/2403.06563) 2024-03-21  
Hui Su; Zhi Tian; Xiaoyu Shen; Xunliang Cai



- **Language models scale reliably with over-training and on downstream tasks** [[paper link]](http://arxiv.org/abs/2403.08540) 2024-03-13  
Samir Yitzhak Gadre; Georgios Smyrnis; Vaishaal Shankar; Suchin Gururangan; Mitchell Wortsman; Rulin Shao; Jean Mercat; Alex Fang; Jeffrey Li; Sedrick Keh; Rui Xin; Marianna Nezhurina; Igor Vasiljevic; Jenia Jitsev; Alexandros G. Dimakis; Gabriel Ilharco; Shuran Song; Thomas Kollar; Yair Carmon; Achal Dave; Reinhard Heckel; Niklas Muennighoff; Ludwig Schmidt



- **When Scaling Meets LLM Finetuning: The Effect of Data, Model and Finetuning Method** [[paper link]](http://arxiv.org/abs/2402.17193) 2024-02-26  
Biao Zhang; Zhongtao Liu; Colin Cherry; Orhan Firat



- **Interpreting Grokked Transformers in Complex Modular Arithmetic** [[paper link]](https://arxiv.org/abs/2402.16726v2) 2024-02-26  
Hiroki Furuta; Gouki Minegishi; Yusuke Iwasawa; Yutaka Matsuo



- **A Tale of Tails: Model Collapse as a Change of Scaling Laws** [[paper link]](https://arxiv.org/abs/2402.07043) 2024-02-10  
Elvis Dohmatob; Yunzhen Feng; Pu Yang; Francois Charton; Julia Kempe



- **Scaling Data-Constrained Language Models** [[paper link]](http://arxiv.org/abs/2305.16264) 2023-10-25  
Niklas Muennighoff; Alexander M. Rush; Boaz Barak; Teven Le Scao; Aleksandra Piktus; Nouamane Tazi; Sampo Pyysalo; Thomas Wolf; Colin Raffel



- **The Cost of Down-Scaling Language Models: Fact Recall Deteriorates before In-Context Learning** [[paper link]](http://arxiv.org/abs/2310.04680) 2023-10-06  
Tian Jin; Nolan Clement; Xin Dong; Vaishnavh Nagarajan; Michael Carbin; Jonathan Ragan-Kelley; Gintare Karolina Dziugaite



- **Are Emergent Abilities of Large Language Models a Mirage?** [[paper link]](https://arxiv.org/abs/2304.15004v2) 2023-04-28  
Rylan Schaeffer; Brando Miranda; Sanmi Koyejo



- **Training Compute-Optimal Large Language Models** [[paper link]](http://arxiv.org/abs/2203.15556) 2022-03-29  
Jordan Hoffmann; Sebastian Borgeaud; Arthur Mensch; Elena Buchatskaya; Trevor Cai; Eliza Rutherford; Diego de Las Casas; Lisa Anne Hendricks; Johannes Welbl; Aidan Clark; Tom Hennigan; Eric Noland; Katie Millican; George van den Driessche; Bogdan Damoc; Aurelia Guy; Simon Osindero; Karen Simonyan; Erich Elsen; Jack W. Rae; Oriol Vinyals; Laurent Sifre



- **Scaling Laws for Neural Language Models** [[paper link]](http://arxiv.org/abs/2001.08361) 2020-01-22  
Jared Kaplan; Sam McCandlish; Tom Henighan; Tom B. Brown; Benjamin Chess; Rewon Child; Scott Gray; Alec Radford; Jeffrey Wu; Dario Amodei

</details>


### **Knowledge / Memory Mechanisms**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers focusing on how large language models store, retrieve, and utilize knowledge, analyzing the memory mechanisms involved.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **A Geometric Framework for Understanding Memorization in Generative Models** [[paper link]](http://arxiv.org/abs/2411.00113) 2024-10-31  
Brendan Leigh Ross; Hamidreza Kamkari; Tongzi Wu; Rasa Hosseinzadeh; Zhaoyan Liu; George Stein; Jesse C. Cresswell; Gabriel Loaiza-Ganem



- **Optimal Memorization Capacity of Transformers** [[paper link]](http://arxiv.org/abs/2409.17677) 2024-09-26  
Tokio Kajitsuka; Issei Sato



- **Schrodingers Memory: Large Language Models** [[paper link]](https://arxiv.org/pdf/2409.10482) 2024-09-16  
Wei Wang; Qing Li



- **Self-Attention Limits Working Memory Capacity of Transformer-Based Models** [[paper link]](http://arxiv.org/abs/2409.10715) 2024-09-16  
Dongyu Gong; Hantao Zhang



- **Great Memory, Shallow Reasoning: Limits of kNN-LMs** [[paper link]](http://arxiv.org/abs/2408.11815) 2024-08-21  
Shangyi Geng; Wenting Zhao; Alexander M Rush



- **Memorisation In In-Context Learning** [[paper link]](http://arxiv.org/abs/2408.11546) 2024-08-21  
Shahriar Golchin; Mihai Surdeanu; Steven Bethard; Eduardo Blanco; Ellen Riloff



- **Generalisation First, Memorisation Second? Memorisation Localisation for Natural Language Classification Tasks** [[paper link]](http://arxiv.org/abs/2408.04965) 2024-08-09  
Verna Dankers; Ivan Titov



- **Understanding Memorisation in LLMs: Dynamics, Influencing Factors, and Implications** [[paper link]](http://arxiv.org/abs/2407.19262) 2024-07-27  
Till Speicher; Mohammad Aflah Khan; Qinyuan Wu; Vedant Nanda; Soumi Das; Bishwamittra Ghosh; Krishna P. Gummadi; Evimaria Terzi



- **Demystifying Verbatim Memorization in Large Language Models** [[paper link]](http://arxiv.org/abs/2407.17817) 2024-07-25  
Jing Huang; Diyi Yang; Christopher Potts



- **From Internal Conflict to Contextual Adaptation of Language Models** [[paper link]](http://arxiv.org/abs/2407.17023) 2024-07-24  
Sara Vera Marjanović; Haeun Yu; Pepa Atanasova; Maria Maistro; Christina Lioma; Isabelle Augenstein



- **Generalization v.s. Memorization: Tracing Language Models' Capabilities Back to Pretraining Data** [[paper link]](http://arxiv.org/abs/2407.14985) 2024-07-20  
Antonis Antoniades; Xinyi Wang; Yanai Elazar; Alfonso Amayuelas; Alon Albalak; Kexun Zhang; William Yang Wang



- **Physics of Language Models: Part 3.1, Knowledge Storage and Extraction** [[paper link]](http://arxiv.org/abs/2309.14316) 2024-07-16  
Zeyuan Allen-Zhu; Yuanzhi Li



- **Induction Heads as an Essential Mechanism for Pattern Matching in In-context Learning** [[paper link]](http://arxiv.org/abs/2407.07011) 2024-07-09  
J. Crosbie; E. Shutova



- **Do LLMs dream of elephants (when told not to)? Latent concept association and associative memory in transformers** [[paper link]](http://arxiv.org/abs/2406.18400) 2024-06-26  
Yibo Jiang; Goutham Rajendran; Pradeep Ravikumar; Bryon Aragam



- **Scaling Laws for Fact Memorization of Large Language Models** [[paper link]](http://arxiv.org/abs/2406.15720) 2024-06-22  
Xingyu Lu; Xiaonan Li; Qinyuan Cheng; Kai Ding; Xuanjing Huang; Xipeng Qiu



- **Connecting the Dots: LLMs can Infer and Verbalize Latent Structure from Disparate Training Data** [[paper link]](http://arxiv.org/abs/2406.14546) 2024-06-20  
Johannes Treutlein; Dami Choi; Jan Betley; Cem Anil; Samuel Marks; Roger Baker Grosse; Owain Evans



- **Uncovering Latent Memories: Assessing Data Leakage and Memorization Patterns in Large Language Models** [[paper link]](http://arxiv.org/abs/2406.14549) 2024-06-20  
Sunny Duan; Mikail Khona; Abhiram Iyer; Rylan Schaeffer; Ila R Fiete



- **Understanding Finetuning for Factual Knowledge Extraction** [[paper link]](http://arxiv.org/abs/2406.14785) 2024-06-20  
Gaurav Ghosal; Tatsunori Hashimoto; Aditi Raghunathan



- **Estimating Knowledge in Large Language Models Without Generating a Single Token** [[paper link]](http://arxiv.org/abs/2406.12673) 2024-06-18  
Daniela Gottesman; Mor Geva



- **How Do Large Language Models Acquire Factual Knowledge During Pretraining?** [[paper link]](http://arxiv.org/abs/2406.11813) 2024-06-17  
Hoyeon Chang; Jinho Park; Seonghyeon Ye; Sohee Yang; Youngkyung Seo; Du-Seong Chang; Minjoon Seo



- **Be like a Goldfish, Don't Memorize! Mitigating Memorization in Generative LLMs** [[paper link]](http://arxiv.org/abs/2406.10209) 2024-06-14  
Abhimanyu Hans; Yuxin Wen; Neel Jain; John Kirchenbauer; Hamid Kazemi; Prajwal Singhania; Siddharth Singh; Gowthami Somepalli; Jonas Geiping; Abhinav Bhatele; Tom Goldstein



- **Knowledge Circuits in Pretrained Transformers** [[paper link]](http://arxiv.org/abs/2405.17969) 2024-05-28  
Yunzhi Yao; Ningyu Zhang; Zekun Xi; Mengru Wang; Ziwen Xu; Shumin Deng; Huajun Chen



- **Upper and lower memory capacity bounds of transformers for next-token prediction** [[paper link]](http://arxiv.org/abs/2405.13718) 2024-05-22  
Liam Madden; Curtis Fox; Christos Thrampoulidis



- **A Multi-Perspective Analysis of Memorization in Large Language Models** [[paper link]](http://arxiv.org/abs/2405.11577) 2024-05-19  
Bowen Chen; Namgi Han; Yusuke Miyao



- **Physics of Language Models: Part 3.3, Knowledge Capacity Scaling Laws** [[paper link]](http://arxiv.org/abs/2404.05405) 2024-04-08  
Zeyuan Allen-Zhu; Yuanzhi Li



- **Memorization Capacity of Multi-Head Attention in Transformers** [[paper link]](http://arxiv.org/abs/2306.02010) 2024-03-02  
Sadegh Mahdavi; Renjie Liao; Christos Thrampoulidis



- **Birth of a Transformer: A Memory Viewpoint** [[paper link]](http://arxiv.org/abs/2306.00802) 2023-11-06  
Alberto Bietti; Vivien Cabannes; Diane Bouchacourt; Herve Jegou; Leon Bottou



- **Physics of Language Models: Part 3.2, Knowledge Manipulation** [[paper link]](http://arxiv.org/abs/2309.14402) 2023-09-25  
Zeyuan Allen-Zhu; Yuanzhi Li



- **Can Neural Network Memorization Be Localized?** [[paper link]](http://arxiv.org/abs/2307.09542) 2023-07-18  
Pratyush Maini; Michael C. Mozer; Hanie Sedghi; Zachary C. Lipton; J. Zico Kolter; Chiyuan Zhang



- **Quantifying Memorization Across Neural Language Models** [[paper link]](http://arxiv.org/abs/2202.07646) 2022-02-15  
Nicholas Carlini; Daphne Ippolito; Matthew Jagielski; Katherine Lee; Florian Tramer; Chiyuan Zhang

</details>


### **Training Dynamics / Landscape / Optimization / Fine-tuning / etc.**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers discussing various aspects of the training process, including optimization, fine-tuning, and the training landscape of large language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Gradient dynamics for low-rank fine-tuning beyond kernels** [[paper link]](http://arxiv.org/abs/2411.15385) 2024-11-23  
Arif Kerem Dayi; Sitan Chen



- **Unraveling the Gradient Descent Dynamics of Transformers** [[paper link]](http://arxiv.org/abs/2411.07538) 2024-11-12  
Bingqing Song; Boran Han; Shuai Zhang; Jie Ding; Mingyi Hong



- **What Do Learning Dynamics Reveal About Generalization in LLM Reasoning?** [[paper link]](http://arxiv.org/abs/2411.07681) 2024-11-12  
Katie Kang; Amrith Setlur; Dibya Ghosh; Jacob Steinhardt; Claire Tomlin; Sergey Levine; Aviral Kumar



- **Training Dynamics of Transformers to Recognize Word Co-occurrence via Gradient Flow Analysis** [[paper link]](http://arxiv.org/abs/2410.09605) 2024-11-12  
Hongru Yang; Bhavya Kailkhura; Zhangyang Wang; Yingbin Liang



- **Global Convergence in Training Large-Scale Transformers** [[paper link]](http://arxiv.org/abs/2410.23610) 2024-10-31  
Cheng Gao; Yuan Cao; Zihao Li; Yihan He; Mengdi Wang; Han Liu; Jason Matthew Klusowski; Jianqing Fan



- **What Happened in LLMs Layers when Trained for Fast vs. Slow Thinking: A Gradient Perspective** [[paper link]](http://arxiv.org/abs/2410.23743) 2024-10-31  
Ming Li; Yanhong Li; Tianyi Zhou



- **Learning and Transferring Sparse Contextual Bigrams with Linear Transformers** [[paper link]](http://arxiv.org/abs/2410.23438) 2024-10-30  
Yunwei Ren; Zixuan Wang; Jason D. Lee



- **Abrupt Learning in Transformers: A Case Study on Matrix Completion** [[paper link]](http://arxiv.org/abs/2410.22244) 2024-10-29  
Pulkit Gopalani; Ekdeep Singh Lubana; Wei Hu



- **LoRA vs Full Fine-tuning: An Illusion of Equivalence** [[paper link]](http://arxiv.org/abs/2410.21228) 2024-10-28  
Reece Shuttleworth; Jacob Andreas; Antonio Torralba; Pratyusha Sharma



- **A distributional simplicity bias in the learning dynamics of transformers** [[paper link]](http://arxiv.org/abs/2410.19637) 2024-10-25  
Riccardo Rende; Federica Gerace; Alessandro Laio; Sebastian Goldt



- **Active-Dormant Attention Heads: Mechanistically Demystifying Extreme-Token Phenomena in LLMs** [[paper link]](http://arxiv.org/abs/2410.13835) 2024-10-17  
Tianyu Guo; Druv Pai; Yu Bai; Jiantao Jiao; Michael I. Jordan; Song Mei



- **How Transformers Implement Induction Heads: Approximation and Optimization Analysis** [[paper link]](http://arxiv.org/abs/2410.11474) 2024-10-15  
Mingze Wang; Ruoxi Yu; Weinan E; Lei Wu



- **What Does It Mean to Be a Transformer? Insights from a Theoretical Hessian Analysis** [[paper link]](http://arxiv.org/abs/2410.10986) 2024-10-14  
Weronika Ormaniec; Felix Dangel; Sidak Pal Singh



- **Adaptation Odyssey in LLMs: Why Does Additional Pretraining Sometimes Fail to Improve?** [[paper link]](http://arxiv.org/abs/2410.05581) 2024-10-08  
Fırat Öncel; Matthias Bethge; Beyza Ermis; Mirco Ravanelli; Cem Subakan; Çağatay Yıldız



- **On the Optimization and Generalization of Two-layer Transformers with Sign Gradient Descent** [[paper link]](http://arxiv.org/abs/2410.04870) 2024-10-07  
Bingrui Li; Wei Huang; Andi Han; Zhanpeng Zhou; Taiji Suzuki; Jun Zhu; Jianfei Chen



- **Understanding Warmup-Stable-Decay Learning Rates: A River Valley Loss Landscape Perspective** [[paper link]](http://arxiv.org/abs/2410.05192) 2024-10-07  
Kaiyue Wen; Zhiyuan Li; Jason Wang; David Hall; Percy Liang; Tengyu Ma



- **Training Nonlinear Transformers for Chain-of-Thought Inference: A Theoretical Generalization Analysis** [[paper link]](http://arxiv.org/abs/2410.02167) 2024-10-03  
Hongkang Li; Meng Wang; Songtao Lu; Xiaodong Cui; Pin-Yu Chen



- **Theoretical Insights into Fine-Tuning Attention Mechanism: Generalization and Optimization** [[paper link]](http://arxiv.org/abs/2410.02247) 2024-10-03  
Xinhao Yao; Hongjin Qian; Xiaolin Hu; Gengze Xu; Yong Liu



- **Trained Transformer Classifiers Generalize and Exhibit Benign Overfitting In-Context** [[paper link]](http://arxiv.org/abs/2410.01774) 2024-10-02  
Spencer Frei; Gal Vardi



- **Towards a Theoretical Understanding of Synthetic Data in LLM Post-Training: A Reverse-Bottleneck Perspective** [[paper link]](http://arxiv.org/abs/2410.01720) 2024-10-02  
Zeyu Gan; Yong Liu



- **Investigating the Impact of Model Complexity in Large Language Models** [[paper link]](http://arxiv.org/abs/2410.00699) 2024-10-01  
Jing Luo; Huiyuan Wang; Weiran Huang



- **Benigh or Not-Benign Overfitting in Token Selection of Attention Mechanism** [[paper link]](http://arxiv.org/abs/2409.17625) 2024-09-26  
Keitaro Sakamoto; Issei Sato



- **Non-asymptotic Convergence of Training Transformers for Next-token Prediction** [[paper link]](http://arxiv.org/abs/2409.17335) 2024-09-25  
Ruiquan Huang; Yingbin Liang; Jing Yang



- **Optimization Hyper-parameter Laws for Large Language Models** [[paper link]](http://arxiv.org/abs/2409.04777) 2024-09-07  
Xingyu Xie; Kuangyu Ding; Shuicheng Yan; Kim-Chuan Toh; Tianwen Wei



- **The AdEMAMix Optimizer: Better, Faster, Older** [[paper link]](http://arxiv.org/abs/2409.03137) 2024-09-05  
Matteo Pagliardini; Pierre Ablin; David Grangier



- **Clustering and Alignment: Understanding the Training Dynamics in Modular Addition** [[paper link]](http://arxiv.org/abs/2408.09414) 2024-08-18  
Tiberiu Musat



- **Global Convergence in Training Large-Scale Transformers** [[paper link]](https://klusowski.princeton.edu/sites/g/files/toruqf5901/files/documents/gao2024global.pdf) 2024-08  
Cheng Gao; Yuan Cao; Zihao Li; Yihan He; Mengdi Wang; Han Liu; Jason M. Klusowski; Jianqing Fan



- **On the Convergence of Encoder-only Shallow Transformers** [[paper link]](https://proceedings.neurips.cc/paper_files/paper/2023/file/a3cf318fbeec1126da21e9185ae9908c-Paper-Conference.pdf) 2024-08  
Yongtao Wu; Fanghui Liu; Grigorios G Chrysos; Volkan Cevher



- **Parameter-Efficient Fine-Tuning for Continual Learning: A Neural Tangent Kernel Perspective** [[paper link]](http://arxiv.org/abs/2407.17120) 2024-07-24  
Jingren Liu; Zhong Ji; YunLong Yu; Jiale Cao; Yanwei Pang; Jungong Han; Xuelong Li



- **Learning Dynamics of LLM Finetuning** [[paper link]](http://arxiv.org/abs/2407.10490) 2024-07-15  
Yi Ren; Danica J. Sutherland



- **Deconstructing What Makes a Good Optimizer for Language Models** [[paper link]](http://arxiv.org/abs/2407.07972) 2024-07-10  
Rosie Zhao; Depen Morwani; David Brandfonbrener; Nikhil Vyas; Sham Kakade



- **Zero-Shot Generalization during Instruction Tuning: Insights from Similarity and Granularity** [[paper link]](http://arxiv.org/abs/2406.11721) 2024-06-17  
Bingxiang He; Ning Ding; Cheng Qian; Jia Deng; Ganqu Cui; Lifan Yuan; Huan-ang Gao; Huimin Chen; Zhiyuan Liu; Maosong Sun



- **Understanding Linear Probing then Fine-tuning Language Models from NTK Perspective** [[paper link]](http://arxiv.org/abs/2405.16747) 2024-05-27  
Akiyoshi Tomihari; Issei Sato



- **Infinite Limits of Multi-head Transformer Dynamics** [[paper link]](http://arxiv.org/abs/2405.15712) 2024-05-24  
Blake Bordelon; Hamza Tahir Chaudhry; Cengiz Pehlevan



- **Towards a Theoretical Understanding of the 'Reversal Curse' via Training Dynamics** [[paper link]](http://arxiv.org/abs/2405.04669) 2024-05-07  
Hanlin Zhu; Baihe Huang; Shaolun Zhang; Michael Jordan; Jiantao Jiao; Yuandong Tian; Stuart Russell



- **Control Theoretic Approach to Fine-Tuning and Transfer Learning** [[paper link]](http://arxiv.org/abs/2404.11013) 2024-04-16  
Erkan Bayram; Shenyu Liu; Mohamed-Ali Belabbas; Tamer Başar



- **Look at the Text: Instruction-Tuned Language Models are More Robust Multiple Choice Selectors than You Think** [[paper link]](http://arxiv.org/abs/2404.08382) 2024-04-12  
Xinpeng Wang; Chengzhi Hu; Bolei Ma; Paul Röttger; Barbara Plank



- **On Training Data Influence of GPT Models** [[paper link]](http://arxiv.org/abs/2404.07840) 2024-04-11  
Qingyi Liu; Yekun Chai; Shuohuan Wang; Yu Sun; Keze Wang; Hua Wu



- **Best Practices and Lessons Learned on Synthetic Data for Language Models** [[paper link]](http://arxiv.org/abs/2404.07503) 2024-04-11  
Ruibo Liu; Jerry Wei; Fangyu Liu; Chenglei Si; Yanzhe Zhang; Jinmeng Rao; Steven Zheng; Daiyi Peng; Diyi Yang; Denny Zhou; Andrew M. Dai



- **How Bad is Training on Synthetic Data? A Statistical Analysis of Language Model Collapse** [[paper link]](http://arxiv.org/abs/2404.05090) 2024-04-07  
Mohamed El Amine Seddik; Suei-Wen Chen; Soufiane Hayou; Pierre Youssef; Merouane Debbah



- **Unveiling the Generalization Power of Fine-Tuned Large Language Models** [[paper link]](http://arxiv.org/abs/2403.09162) 2024-03-14  
Haoran Yang; Yumeng Zhang; Jiaqi Xu; Hongyuan Lu; Pheng Ann Heng; Wai Lam



- **Transformers Get Stable: An End-to-End Signal Propagation Theory for Language Models** [[paper link]](http://arxiv.org/abs/2403.09635) 2024-03-14  
Akhil Kedia; Mohd Abbas Zaidi; Sushil Khyalia; Jungho Jung; Harshith Goka; Haejun Lee



- **Linear Attention is (Maybe) All You Need (to Understand Transformer Optimization)** [[paper link]](http://arxiv.org/abs/2310.01082) 2024-03-13  
Kwangjun Ahn; Xiang Cheng; Minhak Song; Chulhee Yun; Ali Jadbabaie; Suvrit Sra



- **Hallmarks of Optimization Trajectories in Neural Networks and LLMs: The Lengths, Bends, and Dead Ends** [[paper link]](http://arxiv.org/abs/2403.07379) 2024-03-12  
Sidak Pal Singh; Bobby He; Thomas Hofmann; Bernhard Schölkopf



- **The Heuristic Core: Understanding Subnetwork Generalization in Pretrained Language Models** [[paper link]](http://arxiv.org/abs/2403.03942) 2024-03-06  
Adithya Bhaskar; Dan Friedman; Danqi Chen



- **Training Dynamics of Multi-Head Softmax Attention for In-Context Learning: Emergence, Convergence, and Optimality** [[paper link]](http://arxiv.org/abs/2402.19442) 2024-02-29  
Siyu Chen; Heejune Sheen; Tianhao Wang; Zhuoran Yang



- **How Transformers Learn Causal Structure with Gradient Descent** [[paper link]](http://arxiv.org/abs/2402.14735) 2024-02-22  
Eshaan Nichani; Alex Damian; Jason D. Lee



- **LoRA Training in the NTK Regime has No Spurious Local Minima** [[paper link]](http://arxiv.org/abs/2402.11867) 2024-02-19  
Uijeong Jang; Jason D. Lee; Ernest K. Ryu



- **On the Emergence of Cross-Task Linearity in the Pretraining-Finetuning Paradigm** [[paper link]](http://arxiv.org/abs/2402.03660) 2024-02-06  
Zhanpeng Zhou; Zijun Chen; Yilan Chen; Bo Zhang; Junchi Yan



- **Transformers learn through gradual rank increase** [[paper link]](http://arxiv.org/abs/2306.07042) 2023-12-10  
Enric Boix-Adsera; Etai Littwin; Emmanuel Abbe; Samy Bengio; Joshua Susskind



- **Mechanistically analyzing the effects of fine-tuning on procedurally defined tasks** [[paper link]](http://arxiv.org/abs/2311.12786) 2023-11-21  
Samyak Jain; Robert Kirk; Ekdeep Singh Lubana; Robert P. Dick; Hidenori Tanaka; Edward Grefenstette; Tim Rocktäschel; David Scott Krueger



- **Connecting Pre-trained Language Model and Downstream Task via Properties of Representation** [[paper link]](https://openreview.net/forum?id=YLOJ4aKAka) 2023-11-02  
Chenwei Wu; Holden Lee; Rong Ge



- **Scan and Snap: Understanding Training Dynamics and Token Composition in 1-layer Transformer** [[paper link]](http://arxiv.org/abs/2305.16380) 2023-07-02  
Yuandong Tian; Yiping Wang; Beidi Chen; Simon Du



- **A Kernel-Based View of Language Model Fine-Tuning** [[paper link]](https://openreview.net/forum?id=49dTFIGdx8) 2023-06-15  
Sadhika Malladi; Alexander Wettig; Dingli Yu; Danqi Chen; Sanjeev Arora



- **A Stability Analysis of Fine-Tuning a Pre-Trained Model** [[paper link]](https://arxiv.org/abs/2301.09820v2) 2023-01-24  
Zihao Fu; Anthony Man-Cho So; Nigel Collier

</details>


### **Learning / Generalization / Reasoning / Weak to Strong Generalization**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers analyzing the learning capabilities and generalization performance of language models, from weak to strong generalization.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **An In-depth Investigation of Sparse Rate Reduction in Transformer-like Models** [[paper link]](http://arxiv.org/abs/2411.17182) 2024-11-26  
Yunzhe Hu; Difan Zou; Dong Xu



- **What Do Learning Dynamics Reveal About Generalization in LLM Reasoning?** [[paper link]](http://arxiv.org/abs/2411.07681) 2024-11-12  
Katie Kang; Amrith Setlur; Dibya Ghosh; Jacob Steinhardt; Claire Tomlin; Sergey Levine; Aviral Kumar



- **Generalization and Risk Bounds for Recurrent Neural Networks** [[paper link]](http://arxiv.org/abs/2411.02784) 2024-11-05  
Xuewei Cheng; Ke Huang; Shujie Ma



- **Provable Length Generalization in Sequence Prediction via Spectral Filtering** [[paper link]](http://arxiv.org/abs/2411.01035) 2024-11-01  
Annie Marsden; Evan Dogariu; Naman Agarwal; Xinyi Chen; Daniel Suo; Elad Hazan



- **RL-STaR: Theoretical Analysis of Reinforcement Learning Frameworks for Self-Taught Reasoner** [[paper link]](http://arxiv.org/abs/2410.23912) 2024-10-31  
Fu-Chieh Chang; Yu-Ting Lee; Hui-Ying Shih; Pei-Yuan Wu



- **Mixture of Parrots: Experts improve memorization more than reasoning** [[paper link]](http://arxiv.org/abs/2410.19034) 2024-10-24  
Samy Jelassi; Clara Mohri; David Brandfonbrener; Alex Gu; Nikhil Vyas; Nikhil Anand; David Alvarez-Melis; Yuanzhi Li; Sham M. Kakade; Eran Malach



- **How Numerical Precision Affects Mathematical Reasoning Capabilities of LLMs** [[paper link]](http://arxiv.org/abs/2410.13857) 2024-10-17  
Guhao Feng; Kai Yang; Yuntian Gu; Xinyue Ai; Shengjie Luo; Jiacheng Sun; Di He; Zhenguo Li; Liwei Wang



- **On Rank-Dependent Generalisation Error Bounds for Transformers** [[paper link]](http://arxiv.org/abs/2410.11500) 2024-10-15  
Lan V. Truong



- **Benign Overfitting in Single-Head Attention** [[paper link]](http://arxiv.org/abs/2410.07746) 2024-10-10  
Roey Magen; Shuning Shang; Zhiwei Xu; Spencer Frei; Wei Hu; Gal Vardi



- **Dynamics of Concept Learning and Compositional Generalization** [[paper link]](http://arxiv.org/abs/2410.08309) 2024-10-10  
Yongyi Yang; Core Francisco Park; Ekdeep Singh Lubana; Maya Okawa; Wei Hu; Hidenori Tanaka



- **Benign Overfitting for Regression with Trained Two-Layer ReLU Networks** [[paper link]](http://arxiv.org/abs/2410.06191) 2024-10-08  
Junhyung Park; Patrick Bloebaum; Shiva Prasad Kasiviswanathan



- **Provable Weak-to-Strong Generalization via Benign Overfitting** [[paper link]](http://arxiv.org/abs/2410.04638) 2024-10-06  
David X. Wu; Anant Sahai



- **A Formal Framework for Understanding Length Generalization in Transformers** [[paper link]](http://arxiv.org/abs/2410.02140) 2024-10-03  
Xinting Huang; Andy Yang; Satwik Bhattamishra; Yash Sarrof; Andreas Krebs; Hattie Zhou; Preetum Nakkiran; Michael Hahn



- **Trained Transformer Classifiers Generalize and Exhibit Benign Overfitting In-Context** [[paper link]](http://arxiv.org/abs/2410.01774) 2024-10-02  
Spencer Frei; Gal Vardi



- **Lines of Thought in Large Language Models** [[paper link]](http://arxiv.org/abs/2410.01545) 2024-10-02  
Raphaël Sarfati; Toni J. B. Liu; Nicolas Boullé; Christopher J. Earls



- **Investigating the Impact of Model Complexity in Large Language Models** [[paper link]](http://arxiv.org/abs/2410.00699) 2024-10-01  
Jing Luo; Huiyuan Wang; Weiran Huang



- **Benign or Not-Benign Overfitting in Token Selection of Attention Mechanism** [[paper link]](http://arxiv.org/abs/2409.17625) 2024-09-26  
Keitaro Sakamoto; Issei Sato



- **Understanding Simplicity Bias towards Compositional Mappings via Learning Dynamics** [[paper link]](http://arxiv.org/abs/2409.09626) 2024-09-15  
Yi Ren; Danica J. Sutherland



- **Unforgettable Generalization in Language Models** [[paper link]](http://arxiv.org/abs/2409.02228) 2024-09-03  
Eric Zhang; Leshem Chosen; Jacob Andreas



- **The Many Faces of Optimal Weak-to-Strong Learning** [[paper link]](http://arxiv.org/abs/2408.17148) 2024-08-30  
Mikael Møller Høgsgaard; Kasper Green Larsen; Markus Engelund Mathiasen



- **Physics of Language Models: Part 2.2, How to Learn From Mistakes on Grade-School Math Problems** [[paper link]](http://arxiv.org/abs/2408.16293) 2024-08-29  
Tian Ye; Zicheng Xu; Yuanzhi Li; Zeyuan Allen-Zhu



- **Out-of-distribution generalization via composition: a lens through induction heads in Transformers** [[paper link]](http://arxiv.org/abs/2408.09503) 2024-08-18  
Jiajun Song; Zhuoyan Xu; Yiqiao Zhong



- **On the Generalization of Preference Learning with DPO** [[paper link]](http://arxiv.org/abs/2408.03459) 2024-08-06  
Shawn Im; Yixuan Li



- **Inductive or Deductive? Rethinking the Fundamental Reasoning Abilities of LLMs** [[paper link]](http://arxiv.org/abs/2408.00114) 2024-07-31  
Kewei Cheng; Jingfeng Yang; Haoming Jiang; Zhengyang Wang; Binxuan Huang; Ruirui Li; Shiyang Li; Zheng Li; Yifan Gao; Xian Li; Bing Yin; Yizhou Sun



- **Physics of Language Models: Part 2.1, Grade-School Math and the Hidden Reasoning Process** [[paper link]](http://arxiv.org/abs/2407.13123) 2024-07-29  
Tian Ye; Zicheng Xu; Yuanzhi Li; Zeyuan Allen-Zhu



- **Unlocking Tokens as Data Points for Generalization Bounds on Larger Language Models** [[paper link]](http://arxiv.org/abs/2407.18158) 2024-07-25  
Sanae Lotfi; Yilun Kuang; Brandon Amos; Micah Goldblum; Marc Finzi; Andrew Gordon Wilson



- **On Initialization of Transformers with Pre-trained Embeddings** [[paper link]](http://arxiv.org/abs/2407.12514) 2024-07-17  
Ha Young Kim; Niranjan Balasubramanian; Byungkon Kang



- **When can transformers compositionally generalize in-context?** [[paper link]](http://arxiv.org/abs/2407.12275) 2024-07-17  
Seijin Kobayashi; Simon Schug; Yassir Akram; Florian Redhardt; Johannes von Oswald; Razvan Pascanu; Guillaume Lajoie; João Sacramento



- **Reasoning in Large Language Models: A Geometric Perspective** [[paper link]](http://arxiv.org/abs/2407.02678) 2024-07-02  
Romain Cosentino; Sarath Shekkizhar



- **Learning on Transformers is Provable Low-Rank and Sparse: A One-layer Analysis** [[paper link]](http://arxiv.org/abs/2406.17167) 2024-06-24  
Hongkang Li; Meng Wang; Shuai Zhang; Sijia Liu; Pin-Yu Chen



- **How Truncating Weights Improves Reasoning in Language Models** [[paper link]](http://arxiv.org/abs/2406.03068) 2024-06-05  
Lei Chen; Joan Bruna; Alberto Bietti



- **Understanding Transformer Reasoning Capabilities via Graph Algorithms** [[paper link]](http://arxiv.org/abs/2405.18512) 2024-05-28  
Clayton Sanford; Bahare Fatemi; Ethan Hall; Anton Tsitsulin; Mehran Kazemi; Jonathan Halcrow; Bryan Perozzi; Vahab Mirrokni



- **Linguistic Collapse: Neural Collapse in (Large) Language Models** [[paper link]](https://arxiv.org/abs/2405.17767) 2024-05-28  
Robert Wu; Vardan Papyan



- **Reality Only Happens Once: Single-Path Generalization Bounds for Transformers** [[paper link]](http://arxiv.org/abs/2405.16563) 2024-05-26  
Yannick Limmer; Anastasis Kratsios; Xuwei Yang; Raeid Saqur; Blanka Horvath



- **A statistical framework for weak-to-strong generalization** [[paper link]](http://arxiv.org/abs/2405.16236) 2024-05-25  
Seamus Somerstep; Felipe Maia Polo; Moulinath Banerjee; Ya'acov Ritov; Mikhail Yurochkin; Yuekai Sun



- **Theoretical Analysis of Weak-to-Strong Generalization** [[paper link]](http://arxiv.org/abs/2405.16043) 2024-05-25  
Hunter Lang; David Sontag; Aravindan Vijayaraghavan



- **Quantifying the Gain in Weak-to-Strong Generalization** [[paper link]](http://arxiv.org/abs/2405.15116) 2024-05-24  
Moses Charikar; Chirag Pabbaraju; Kirankumar Shiragur



- **Towards Understanding How Transformer Perform Multi-step Reasoning with Matching Operation** [[paper link]](http://arxiv.org/abs/2405.15302) 2024-05-24  
Zhiwei Wang; Yunji Wang; Zhongwang Zhang; Zhangchen Zhou; Hui Jin; Tianyang Hu; Jiacheng Sun; Zhenguo Li; Yaoyu Zhang; Zhi-Qin John Xu



- **Initialization is Critical to Whether Transformers Fit Composite Functions by Inference or Memorizing** [[paper link]](http://arxiv.org/abs/2405.05409) 2024-05-08  
Zhongwang Zhang; Pengxiao Lin; Zhiwei Wang; Yaoyu Zhang; Zhi-Qin John Xu



- **On the Empirical Complexity of Reasoning and Planning in LLMs** [[paper link]](http://arxiv.org/abs/2404.11041) 2024-04-17  
Liwei Kang; Zirui Zhao; David Hsu; Wee Sun Lee



- **When can transformers reason with abstract symbols?** [[paper link]](http://arxiv.org/abs/2310.09753) 2024-04-16  
Enric Boix-Adsera; Omid Saremi; Emmanuel Abbe; Samy Bengio; Etai Littwin; Joshua Susskind



- **A Mechanistic Analysis of a Transformer Trained on a Symbolic Multi-Step Reasoning Task** [[paper link]](http://arxiv.org/abs/2402.11917) 2024-02-19  
Jannik Brinkmann; Abhay Sheshadri; Victor Levoso; Paul Swoboda; Christian Bartelt



- **Provably learning a multi-head attention layer** [[paper link]](http://arxiv.org/abs/2402.04084) 2024-02-06  
Sitan Chen; Yuanzhi Li



- **Mechanistically analyzing the effects of fine-tuning on procedurally defined tasks** [[paper link]](http://arxiv.org/abs/2311.12786) 2023-11-21  
Samyak Jain; Robert Kirk; Ekdeep Singh Lubana; Robert P. Dick; Hidenori Tanaka; Edward Grefenstette; Tim Rocktäschel; David Scott Krueger



- **The Impact of Depth and Width on Transformer Language Model Generalization** [[paper link]](http://arxiv.org/abs/2310.19956) 2023-10-30  
Jackson Petty; Sjoerd van Steenkiste; Ishita Dasgupta; Fei Sha; Dan Garrette; Tal Linzen



- **Implicit meta-learning may lead language models to trust more reliable sources** [[paper link]](http://arxiv.org/abs/2310.15047) 2023-10-23  
Dmitrii Krasheninnikov; Egor Krasheninnikov; Bruno Mlodozeniec; Tegan Maharaj; David Krueger



- **On the Optimization and Generalization of Multi-head Attention** [[paper link]](http://arxiv.org/abs/2310.12680) 2023-10-19  
Puneesh Deora; Rouzbeh Ghaderi; Hossein Taheri; Christos Thrampoulidis



- **Large Language Models Cannot Self-Correct Reasoning Yet** [[paper link]](https://openreview.net/forum?id=IkmD3fKBPQ) 2023-10-13  
Jie Huang; Xinyun Chen; Swaroop Mishra; Huaixiu Steven Zheng; Adams Wei Yu; Xinying Song; Denny Zhou



- **How Abilities in Large Language Models are Affected by Supervised Fine-tuning Data Composition** [[paper link]](http://arxiv.org/abs/2310.05492) 2023-10-09  
Guanting Dong; Hongyi Yuan; Keming Lu; Chengpeng Li; Mingfeng Xue; Dayiheng Liu; Wei Wang; Zheng Yuan; Chang Zhou; Jingren Zhou



- **A Theory for Emergence of Complex Skills in Language Models** [[paper link]](http://arxiv.org/abs/2307.15936) 2023-07-29  
Sanjeev Arora; Anirudh Goyal



- **On the Power of Foundation Models** [[paper link]](https://proceedings.mlr.press/v202/yuan23b.html) 2023-07-03  
Yang Yuan



- **Task-Specific Skill Localization in Fine-tuned Language Models** [[paper link]](https://openreview.net/forum?id=Rgnaj43Pk0) 2023-06-15  
Abhishek Panigrahi; Nikunj Saunshi; Haoyu Zhao; Sanjeev Arora



- **Towards Understanding Why Mask-Reconstruction Pretraining Helps in Downstream Tasks** [[paper link]](http://arxiv.org/abs/2206.03826) 2023-02-11  
Jiachun Pan; Pan Zhou; Shuicheng Yan



- **Same Pre-training Loss, Better Downstream: Implicit Bias Matters for Language Models** [[paper link]](http://arxiv.org/abs/2210.14199) 2022-10-25  
Hong Liu; Sang Michael Xie; Zhiyuan Li; Tengyu Ma



- **Why Do Pretrained Language Models Help in Downstream Tasks? An Analysis of Head and Prompt Tuning** [[paper link]](http://arxiv.org/abs/2106.09226) 2022-04-20  
Colin Wei; Sang Michael Xie; Tengyu Ma



- **A Mathematical Exploration of Why Language Models Help Solve Downstream Tasks** [[paper link]](http://arxiv.org/abs/2010.03648) 2021-04-14  
Nikunj Saunshi; Sadhika Malladi; Sanjeev Arora



- **Intrinsic Dimensionality Explains the Effectiveness of Language Model Fine-Tuning** [[paper link]](http://arxiv.org/abs/2012.13255) 2020-12-22  
Armen Aghajanyan; Luke Zettlemoyer; Sonal Gupta



- **How fine can fine-tuning be? Learning efficient language models** [[paper link]](https://proceedings.mlr.press/v108/radiya-dixit20a.html) 2020-06-03  
Evani Radiya-Dixit; Xin Wang

</details>


### **Other Phenomena / Discoveries**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers discussing other interesting phenomena or discoveries related to the behavior and properties of language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **On the loss of context-awareness in general instruction fine-tuning** [[paper link]](http://arxiv.org/abs/2411.02688) 2024-11-05  
Yihan Wang; Andrew Bai; Nanyun Peng; Cho-Jui Hsieh



- **Weight decay induces low-rank attention layers** [[paper link]](http://arxiv.org/abs/2410.23819) 2024-10-31  
Seijin Kobayashi; Yassir Akram; Johannes Von Oswald



- **All or None: Identifiable Linear Properties of Next-token Predictors in Language Modeling** [[paper link]](http://arxiv.org/abs/2410.23501) 2024-10-30  
Emanuele Marconato; Sébastien Lachapelle; Sebastian Weichwald; Luigi Gresele



- **Looking Beyond The Top-1: Transformers Determine Top Tokens In Order** [[paper link]](http://arxiv.org/abs/2410.20210) 2024-10-26  
Daria Lioubashevski; Tomer Schlank; Gabriel Stanovsky; Ariel Goldstein



- **Active-Dormant Attention Heads: Mechanistically Demystifying Extreme-Token Phenomena in LLMs** [[paper link]](http://arxiv.org/abs/2410.13835) 2024-10-17  
Tianyu Guo; Druv Pai; Yu Bai; Jiantao Jiao; Michael I. Jordan; Song Mei



- **Emergent properties with repeated examples** [[paper link]](http://arxiv.org/abs/2410.07041) 2024-10-09  
François Charton; Julia Kempe



- **Masked Mixers for Language Generation and Retrieval** [[paper link]](http://arxiv.org/abs/2409.01482) 2024-09-02  
Benjamin L. Badger



- **Monotonic Representation of Numeric Properties in Language Models** [[paper link]](http://arxiv.org/abs/2408.10381) 2024-08-15  
Benjamin Heinzerling; Kentaro Inui



- **Does Liking Yellow Imply Driving a School Bus? Semantic Leakage in Language Models** [[paper link]](http://arxiv.org/abs/2408.06518) 2024-08-12  
Hila Gonen; Terra Blevins; Alisa Liu; Luke Zettlemoyer; Noah A. Smith



- **Large Language Monkeys: Scaling Inference Compute with Repeated Sampling** [[paper link]](http://arxiv.org/abs/2407.21787) 2024-07-31  
Bradley Brown; Jordan Juravsky; Ryan Ehrlich; Ronald Clark; Quoc V. Le; Christopher Ré; Azalia Mirhoseini



- **Transformers on Markov Data: Constant Depth Suffices** [[paper link]](http://arxiv.org/abs/2407.17686) 2024-07-25  
Nived Rajaraman; Marco Bondaschi; Kannan Ramchandran; Michael Gastpar; Ashok Vardhan Makkuva



- **On the Benefits of Rank in Attention Layers** [[paper link]](http://arxiv.org/abs/2407.16153) 2024-07-23  
Noah Amsel; Gilad Yehudai; Joan Bruna



- **Transformer Alignment in Large Language Models** [[paper link]](http://arxiv.org/abs/2407.07810) 2024-07-10  
Murdock Aubry; Haoming Meng; Anton Sugolov; Vardan Papyan



- **Understanding Transformers via N-gram Statistics** [[paper link]](http://arxiv.org/abs/2407.12034) 2024-06-30  
Timothy Nguyen



- **Large Vocabulary Size Improves Large Language Models** [[paper link]](http://arxiv.org/abs/2406.16508) 2024-06-24  
Sho Takase; Ryokan Ri; Shun Kiyono; Takuya Kato



- **Connecting the Dots: LLMs can Infer and Verbalize Latent Structure from Disparate Training Data** [[paper link]](http://arxiv.org/abs/2406.14546) 2024-06-20  
Johannes Treutlein; Dami Choi; Jan Betley; Cem Anil; Samuel Marks; Roger Baker Grosse; Owain Evans



- **Distributional reasoning in LLMs: Parallel reasoning processes in multi-hop reasoning** [[paper link]](http://arxiv.org/abs/2406.13858) 2024-06-19  
Yuval Shalev; Amir Feder; Ariel Goldstein



- **Transcendence: Generative Models Can Outperform The Experts That Train Them** [[paper link]](http://arxiv.org/abs/2406.11741) 2024-06-17  
Edwin Zhang; Vincent Zhu; Naomi Saphra; Anat Kleiman; Benjamin L. Edelman; Milind Tambe; Sham M. Kakade; Eran Malach



- **Taking a Deep Breath: Enhancing Language Modeling of Large Language Models with Sentinel Tokens** [[paper link]](http://arxiv.org/abs/2406.10985) 2024-06-16  
Weiyao Luo; Suncong Zheng; Heming Xia; Weikang Wang; Yan Lei; Tianyu Liu; Shuang Chen; Zhifang Sui



- **Anisotropy is Not Inherent to Transformers** [[paper link]](https://aclanthology.org/2024.naacl-long.274) 2024-06  
Anemily Machina; Robert Mercer



- **Linguistic Collapse: Neural Collapse in (Large) Language Models** [[paper link]](https://arxiv.org/abs/2405.17767) 2024-05-28  
Robert Wu; Vardan Papyan



- **Exploring Activation Patterns of Parameters in Language Models** [[paper link]](https://arxiv.org/abs/2405.17799) 2024-05-28  
Yudong Wang; Damai Dai; Zhifang Sui



- **Implicit Multimodal Alignment: On the Generalization of Frozen LLMs to Multimodal Inputs** [[paper link]](https://arxiv.org/abs/2405.16700) 2024-05-26  
Mustafa Shukor; Matthieu Cord



- **Your Transformer is Secretly Linear** [[paper link]](https://arxiv.org/abs/2405.12250) 2024-05-19  
Anton Razzhigaev; Matvey Mikhalchuk; Elizaveta Goncharova; Nikolai Gerasimenko; Ivan Oseledets; Denis Dimitrov; Andrey Kuznetsov



- **The Platonic Representation Hypothesis** [[paper link]](https://arxiv.org/abs/2405.07987v1) 2024-05-13  
Minyoung Huh; Brian Cheung; Tongzhou Wang; Phillip Isola



- **By Tying Embeddings You Are Assuming the Distributional Hypothesis** [[paper link]](https://openreview.net/pdf?id=yyYMAprcAR) 2024-05-02  
Francesco Bertolotti; Walter Cazzola



- **Emergent Representations of Program Semantics in Language Models Trained on Programs** [[paper link]](https://openreview.net/pdf?id=8PTx4CpNoT) 2024-05-02  
Charles Jin; Martin Rinard



- **Algorithmic progress in language models** [[paper link]](http://arxiv.org/abs/2403.05812) 2024-03-09  
Anson Ho; Tamay Besiroglu; Ege Erdil; David Owen; Robi Rahman; Zifan Carl Guo; David Atkinson; Neil Thompson; Jaime Sevilla



- **Massive Activations in Large Language Models** [[paper link]](http://arxiv.org/abs/2402.17762) 2024-02-27  
Mingjie Sun; Xinlei Chen; J. Zico Kolter; Zhuang Liu



- **On the Emergence of Cross-Task Linearity in the Pretraining-Finetuning Paradigm** [[paper link]](http://arxiv.org/abs/2402.03660) 2024-02-06  
Zhanpeng Zhou; Zijun Chen; Yilan Chen; Bo Zhang; Junchi Yan



- **Anisotropy Is Inherent to Self-Attention in Transformers** [[paper link]](http://arxiv.org/abs/2406.12143) 2024-01-24  
Nathan Godey; Éric de la Clergerie; Benoît Sagot



- **The Lazy Neuron Phenomenon: On Emergence of Activation Sparsity in Transformers** [[paper link]](https://openreview.net/forum?id=TJ2nxciYCk-) 2023-02-01  
Zonglin Li; Chong You; Srinadh Bhojanapalli; Daliang Li; Ankit Singh Rawat; Sashank J. Reddi; Ke Ye; Felix Chern; Felix Yu; Ruiqi Guo; Sanjiv Kumar

</details>


## **Representational Capacity**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Categories focused on the representational capacities and limitations of transformers and language models.

### **What Can Transformer Do? / Properties of Transformer**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers providing positive results into the capabilities and properties of transformer-based models, e.g., expressiveness and learning abilities.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Fundamental Limits of Prompt Tuning Transformers: Universality, Capacity and Efficiency** [[paper link]](http://arxiv.org/abs/2411.16525) 2024-11-25  
Jerry Yao-Chieh Hu; Wei-Po Wang; Ammar Gilani; Chenyang Li; Zhao Song; Han Liu



- **Mechanism and Emergence of Stacked Attention Heads in Multi-Layer Transformers** [[paper link]](http://arxiv.org/abs/2411.12118) 2024-11-18  
Tiberiu Musat



- **Measure-to-measure interpolation using Transformers** [[paper link]](http://arxiv.org/abs/2411.04551) 2024-11-07  
Borjan Geshkovski; Philippe Rigollet; Domènec Ruiz-Balet



- **Ask, and it shall be given: Turing completeness of prompting** [[paper link]](http://arxiv.org/abs/2411.01992) 2024-11-04  
Ruizhong Qiu; Zhe Xu; Wenxuan Bao; Hanghang Tong



- **Provable Optimal Transport with Transformers: The Essence of Depth and Prompt Engineering** [[paper link]](http://arxiv.org/abs/2410.19931) 2024-10-25  
Hadi Daneshmand



- **On the Learn-to-Optimize Capabilities of Transformers in In-Context Sparse Recovery** [[paper link]](http://arxiv.org/abs/2410.13981) 2024-10-17  
Renpu Liu; Ruida Zhou; Cong Shen; Jing Yang



- **Theoretical Analysis of Hierarchical Language Recognition and Generation by Transformers without Positional Encoding** [[paper link]](http://arxiv.org/abs/2410.12413) 2024-10-16  
Daichi Hayakawa; Issei Sato



- **Memory-augmented Transformers can implement Linear First-Order Optimization Methods** [[paper link]](http://arxiv.org/abs/2410.07263) 2024-10-08  
Sanchayan Dutta; Suvrit Sra



- **Transformers are Efficient Compilers, Provably** [[paper link]](http://arxiv.org/abs/2410.14706) 2024-10-07  
Xiyu Zhai; Runlong Zhou; Liao Zhang; Simon Shaolei Du



- **Fundamental Limitations on Subquadratic Alternatives to Transformers** [[paper link]](http://arxiv.org/abs/2410.04271) 2024-10-05  
Josh Alman; Hantao Yu



- **Autoregressive Large Language Models are Computationally Universal** [[paper link]](http://arxiv.org/abs/2410.03170) 2024-10-04  
Dale Schuurmans; Hanjun Dai; Francesco Zanini



- **Can Transformers Learn n-gram Language Models?** [[paper link]](http://arxiv.org/abs/2410.03001) 2024-10-03  
Anej Svete; Nadav Borenstein; Mike Zhou; Isabelle Augenstein; Ryan Cotterell



- **Towards Understanding the Universality of Transformers for Next-Token Prediction** [[paper link]](http://arxiv.org/abs/2410.03011) 2024-10-03  
Michael E. Sander; Gabriel Peyré



- **Large Language Models as Markov Chains** [[paper link]](http://arxiv.org/abs/2410.02724) 2024-10-03  
Oussama Zekri; Ambroise Odonnat; Abdelhakim Benechehab; Linus Bleistein; Nicolas Boullé; Ievgen Redko



- **On Expressive Power of Looped Transformers: Theoretical Analysis and Enhancement via Timestep Encoding** [[paper link]](http://arxiv.org/abs/2410.01405) 2024-10-02  
Kevin Xu; Issei Sato



- **Attention layers provably solve single-location regression** [[paper link]](http://arxiv.org/abs/2410.01537) 2024-10-02  
Pierre Marion; Raphaël Berthier; Gérard Biau; Claire Boyer



- **Transformers in Uniform TC0** [[paper link]](http://arxiv.org/abs/2409.13629) 2024-09-20  
David Chiang



- **How Transformers Learn Structured Data: Insights from Hierarchical Filtering** [[paper link]](http://arxiv.org/abs/2408.15138) 2024-08-27  
Jerome Garnier-Brun; Marc Mézard; Emanuele Moscato; Luca Saglietti



- **Implicit Geometry of Next-token Prediction: From Language Sparsity Patterns to Model Representations** [[paper link]](http://arxiv.org/abs/2408.15417) 2024-08-27  
Yize Zhao; Tina Behnia; Vala Vakilian; Christos Thrampoulidis



- **A Law of Next-Token Prediction in Large Language Models** [[paper link]](http://arxiv.org/abs/2408.13442) 2024-08-24  
Hangfeng He; Weijie J. Su



- **Transformers As Approximations of Solomonoff Induction** [[paper link]](http://arxiv.org/abs/2408.12065) 2024-08-22  
Nathan Young; Michael Witbrock



- **Learning Randomized Algorithms with Transformers** [[paper link]](http://arxiv.org/abs/2408.10818) 2024-08-20  
Johannes von Oswald; Seijin Kobayashi; Yassir Akram; Angelika Steger



- **Attention is a smoothed cubic spline** [[paper link]](http://arxiv.org/abs/2408.09624) 2024-08-19  
Zehua Lai; Lek-Heng Lim; Yucong Liu



- **Why Transformers are Obviously Good Models of Language** [[paper link]](http://arxiv.org/abs/2408.03855) 2024-08-07  
Felix Hill



- **Can LLMs predict the convergence of Stochastic Gradient Descent?** [[paper link]](http://arxiv.org/abs/2408.01736) 2024-08-03  
Oussama Zekri; Abdelhakim Benechehab; Ievgen Redko



- **Transformers on Markov Data: Constant Depth Suffices** [[paper link]](http://arxiv.org/abs/2407.17686) 2024-07-25  
Nived Rajaraman; Marco Bondaschi; Kannan Ramchandran; Michael Gastpar; Ashok Vardhan Makkuva



- **Do Large Language Models Have Compositional Ability? An Investigation into Limitations and Scalability** [[paper link]](http://arxiv.org/abs/2407.15720) 2024-07-22  
Zhuoyan Xu; Zhenmei Shi; Yingyu Liang



- **Universal Approximation Theory: The basic theory for large language models** [[paper link]](http://arxiv.org/abs/2407.00958) 2024-07-01  
Wei Wang; Qing Li



- **Seperations in the Representational Capabilities of Transformers and Recurrent Architectures** [[paper link]](http://arxiv.org/abs/2406.09347) 2024-06-13  
Satwik Bhattamishra; Michael Hahn; Phil Blunsom; Varun Kanade



- **Transformers Provably Learn Sparse Token Selection While Fully-Connected Nets Cannot** [[paper link]](http://arxiv.org/abs/2406.06893) 2024-06-11  
Zixuan Wang; Stanley Wei; Daniel Hsu; Jason D. Lee



- **What Languages are Easy to Language-Model? A Perspective from Learning Probabilistic Regular Languages** [[paper link]](http://arxiv.org/abs/2406.04289) 2024-06-07  
Nadav Borenstein; Anej Svete; Robin Chan; Josef Valvoda; Franz Nowak; Isabelle Augenstein; Eleanor Chodroff; Ryan Cotterell



- **Physics of Language Models: Part 1, Learning Hierarchical Language Structures** [[paper link]](http://arxiv.org/abs/2305.13673) 2024-06-02  
Zeyuan Allen-Zhu; Yuanzhi Li



- **Transformers Can Do Arithmetic with the Right Embeddings** [[paper link]](http://arxiv.org/abs/2405.17399) 2024-05-27  
Sean McLeish; Arpit Bansal; Alex Stein; Neel Jain; John Kirchenbauer; Brian R. Bartoldson; Bhavya Kailkhura; Abhinav Bhatele; Jonas Geiping; Avi Schwarzschild; Tom Goldstein



- **A One-Layer Decoder-Only Transformer is a Two-Layer RNN: With an Application to Certified Robustness** [[paper link]](http://arxiv.org/abs/2405.17361) 2024-05-27  
Yuhao Zhang; Aws Albarghouthi; Loris D'Antoni



- **The Power of Hard Attention Transformers on Data Sequences: A Formal Language Theoretic Perspective** [[paper link]](http://arxiv.org/abs/2405.16166) 2024-05-25  
Pascal Bergsträßer; Chris Köcher; Anthony Widjaja Lin; Georg Zetzsche



- **Transformers represent belief state geometry in their residual stream** [[paper link]](http://arxiv.org/abs/2405.15943) 2024-05-24  
Adam S. Shai; Sarah E. Marzen; Lucas Teixeira; Alexander Gietelink Oldenziel; Paul M. Riechers



- **ALPINE: Unveiling the Planning Capability of Autoregressive Learning in Language Models** [[paper link]](http://arxiv.org/abs/2405.09220) 2024-05-15  
 Siwei Wang; Yifei Shen; Shi Feng; Haoran Sun; Shang-Hua Teng; Wei Chen



- **What Formal Languages Can Transformers Express? A Survey** [[paper link]](http://arxiv.org/abs/2311.00208) 2024-05-06  
Lena Strobl; William Merrill; Gail Weiss; David Chiang; Dana Angluin



- **Transformers Can Represent $n$-gram Language Models** [[paper link]](http://arxiv.org/abs/2404.14994) 2024-04-23  
Anej Svete; Ryan Cotterell



- **Mechanics of Next Token Prediction with Self-Attention** [[paper link]](https://proceedings.mlr.press/v238/li24f.html) 2024-04-18  
Yingcong Li; Yixiao Huang; Muhammed E. Ildiz; Ankit Singh Rawat; Samet Oymak



- **When can transformers reason with abstract symbols?** [[paper link]](http://arxiv.org/abs/2310.09753) 2024-04-16  
Enric Boix-Adsera; Omid Saremi; Emmanuel Abbe; Samy Bengio; Etai Littwin; Joshua Susskind



- **The Illusion of State in State-Space Models** [[paper link]](http://arxiv.org/abs/2404.08819) 2024-04-12  
William Merrill; Jackson Petty; Ashish Sabharwal



- **Language Generation in the Limit** [[paper link]](http://arxiv.org/abs/2404.06757) 2024-04-10  
Jon Kleinberg; Sendhil Mullainathan



- **Attention is Naturally Sparse with Gaussian Distributed Input** [[paper link]](http://arxiv.org/abs/2404.02690) 2024-04-03  
Yichuan Deng; Zhao Song; Chiwun Yang



- **What Can Transformer Learn with Varying Depth? Case Studies on Sequence Learning Tasks** [[paper link]](http://arxiv.org/abs/2404.01601) 2024-04-01  
Xingwu Chen; Difan Zou



- **The Topos of Transformer Networks** [[paper link]](http://arxiv.org/abs/2403.18415) 2024-03-27  
Mattia Jacopo Villani; Peter McBurney



- **Simulating Weighted Automata over Sequences and Trees with Transformers** [[paper link]](http://arxiv.org/abs/2403.09728) 2024-03-12  
Michael Rizvi; Maude Lizaire; Clara Lacroce; Guillaume Rabusseau



- **Simplicity Bias of Transformers to Learn Low Sensitivity Functions** [[paper link]](http://arxiv.org/abs/2403.06925) 2024-03-11  
Bhavya Vasudeva; Deqing Fu; Tianyi Zhou; Elliott Kau; Youqi Huang; Vatsal Sharan



- **On the Origins of Linear Representations in Large Language Models** [[paper link]](http://arxiv.org/abs/2403.03867) 2024-03-06  
Yibo Jiang; Goutham Rajendran; Pradeep Ravikumar; Bryon Aragam; Victor Veitch



- **How Well Can Transformers Emulate In-context Newton's Method?** [[paper link]](http://arxiv.org/abs/2403.03183) 2024-03-05  
Angeliki Giannou; Liu Yang; Tianhao Wang; Dimitris Papailiopoulos; Jason D. Lee



- **RNNs are not Transformers (Yet): The Key Bottleneck on In-context Retrieval** [[paper link]](http://arxiv.org/abs/2402.18510) 2024-02-29  
Kaiyue Wen; Xingyu Dang; Kaifeng Lyu



- **Implicit Bias of Next-Token Prediction** [[paper link]](http://arxiv.org/abs/2402.18551) 2024-02-28  
Christos Thrampoulidis



- **On the Expressive Power of a Variant of the Looped Transformer** [[paper link]](http://arxiv.org/abs/2402.13572) 2024-02-21  
Yihang Gao; Chuanyang Zheng; Enze Xie; Han Shi; Tianyang Hu; Yu Li; Michael K. Ng; Zhenguo Li; Zhaoqiang Liu



- **From Self-Attention to Markov Models: Unveiling the Dynamics of Generative Transformers** [[paper link]](http://arxiv.org/abs/2402.13512) 2024-02-20  
M. Emrullah Ildiz; Yixiao Huang; Yingcong Li; Ankit Singh Rawat; Samet Oymak



- **Transformers Implement Functional Gradient Descent to Learn Non-Linear Functions In Context** [[paper link]](http://arxiv.org/abs/2312.06528) 2024-02-15  
Xiang Cheng; Yuxin Chen; Suvrit Sra



- **Compositional Capabilities of Autoregressive Transformers: A Study on Synthetic, Interpretable Tasks** [[paper link]](http://arxiv.org/abs/2311.12997) 2024-02-05  
Rahul Ramesh; Ekdeep Singh Lubana; Mikail Khona; Robert P. Dick; Hidenori Tanaka



- **Are Transformers with One Layer Self-Attention Using Low-Rank Weight Matrices Universal Approximators?** [[paper link]](http://arxiv.org/abs/2307.14023) 2024-01-29  
Tokio Kajitsuka; Issei Sato



- **Transformers are Multi-State RNNs** [[paper link]](http://arxiv.org/abs/2401.06104) 2024-01-11  
Matanel Oren; Michael Hassid; Yossi Adi; Roy Schwartz



- **How Capable Can a Transformer Become? A Study on Synthetic, Interpretable Tasks** [[paper link]](https://openreview.net/forum?id=KIhFggzePM) 2023-12-12  
Rahul Ramesh; Mikail Khona; Robert P. Dick; Hidenori Tanaka; Ekdeep Singh Lubana



- **Transformers can optimally learn regression mixture models** [[paper link]](http://arxiv.org/abs/2311.08362) 2023-11-14  
Reese Pathak; Rajat Sen; Weihao Kong; Abhimanyu Das



- **The Expressive Power of Low-Rank Adaptation** [[paper link]](http://arxiv.org/abs/2310.17513) 2023-10-26  
Yuchen Zeng; Kangwook Lee



- **What Algorithms can Transformers Learn? A Study in Length Generalization** [[paper link]](http://arxiv.org/abs/2310.16028) 2023-10-24  
Hattie Zhou; Arwen Bradley; Etai Littwin; Noam Razin; Omid Saremi; Josh Susskind; Samy Bengio; Preetum Nakkiran



- **Transformers as Support Vector Machines** [[paper link]](http://arxiv.org/abs/2308.16898) 2023-09-07  
Davoud Ataee Tarzanagh; Yingcong Li; Christos Thrampoulidis; Samet Oymak



- **How Do Transformers Learn Topic Structure: Towards a Mechanistic Understanding** [[paper link]](https://openreview.net/forum?id=LMXgU4zrq6) 2023-06-15  
Yuchen Li; Yuanzhi Li; Andrej Risteski



- **Tighter Bounds on the Expressivity of Transformer Encoders** [[paper link]](https://openreview.net/forum?id=XKcogevHj8) 2023-06-15  
David Chiang; Peter Cholak; Anand Pillay



- **Fast Attention Requires Bounded Entries** [[paper link]](https://arxiv.org/abs/2302.13214v2) 2023-02-26  
Josh Alman; Zhao Song



- **Transformers Learn Shortcuts to Automata** [[paper link]](https://openreview.net/forum?id=De4FYqjFueZ) 2023-02-01  
Bingbin Liu; Jordan T. Ash; Surbhi Goel; Akshay Krishnamurthy; Cyril Zhang



- **Transformer Vs. MLP-Mixer: Exponential Expressive Gap For NLP Problems** [[paper link]](http://arxiv.org/abs/2208.08191) 2022-11-17  
Dan Navon; Alex M. Bronstein



- **Small Transformers Compute Universal Metric Embeddings** [[paper link]](http://arxiv.org/abs/2209.06788) 2022-10-18  
Anastasis Kratsios; Valentin Debarnot; Ivan Dokmanić



- **The Lipschitz Constant of Self-Attention** [[paper link]](http://arxiv.org/abs/2006.04710) 2021-06-09  
Hyunjik Kim; George Papamakarios; Andriy Mnih



- **On Identifiability in Transformers** [[paper link]](http://arxiv.org/abs/1908.04211) 2020-02-07  
Gino Brunner; Yang Liu; Damián Pascual; Oliver Richter; Massimiliano Ciaramita; Roger Wattenhofer

</details>


### **What Can Transformer Not Do? / Limitation of Transformer**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers investigating the limitations of transformer-based models, including expressiveness and learning constraints, e.g., limitations in reasoning.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Circuit Complexity Bounds for RoPE-based Transformer Architecture** [[paper link]](http://arxiv.org/abs/2411.07602) 2024-11-12  
Bo Chen; Xiaoyu Li; Yingyu Liang; Jiangxuan Long; Zhenmei Shi; Zhao Song



- **Consistent Bidirectional Language Modelling: Expressive Power and Representational Conciseness** [[paper link]](http://aclanthology.org/2024.emnlp-main.328) 2024-11  
Georgi Shopov; Stefan Gerdjikov



- **How Numerical Precision Affects Mathematical Reasoning Capabilities of LLMs** [[paper link]](http://arxiv.org/abs/2410.13857) 2024-10-17  
Guhao Feng; Kai Yang; Yuntian Gu; Xinyue Ai; Shengjie Luo; Jiacheng Sun; Di He; Zhenguo Li; Liwei Wang



- **Self-Attention Limits Working Memory Capacity of Transformer-Based Models** [[paper link]](http://arxiv.org/abs/2409.10715) 2024-09-16  
Dongyu Gong; Hantao Zhang



- **One-layer transformers fail to solve the induction heads task** [[paper link]](http://arxiv.org/abs/2408.14332) 2024-08-26  
Clayton Sanford; Daniel Hsu; Matus Telgarsky



- **Your Context Is Not an Array: Unveiling Random Access Limitations in Transformers** [[paper link]](http://arxiv.org/abs/2408.05506) 2024-08-10  
MohammadReza Ebrahimi; Sunny Panchal; Roland Memisevic



- **When Can Transformers Count to n?** [[paper link]](http://arxiv.org/abs/2407.15160) 2024-07-21  
Gilad Yehudai; Haim Kaplan; Asma Ghandeharioun; Mor Geva; Amir Globerson



- **When can transformers compositionally generalize in-context?** [[paper link]](http://arxiv.org/abs/2407.12275) 2024-07-17  
Seijin Kobayashi; Simon Schug; Yassir Akram; Florian Redhardt; Johannes von Oswald; Razvan Pascanu; Guillaume Lajoie; João Sacramento



- **Hopping Too Late: Exploring the Limitations of Large Language Models on Multi-Hop Queries** [[paper link]](http://arxiv.org/abs/2406.12775) 2024-06-18  
Eden Biran; Daniela Gottesman; Sohee Yang



- **How Far Can Transformers Reason? The Locality Barrier and Inductive Scratchpad** [[paper link]](http://arxiv.org/abs/2406.06467) 2024-06-10  
Emmanuel Abbe; Samy Bengio; Aryo Lotfi; Colin Sandon; Omid Saremi



- **Transformers Need Glasses! Information Over-squashing in Language Tasks** [[paper link]](http://arxiv.org/abs/2406.04267) 2024-06-06  
Federico Barbero; Andrea Banino; Steven Kapturowski; Dharshan Kumaran; João G.M. Araújo; Alex Vitvitskyi; Razvan Pascanu; Petar Veličković



- **On Limitation of Transformer for Learning HMMs** [[paper link]](http://arxiv.org/abs/2406.04089) 2024-06-06  
Jiachen Hu; Qinghua Liu; Chi Jin



- **Language Models Need Inductive Biases to Count Inductively** [[paper link]](http://arxiv.org/abs/2405.20131) 2024-05-30  
Yingshan Chang; Yonatan Bisk



- **Limits of Deep Learning: Sequence Modeling through the Lens of Complexity Theory** [[paper link]](http://arxiv.org/abs/2405.16674) 2024-05-26  
Nikola Zubić; Federico Soldá; Aurelio Sulser; Davide Scaramuzza



- **Attention Mechanisms Don't Learn Additive Models: Rethinking Feature Importance for Transformers** [[paper link]](http://arxiv.org/abs/2405.13536) 2024-05-22  
Tobias Leemann; Alina Fastowski; Felix Pfeiffer; Gjergji Kasneci



- **Collapse of Self-trained Language Models** [[paper link]](http://arxiv.org/abs/2404.02305) 2024-04-02  
David Herel; Tomas Mikolov



- **The pitfalls of next-token prediction** [[paper link]](http://arxiv.org/abs/2403.06963) 2024-03-11  
Gregor Bachmann; Vaishnavh Nagarajan



- **Why are Sensitive Functions Hard for Transformers?** [[paper link]](http://arxiv.org/abs/2402.09963) 2024-03-03  
Michael Hahn; Mark Rofin



- **Transformers are Expressive, But Are They Expressive Enough for Regression?** [[paper link]](http://arxiv.org/abs/2402.15478) 2024-02-23  
Swaroop Nath; Harshad Khadilkar; Pushpak Bhattacharyya



- **Limits of Transformer Language Models on Learning Algorithmic Compositions** [[paper link]](http://arxiv.org/abs/2402.05785) 2024-02-13  
Jonathan Thomm; Aleksandar Terzic; Geethan Karunaratne; Giacomo Camposampiero; Bernhard Schölkopf; Abbas Rahimi



- **Representational Strengths and Limitations of Transformers** [[paper link]](http://arxiv.org/abs/2306.02896) 2023-11-16  
Clayton Sanford; Daniel Hsu; Matus Telgarsky



- **Large Language Models Cannot Self-Correct Reasoning Yet** [[paper link]](https://openreview.net/forum?id=IkmD3fKBPQ) 2023-10-13  
Jie Huang; Xinyun Chen; Swaroop Mishra; Huaixiu Steven Zheng; Adams Wei Yu; Xinying Song; Denny Zhou



- **Attention is Not All You Need: Pure Attention Loses Rank Doubly Exponentially with Depth** [[paper link]](http://arxiv.org/abs/2103.03404) 2023-08-01  
Yihe Dong; Jean-Baptiste Cordonnier; Andreas Loukas



- **Limits for Learning with Language Models** [[paper link]](http://arxiv.org/abs/2306.12213) 2023-06-21  
Nicholas Asher; Swarnadeep Bhar; Akshay Chaturvedi; Julie Hunter; Soumya Paul



- **Your Transformer May Not be as Powerful as You Expect** [[paper link]](https://openreview.net/forum?id=NQFFNdsOGD) 2022-10-31  
Shengjie Luo; Shanda Li; Shuxin Zheng; Tie-Yan Liu; Liwei Wang; Di He



- **The Devil in Linear Transformer** [[paper link]](http://arxiv.org/abs/2210.10340) 2022-10-19  
Zhen Qin; XiaoDong Han; Weixuan Sun; Dongxu Li; Lingpeng Kong; Nick Barnes; Yiran Zhong



- **On the Ability and Limitations of Transformers to Recognize Formal Languages** [[paper link]](http://arxiv.org/abs/2009.11264) 2020-09-23  
Satwik Bhattamishra; Kabir Ahuja; Navin Goyal

</details>


## **Architectural Effectivity**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Categories analyzing different architectural components and their effects in transformer models.

### **Layer-normalization**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers discussing the role, effects, and optimization of layer normalization in transformer models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Re-Introducing LayerNorm: Geometric Meaning, Irreversibility and a Comparative Study with RMSNorm** [[paper link]](http://arxiv.org/abs/2409.12951) 2024-09-19  
Akshat Gupta; Atahan Ozdemir; Gopala Anumanchipalli



- **On the Role of Attention Masks and LayerNorm in Transformers** [[paper link]](http://arxiv.org/abs/2405.18781) 2024-05-29  
Xinyi Wu; Amir Ajorlou; Yifei Wang; Stefanie Jegelka; Ali Jadbabaie



- **The Expressive Power of Tuning Only the Normalization Layers** [[paper link]](https://proceedings.mlr.press/v195/giannou23a.html) 2023-07-12  
Angeliki Giannou; Shashank Rajput; Dimitris Papailiopoulos



- **ResiDual: Transformer with Dual Residual Connections** [[paper link]](http://arxiv.org/abs/2304.14802) 2023-04-28  
Shufang Xie; Huishuai Zhang; Junliang Guo; Xu Tan; Jiang Bian; Hany Hassan Awadalla; Arul Menezes; Tao Qin; Rui Yan



- **DeepNet: Scaling Transformers to 1,000 Layers** [[paper link]](http://arxiv.org/abs/2203.00555) 2022-03-01  
Hongyu Wang; Shuming Ma; Li Dong; Shaohan Huang; Dongdong Zhang; Furu Wei



- **On Layer Normalization in the Transformer Architecture** [[paper link]](http://arxiv.org/abs/2002.04745) 2020-06-29  
Ruibin Xiong; Yunchang Yang; Di He; Kai Zheng; Shuxin Zheng; Chen Xing; Huishuai Zhang; Yanyan Lan; Liwei Wang; Tie-Yan Liu

</details>


### **Tokenization / Embedding**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers focused on tokenization, embedding strategies, and input representations in language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Theoretical Analysis of Byte-Pair Encoding** [[paper link]](http://arxiv.org/abs/2411.08671) 2024-11-13  
László Kozma; Johannes Voderholzer



- **Counting Ability of Large Language Models and Impact of Tokenization** [[paper link]](http://arxiv.org/abs/2410.19730) 2024-10-25  
Xiang Zhang; Juntai Cao; Chenyu You



- **Tokenization as Finite-State Transduction** [[paper link]](http://arxiv.org/abs/2410.15696) 2024-10-21  
Marco Cognetta; Naoaki Okazaki



- **Tokenization and Morphology in Multilingual Language Models: A Comparative Analysis of mT5 and ByT5** [[paper link]](http://arxiv.org/abs/2410.11627) 2024-10-15  
Thao Anh Dang; Limor Raviv; Lukas Galke



- **From Tokens to Words: On the Inner Lexicon of LLMs** [[paper link]](http://arxiv.org/abs/2410.05864) 2024-10-08  
Guy Kaplan; Matanel Oren; Yuval Reif; Roy Schwartz



- **Norm of Mean Contextualized Embeddings Determines their Variance** [[paper link]](http://arxiv.org/abs/2409.11253) 2024-09-17  
Hiroaki Yamagiwa; Hidetoshi Shimodaira



- **Where is the signal in tokenization space?** [[paper link]](http://arxiv.org/abs/2408.08541) 2024-08-16  
Renato Lui Geh; Honghua Zhang; Kareem Ahmed; Benjie Wang; Guy Van den Broeck



- **Monotonic Representation of Numeric Properties in Language Models** [[paper link]](http://arxiv.org/abs/2408.10381) 2024-08-15  
Benjamin Heinzerling; Kentaro Inui



- **Reconsidering Token Embeddings with the Definitions for Pre-trained Language Models** [[paper link]](http://arxiv.org/abs/2408.01308) 2024-08-02  
Ying Zhang; Dongyuan Li; Manabu Okumura



- **Data Mixture Inference: What do BPE Tokenizers Reveal about their Training Data?** [[paper link]](http://arxiv.org/abs/2407.16607) 2024-07-23  
Jonathan Hayase; Alisa Liu; Yejin Choi; Sewoong Oh; Noah A. Smith



- **Scaling Laws with Vocabulary: Larger Models Deserve Larger Vocabularies** [[paper link]](http://arxiv.org/abs/2407.13623) 2024-07-18  
Chaofan Tao; Qian Liu; Longxu Dou; Niklas Muennighoff; Zhongwei Wan; Ping Luo; Min Lin; Ngai Wong



- **On Initialization of Transformers with Pre-trained Embeddings** [[paper link]](http://arxiv.org/abs/2407.12514) 2024-07-17  
Ha Young Kim; Niranjan Balasubramanian; Byungkon Kang



- **An Empirical Comparison of Vocabulary Expansion and Initialization Approaches for Language Models** [[paper link]](http://arxiv.org/abs/2407.05841) 2024-07-08  
Nandini Mundra; Aditya Nanda Kishore; Raj Dabre; Ratish Puduppully; Anoop Kunchukuttan; Mitesh M. Khapra



- **Understanding and Mitigating Tokenization Bias in Language Models** [[paper link]](http://arxiv.org/abs/2406.16829) 2024-06-24  
Buu Phan; Marton Havasi; Matthew Muckley; Karen Ullrich



- **Large Vocabulary Size Improves Large Language Models** [[paper link]](http://arxiv.org/abs/2406.16508) 2024-06-24  
Sho Takase; Ryokan Ri; Shun Kiyono; Takuya Kato



- **Transformers Can Do Arithmetic with the Right Embeddings** [[paper link]](http://arxiv.org/abs/2405.17399) 2024-05-27  
Sean McLeish; Arpit Bansal; Alex Stein; Neel Jain; John Kirchenbauer; Brian R. Bartoldson; Bhavya Kailkhura; Abhinav Bhatele; Jonas Geiping; Avi Schwarzschild; Tom Goldstein



- **By Tying Embeddings You Are Assuming the Distributional Hypothesis** [[paper link]](https://openreview.net/pdf?id=yyYMAprcAR) 2024-05-02  
Francesco Bertolotti; Walter Cazzola



- **Toward a Theory of Tokenization in LLMs** [[paper link]](http://arxiv.org/abs/2404.08335) 2024-04-12  
Nived Rajaraman; Jiantao Jiao; Kannan Ramchandran



- **On the Effect of (Near) Duplicate Subwords in Language Modelling** [[paper link]](http://arxiv.org/abs/2404.06508) 2024-04-09  
Anton Schäfer; Thomas Hofmann; Imanol Schlag; Tiago Pimentel



- **Tokenization Is More Than Compression** [[paper link]](http://arxiv.org/abs/2402.18376) 2024-02-28  
Craig W. Schmidt; Varshini Reddy; Haoran Zhang; Alec Alameddine; Omri Uzan; Yuval Pinter; Chris Tanner



- **Small Transformers Compute Universal Metric Embeddings** [[paper link]](http://arxiv.org/abs/2209.06788) 2022-10-18  
Anastasis Kratsios; Valentin Debarnot; Ivan Dokmanić

</details>


### **Linear Attention / State Space Models / Recurrent Language Models / etc.**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Papers analyzing alternative architectures to the standard transformer models, such as linear attention and state space models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **kNN Attention Demystified: A Theoretical Exploration for Scalable Transformers** [[paper link]](http://arxiv.org/abs/2411.04013) 2024-11-06  
Themistoklis Haris



- **Fundamental Limitations on Subquadratic Alternatives to Transformers** [[paper link]](http://arxiv.org/abs/2410.04271) 2024-10-05  
Josh Alman; Hantao Yu



- **Autoregressive + Chain of Thought (CoT) ≃ Recurrent: Recurrence's Role in Language Models and a Revist of Recurrent Transformer** [[paper link]](http://arxiv.org/abs/2409.09239) 2024-09-14  
Xiang Zhang; Muhammad Abdul-Mageed; Laks V.S. Lakshmanan



- **Theory, Analysis, and Best Practices for Sigmoid Self-Attention** [[paper link]](http://arxiv.org/abs/2409.04431) 2024-09-06  
Jason Ramapuram; Federico Danieli; Eeshan Dhekane; Floris Weers; Dan Busbridge; Pierre Ablin; Tatiana Likhomanenko; Jagrit Digani; Zijin Gu; Amitis Shidani; Russ Webb



- **Recurrent Neural Networks Learn to Store and Generate Sequences using Non-Linear Representations** [[paper link]](http://arxiv.org/abs/2408.10920) 2024-08-20  
Róbert Csordás; Christopher Potts; Christopher D. Manning; Atticus Geiger



- **Transformers to SSMs: Distilling Quadratic Knowledge to Subquadratic Models** [[paper link]](http://arxiv.org/abs/2408.10189) 2024-08-19  
Aviv Bick; Kevin Y. Li; Eric P. Xing; J. Zico Kolter; Albert Gu



- **Just read twice: closing the recall gap for recurrent language models** [[paper link]](http://arxiv.org/abs/2407.05483) 2024-07-07  
Simran Arora; Aman Timalsina; Aaryan Singhal; Benjamin Spector; Sabri Eyuboglu; Xinyi Zhao; Ashish Rao; Atri Rudra; Christopher Ré



- **Parallelizing Linear Transformers with the Delta Rule over Sequence Length** [[paper link]](http://arxiv.org/abs/2406.06484) 2024-06-10  
Songlin Yang; Bailin Wang; Yu Zhang; Yikang Shen; Yoon Kim



- **Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality** [[paper link]](http://arxiv.org/abs/2405.21060) 2024-05-31  
Tri Dao; Albert Gu

</details>


## **Training Paradigms**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Categories discussing various training methodologies and paradigms for language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **Knowledge Distillation vs. Pretraining from Scratch under a Fixed (Computation) Budget** [[paper link]](http://arxiv.org/abs/2404.19319) 2024-04-30  
Minh Duc Bui; Fabian David Schmidt; Goran Glavaš; Katharina von der Wense



- **Why are Adaptive Methods Good for Attention Models?** [[paper link]](http://arxiv.org/abs/1912.03194) 2020-10-23  
Jingzhao Zhang; Sai Praneeth Karimireddy; Andreas Veit; Seungyeon Kim; Sashank J. Reddi; Sanjiv Kumar; Suvrit Sra

</details>


## **Mechanistic Engineering / Probing / Interpretability**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Categories exploring the internal mechanisms and interpretability of language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **How Transformers Solve Propositional Logic Problems: A Mechanistic Analysis** [[paper link]](http://arxiv.org/abs/2411.04105) 2024-11-06  
Guan Zhe Hong; Nishanth Dikkala; Enming Luo; Cyrus Rashtchian; Xin Wang; Rina Panigrahy



- **Towards Interpreting Language Models: A Case Study in Multi-Hop Reasoning** [[paper link]](http://arxiv.org/abs/2411.05037) 2024-11-06  
Mansi Sakarvadia



- **Mechanisms of Symbol Processing for In-Context Learning in Transformer Networks** [[paper link]](http://arxiv.org/abs/2410.17498) 2024-10-23  
Paul Smolensky; Roland Fernandez; Zhenghao Herbert Zhou; Mattia Opper; Jianfeng Gao



- **Interpreting Affine Recurrence Learning in GPT-style Transformers** [[paper link]](http://arxiv.org/abs/2410.17438) 2024-10-22  
Samarth Bhargav; Alexander Gu



- **Extracting Finite State Machines from Transformers** [[paper link]](http://arxiv.org/abs/2410.06045) 2024-10-08  
Rik Adriaensen; Jaron Maene



- **Optimal ablation for interpretability** [[paper link]](http://arxiv.org/abs/2409.09951) 2024-09-16  
Maximilian Li; Lucas Janson



- **Self-Attention Limits Working Memory Capacity of Transformer-Based Models** [[paper link]](http://arxiv.org/abs/2409.10715) 2024-09-16  
Dongyu Gong; Hantao Zhang



- **Explaining Datasets in Words: Statistical Models with Natural Language Parameters** [[paper link]](http://arxiv.org/abs/2409.08466) 2024-09-13  
Ruiqi Zhong; Heng Wang; Dan Klein; Jacob Steinhardt



- **Extracting Paragraphs from LLM Token Activations** [[paper link]](http://arxiv.org/abs/2409.06328) 2024-09-10  
Nicholas Pochinkov; Angelo Benoit; Lovkush Agarwal; Zainab Ali Majid; Lucile Ter-Minassian



- **Modularity in Transformers: Investigating Neuron Separability & Specialization** [[paper link]](http://arxiv.org/abs/2408.17324) 2024-08-30  
Nicholas Pochinkov; Thomas Jones; Mohammed Rashidur Rahman



- **A Mechanistic Interpretation of Syllogistic Reasoning in Auto-Regressive Language Models** [[paper link]](http://arxiv.org/abs/2408.08590) 2024-08-16  
Geonhee Kim; Marco Valentino; André Freitas



- **Monotonic Representation of Numeric Properties in Language Models** [[paper link]](http://arxiv.org/abs/2408.10381) 2024-08-15  
Benjamin Heinzerling; Kentaro Inui



- **The Mechanics of Conceptual Interpretation in GPT Models: Interpretative Insights** [[paper link]](http://arxiv.org/abs/2408.11827) 2024-08-05  
Nura Aljaafari; Danilo S. Carvalho; André Freitas



- **Answer, Assemble, Ace: Understanding How Transformers Answer Multiple Choice Questions** [[paper link]](http://arxiv.org/abs/2407.15018) 2024-07-21  
Sarah Wiegreffe; Oyvind Tafjord; Yonatan Belinkov; Hannaneh Hajishirzi; Ashish Sabharwal



- **LLM Circuit Analyses Are Consistent Across Training and Scale** [[paper link]](http://arxiv.org/abs/2407.10827) 2024-07-15  
Curt Tigges; Michael Hanna; Qinan Yu; Stella Biderman



- **Transformer Layers as Painters** [[paper link]](http://arxiv.org/abs/2407.09298) 2024-07-12  
Qi Sun; Marc Pickett; Aakash Kumar Nain; Llion Jones



- **Transformer Circuit Faithfulness Metrics are not Robust** [[paper link]](http://arxiv.org/abs/2407.08734) 2024-07-11  
Joseph Miller; Bilal Chughtai; William Saunders



- **Monitoring Latent World States in Language Models with Propositional Probes** [[paper link]](http://arxiv.org/abs/2406.19501) 2024-06-27  
Jiahai Feng; Stuart Russell; Jacob Steinhardt



- **Clustering in pure-attention hardmax transformers and its role in sentiment analysis** [[paper link]](http://arxiv.org/abs/2407.01602) 2024-06-26  
Albert Alcalde; Giovanni Fantuzzi; Enrique Zuazua



- **Interpreting Attention Layer Outputs with Sparse Autoencoders** [[paper link]](http://arxiv.org/abs/2406.17759) 2024-06-25  
Connor Kissane; Robert Krzyzanowski; Joseph Isaac Bloom; Arthur Conmy; Neel Nanda



- **Large Language Models are Interpretable Learners** [[paper link]](http://arxiv.org/abs/2406.17224) 2024-06-25  
Ruochen Wang; Si Si; Felix Yu; Dorothea Wiesmann; Cho-Jui Hsieh; Inderjit Dhillon



- **Transformer Normalisation Layers and the Independence of Semantic Subspaces** [[paper link]](http://arxiv.org/abs/2406.17837) 2024-06-25  
Stephen Menary; Samuel Kaski; Andre Freitas



- **Confidence Regulation Neurons in Language Models** [[paper link]](http://arxiv.org/abs/2406.16254) 2024-06-24  
Alessandro Stolfo; Ben Wu; Wes Gurnee; Yonatan Belinkov; Xingyi Song; Mrinmaya Sachan; Neel Nanda



- **Finding Transformer Circuits with Edge Pruning** [[paper link]](http://arxiv.org/abs/2406.16778) 2024-06-24  
Adithya Bhaskar; Alexander Wettig; Dan Friedman; Danqi Chen



- **Unlocking the Future: Exploring Look-Ahead Planning Mechanistic Interpretability in Large Language Models** [[paper link]](http://arxiv.org/abs/2406.16033) 2024-06-23  
Tianyi Men; Pengfei Cao; Zhuoran Jin; Yubo Chen; Kang Liu; Jun Zhao



- **Insights into LLM Long-Context Failures: When Transformers Know but Don't Tell** [[paper link]](http://arxiv.org/abs/2406.14673) 2024-06-20  
Taiming Lu; Muhan Gao; Kuai Yu; Adam Byerly; Daniel Khashabi



- **From RAGs to rich parameters: Probing how language models utilize external knowledge over parametric information for factual queries** [[paper link]](http://arxiv.org/abs/2406.12824) 2024-06-18  
Hitesh Wadhwa; Rahul Seetharaman; Somyaa Aggarwal; Reshmi Ghosh; Samyadeep Basu; Soundararajan Srinivasan; Wenlong Zhao; Shreyas Chaudhari; Ehsan Aghazadeh



- **Refusal in Language Models Is Mediated by a Single Direction** [[paper link]](http://arxiv.org/abs/2406.11717) 2024-06-17  
Andy Arditi; Oscar Obeso; Aaquib Syed; Daniel Paleka; Nina Panickssery; Wes Gurnee; Neel Nanda



- **Talking Heads: Understanding Inter-layer Communication in Transformer Language Models** [[paper link]](http://arxiv.org/abs/2406.09519) 2024-06-13  
Jack Merullo; Carsten Eickhoff; Ellie Pavlick



- **Scaling and evaluating sparse autoencoders** [[paper link]](http://arxiv.org/abs/2406.04093) 2024-06-06  
Leo Gao; Tom Dupré la Tour; Henk Tillman; Gabriel Goh; Rajan Troll; Alec Radford; Ilya Sutskever; Jan Leike; Jeffrey Wu



- **Observable Propagation: Uncovering Feature Vectors in Transformers** [[paper link]](http://arxiv.org/abs/2406.16291) 2024-06-04  
Jacob Dunefsky; Arman Cohan



- **From Neurons to Neutrons: A Case Study in Interpretability** [[paper link]](http://arxiv.org/abs/2405.17425) 2024-05-27  
Ouail Kitouni; Niklas Nolte; Víctor Samuel Pérez-Díaz; Sokratis Trifinopoulos; Mike Williams



- **Mechanistic Interpretability of Binary and Ternary Transformers** [[paper link]](http://arxiv.org/abs/2405.17703) 2024-05-27  
Jason Li



- **InversionView: A General-Purpose Method for Reading Information from Neural Activations** [[paper link]](http://arxiv.org/abs/2405.17653) 2024-05-27  
Xinting Huang; Madhur Panwar; Navin Goyal; Michael Hahn



- **Not All Language Model Features Are Linear** [[paper link]](http://arxiv.org/abs/2405.14860) 2024-05-23  
Joshua Engels; Isaac Liao; Eric J. Michaud; Wes Gurnee; Max Tegmark



- **Attention Mechanisms Don't Learn Additive Models: Rethinking Feature Importance for Transformers** [[paper link]](http://arxiv.org/abs/2405.13536) 2024-05-22  
Tobias Leemann; Alina Fastowski; Felix Pfeiffer; Gjergji Kasneci



- **Sparse Autoencoders Enable Scalable and Reliable Circuit Identification in Language Models** [[paper link]](http://arxiv.org/abs/2405.12522) 2024-05-21  
Charles O'Neill; Thang Bui



- **Anchored Answers: Unravelling Positional Bias in GPT-2's Multiple-Choice Questions** [[paper link]](https://arxiv.org/abs/2405.03205) 2024-05-06  
Ruizhe Li; Yanjun Gao



- **A Primer on the Inner Workings of Transformer-based Language Models** [[paper link]](https://arxiv.org/abs/2405.00208) 2024-05-02  
Javier Ferrando; Gabriele Sarti; Arianna Bisazza; Marta R. Costa-jussà



- **GiLOT: Interpreting Generative Language Models via Optimal Transport** [[paper link]](https://openreview.net/pdf?id=qKL25sGjxL) 2024-05-02  
Xuhong Li; Jiamin Chen; Yekun Chai; Haoyi Xiong



- **Talking Nonsense: Probing Large Language Models' Understanding of Adversarial Gibberish Inputs** [[paper link]](http://arxiv.org/abs/2404.17120) 2024-04-25  
Valeriia Cherepanova; James Zou



- **Interpreting Context Look-ups in Transformers: Investigating Attention-MLP Interactions** [[paper link]](http://arxiv.org/abs/2402.15055) 2024-02-22  
Clement Neo; Shay B. Cohen; Fazl Barez



- **Universal Neurons in GPT2 Language Models** [[paper link]](http://arxiv.org/abs/2401.12181) 2024-01-22  
Wes Gurnee; Theo Horsley; Zifan Carl Guo; Tara Rezaei Kheirkhah; Qinyi Sun; Will Hathaway; Neel Nanda; Dimitris Bertsimas



- **Interpretability Illusions in the Generalization of Simplified Models** [[paper link]](http://arxiv.org/abs/2312.03656) 2023-12-06  
Dan Friedman; Andrew Lampinen; Lucas Dixon; Danqi Chen; Asma Ghandeharioun



- **Transformers are uninterpretable with myopic methods: a case study with bounded Dyck grammars** [[paper link]](http://arxiv.org/abs/2312.01429) 2023-12-03  
Kaiyue Wen; Yuchen Li; Bingbin Liu; Andrej Risteski



- **White-Box Transformers via Sparse Rate Reduction: Compression Is All There Is?** [[paper link]](https://arxiv.org/abs/2311.13110v2) 2023-11-22  
Yaodong Yu; Sam Buchanan; Druv Pai; Tianzhe Chu; Ziyang Wu; Shengbang Tong; Hao Bai; Yuexiang Zhai; Benjamin D. Haeffele; Yi Ma



- **Mechanistically analyzing the effects of fine-tuning on procedurally defined tasks** [[paper link]](http://arxiv.org/abs/2311.12786) 2023-11-21  
Samyak Jain; Robert Kirk; Ekdeep Singh Lubana; Robert P. Dick; Hidenori Tanaka; Edward Grefenstette; Tim Rocktäschel; David Scott Krueger



- **Understanding the Mechanics and Dynamics of Memorisation in Large Language Models: A Case Study with Random Strings** [[paper link]](https://openreview.net/forum?id=ILStlRb1Sp) 2023-10-13  
Till Speicher; Aflah Mohammad Khan; Qinyuan Wu; Vedant Nanda; Soumi Das; Bishwamittra Ghosh; Krishna P. Gummadi; Evimaria Terzi

</details>


## **Miscellanea**

**[`^        back to top        ^`](#awesome-language-model-analysis-)**

Categories for papers that do not fit neatly into other classifications but discuss theoretical or empirical aspects of language models.


<details open>
<summary><em>paper list (click to fold / unfold)</em></summary>
<br>

- **An In-depth Investigation of Sparse Rate Reduction in Transformer-like Models** [[paper link]](http://arxiv.org/abs/2411.17182) 2024-11-26  
Yunzhe Hu; Difan Zou; Dong Xu



- **On the goals of linguistic theory: Revisiting Chomskyan theories in the era of AI** [[paper link]](http://arxiv.org/abs/2411.10533) 2024-11-15  
Eva Portelance; Masoud Jasbi



- **Length-Induced Embedding Collapse in Transformer-based Models** [[paper link]](http://arxiv.org/abs/2410.24200) 2024-10-31  
Yuqi Zhou; Sunhao Dai; Zhanshuo Cao; Xiao Zhang; Jun Xu



- **Analyzing & Reducing the Need for Learning Rate Warmup in GPT Training** [[paper link]](http://arxiv.org/abs/2410.23922) 2024-10-31  
Atli Kosson; Bettina Messmer; Martin Jaggi



- **A Theoretical Perspective for Speculative Decoding Algorithm** [[paper link]](http://arxiv.org/abs/2411.00841) 2024-10-30  
Ming Yin; Minshuo Chen; Kaixuan Huang; Mengdi Wang



- **Inevitable Trade-off between Watermark Strength and Speculative Sampling Efficiency for Language Models** [[paper link]](http://arxiv.org/abs/2410.20418) 2024-10-27  
Zhengmian Hu; Heng Huang



- **Optimizing Attention with Mirror Descent: Generalized Max-Margin Token Selection** [[paper link]](http://arxiv.org/abs/2410.14581) 2024-10-18  
Aaron Alvarado Kristanto Julistiono; Davoud Ataee Tarzanagh; Navid Azizan



- **Fine-grained Attention I/O Complexity: Comprehensive Analysis for Backward Passes** [[paper link]](http://arxiv.org/abs/2410.09397) 2024-10-12  
Xiaoyu Li; Yingyu Liang; Zhenmei Shi; Zhao Song; Yufa Zhou



- **Mind the Gap: a Spectral Analysis of Rank Collapse and Signal Propagation in Transformers** [[paper link]](http://arxiv.org/abs/2410.07799) 2024-10-10  
Alireza Naderi; Thiziri Nait Saada; Jared Tanner



- **Dynamic metastability in the self-attention model** [[paper link]](http://arxiv.org/abs/2410.06833) 2024-10-09  
Borjan Geshkovski; Hugo Koubbi; Yury Polyanskiy; Philippe Rigollet



- **Decoding Game: On Minimax Optimality of Heuristic Text Generation Strategies** [[paper link]](http://arxiv.org/abs/2410.03968) 2024-10-04  
Sijin Chen; Omar Hagrass; Jason M. Klusowski



- **How to Train Long-Context Language Models (Effectively)** [[paper link]](http://arxiv.org/abs/2410.02660) 2024-10-03  
Tianyu Gao; Alexander Wettig; Howard Yen; Danqi Chen



- **softmax is not enough (for sharp out-of-distribution)** [[paper link]](http://arxiv.org/abs/2410.01104) 2024-10-01  
Petar Veličković; Christos Perivolaropoulos; Federico Barbero; Razvan Pascanu



- **On the Implicit Relation Between Low-Rank Adaptation and Differential Privacy** [[paper link]](http://arxiv.org/abs/2409.17538) 2024-09-26  
Saber Malekmohammadi; Golnoosh Farnadi



- **A Controlled Study on Long Context Extension and Generalization in LLMs** [[paper link]](http://arxiv.org/abs/2409.12181) 2024-09-18  
Yi Lu; Jing Nathan Yan; Songlin Yang; Justin T. Chiu; Siyu Ren; Fei Yuan; Wenting Zhao; Zhiyong Wu; Alexander M. Rush



- **Beyond Parameter Count: Implicit Bias in Soft Mixture of Experts** [[paper link]](http://arxiv.org/abs/2409.00879) 2024-09-02  
Youngseog Chung; Dhruv Malik; Jeff Schneider; Yuanzhi Li; Aarti Singh



- **Reframing Data Value for Large Language Models Through the Lens of Plausability** [[paper link]](http://arxiv.org/abs/2409.00284) 2024-08-30  
Mohamad Rida Rammal; Ruida Zhou; Suhas Diggavi



- **Multi-Layer Transformers Gradient Can be Approximated in Almost Linear Time** [[paper link]](http://arxiv.org/abs/2408.13233) 2024-08-23  
Yingyu Liang; Zhizhou Sha; Zhenmei Shi; Zhao Song; Yufa Zhou



- **A Tighter Complexity Analysis of SparseGPT** [[paper link]](http://arxiv.org/abs/2408.12151) 2024-08-22  
Xiaoyu Li; Yingyu Liang; Zhenmei Shi; Zhao Song



- **Great Memory, Shallow Reasoning: Limits of kNN-LMs** [[paper link]](http://arxiv.org/abs/2408.11815) 2024-08-21  
Shangyi Geng; Wenting Zhao; Alexander M Rush



- **Learning Randomized Algorithms with Transformers** [[paper link]](http://arxiv.org/abs/2408.10818) 2024-08-20  
Johannes von Oswald; Seijin Kobayashi; Yassir Akram; Angelika Steger



- **Language Models as Models of Language** [[paper link]](http://arxiv.org/abs/2408.07144) 2024-08-13  
Raphaël Millière



- **Enhancing Exploratory Learning through Exploratory Search with the Emergence of Large Language Models** [[paper link]](http://arxiv.org/abs/2408.08894) 2024-08-09  
Yiming Luo; Patrick Cheong-Iao; Shanton Chang



- **Data Debugging is NP-hard for Classifiers Trained with SGD** [[paper link]](http://arxiv.org/abs/2408.01365) 2024-08-02  
Zizheng Guo; Pengyu Chen; Yanzhang Fu; Dongjing Miao



- **Dancing in Chains: Reconciling Instruction Following and Faithfulness in Language Models** [[paper link]](http://arxiv.org/abs/2407.21417) 2024-07-31  
Zhengxuan Wu; Yuhao Zhang; Peng Qi; Yumo Xu; Rujun Han; Yian Zhang; Jifan Chen; Bonan Min; Zhiheng Huang



- **On the Benefits of Rank in Attention Layers** [[paper link]](http://arxiv.org/abs/2407.16153) 2024-07-23  
Noah Amsel; Gilad Yehudai; Joan Bruna



- **Fundamental Limits of Prompt Compression: A Rate-Distortion Framework for Black-Box Language Models** [[paper link]](http://arxiv.org/abs/2407.15504) 2024-07-22  
Adway Girish; Alliot Nagle; Marco Bondaschi; Michael Gastpar; Ashok Vardhan Makkuva; Hyeji Kim



- **In-Context Probing Approximates Influence Function for Data Valuation** [[paper link]](http://arxiv.org/abs/2407.12259) 2024-07-17  
Cathy Jiao; Gary Gao; Chenyan Xiong



- **On Initialization of Transformers with Pre-trained Embeddings** [[paper link]](http://arxiv.org/abs/2407.12514) 2024-07-17  
Ha Young Kim; Niranjan Balasubramanian; Byungkon Kang



- **On Exact Bit-level Reversible Transformers Without Changing Architectures** [[paper link]](http://arxiv.org/abs/2407.09093) 2024-07-12  
Guoqiang Zhang; J.P. Lewis; W. B. Kleijn



- **Implicit Geometry of Next-token Prediction: From Language Sparsity Patterns to Model Representations** [[paper link]](http://openreview.net/pdf?id=qyilOnIRHI) 2024-07-10  
Yize Zhao; Tina Behnia; Vala Vakilian; Christos Thrampoulidis



- **Universal Length Generalization with Turing Programs** [[paper link]](http://arxiv.org/abs/2407.03310) 2024-07-03  
Kaiying Hou; David Brandfonbrener; Sham Kakade; Samy Jelassi; Eran Malach



- **Efficient Training of Language Models with Compact and Consistent Next Token Distributions** [[paper link]](http://arxiv.org/abs/2407.02819) 2024-07-03  
Ashutosh Sathe; Sunita Sarawagi



- **Understanding Transformers via N-gram Statistics** [[paper link]](http://arxiv.org/abs/2407.12034) 2024-06-30  
Timothy Nguyen



- **Evaluating n-Gram Novelty of Language Models Using Rusty-DAWG** [[paper link]](http://arxiv.org/abs/2406.13069) 2024-06-25  
William Merrill; Noah A. Smith; Yanai Elazar



- **A Text is Worth Several Tokens: Text Embedding from LLMs Secretly Aligns Well with The Key Tokens** [[paper link]](http://arxiv.org/abs/2406.17378) 2024-06-25  
Zhijie Nie; Richong Zhang; Zhanyu Wu



- **Connecting the Dots: LLMs can Infer and Verbalize Latent Structure from Disparate Training Data** [[paper link]](http://arxiv.org/abs/2406.14546) 2024-06-20  
Johannes Treutlein; Dami Choi; Jan Betley; Cem Anil; Samuel Marks; Roger Baker Grosse; Owain Evans



- **Demystifying Forgetting in Language Model Fine-Tuning with Statistical Analysis of Example Associations** [[paper link]](http://arxiv.org/abs/2406.14026) 2024-06-20  
Xisen Jin; Xiang Ren



- **On Layer-wise Representation Similarity: Application for Multi-Exit Models with a Single Classifier** [[paper link]](http://arxiv.org/abs/2406.14479) 2024-06-20  
Jiachen Jiang; Jinxin Zhou; Zhihui Zhu



- **How to Compute the Probability of a Word** [[paper link]](http://arxiv.org/abs/2406.14561) 2024-06-20  
Tiago Pimentel; Clara Meister



- **Toward Infinite-Long Prefix in Transformer** [[paper link]](http://arxiv.org/abs/2406.14036) 2024-06-20  
Jiuxiang Gu; Yingyu Liang; Zhenmei Shi; Zhao Song; Chiwun Yang



- **Unveiling the Hidden Structure of Self-Attention via Kernel Principal Component Analysis** [[paper link]](http://arxiv.org/abs/2406.13762) 2024-06-19  
Rachel S.Y. Teo; Tan M. Nguyen



- **Textual Unlearning Gives a False Sense of Unlearning** [[paper link]](http://arxiv.org/abs/2406.13348) 2024-06-19  
Jiacheng Du; Zhibo Wang; Kui Ren



- **Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters** [[paper link]](http://arxiv.org/abs/2406.12335) 2024-06-18  
Zhiyu Guo; Hidetaka Kamigaito; Taro Watanabe



- **Exploring the Impact of a Transformer's Latent Space Geometry on Downstream Task Performance** [[paper link]](http://arxiv.org/abs/2406.12159) 2024-06-18  
Anna C. Marbut; John W. Chandler; Travis J. Wheeler



- **Understanding Jailbreak Success: A Study of Latent Space Dynamics in Large Language Models** [[paper link]](http://arxiv.org/abs/2406.09289) 2024-06-13  
Sarah Ball; Frauke Kreuter; Nina Rimsky



- **Interpretability of Language Models via Task Spaces** [[paper link]](http://arxiv.org/abs/2406.06441) 2024-06-10  
Lucas Weber; Jaap Jumelet; Elia Bruni; Dieuwke Hupkes



- **How Alignment and Jailbreak Work: Explain LLM Safety through Intermediate Hidden States** [[paper link]](http://arxiv.org/abs/2406.05644) 2024-06-09  
Zhenhong Zhou; Haiyang Yu; Xinghua Zhang; Rongwu Xu; Fei Huang; Yongbin Li



- **Attention as a Hypernetwork** [[paper link]](http://arxiv.org/abs/2406.05816) 2024-06-09  
Simon Schug; Seijin Kobayashi; Yassir Akram; João Sacramento; Razvan Pascanu



- **Verbalized Machine Learning: Revisiting Machine Learning with Language Models** [[paper link]](http://arxiv.org/abs/2406.04344) 2024-06-06  
Tim Z. Xiao; Robert Bamler; Bernhard Schölkopf; Weiyang Liu



- **Local to Global: Learning Dynamics and Effect of Initialization for Transformers** [[paper link]](http://arxiv.org/abs/2406.03072) 2024-06-05  
Ashok Vardhan Makkuva; Marco Bondaschi; Chanakya Ekbote; Adway Girish; Alliot Nagle; Hyeji Kim; Michael Gastpar



- **Pre-trained Large Language Models Use Fourier Features to Compute Addition** [[paper link]](http://arxiv.org/abs/2406.03445) 2024-06-05  
Tianyi Zhou; Deqing Fu; Vatsal Sharan; Robin Jia



- **Computational Limits of Low-Rank Adaptation (LoRA) for Transformer-Based Models** [[paper link]](http://arxiv.org/abs/2406.03136) 2024-06-05  
Jerry Yao-Chieh Hu; Maojiang Su; En-Jui Kuo; Zhao Song; Han Liu



- **Rethinking Spiking Neural Networks as State Space Models** [[paper link]](http://arxiv.org/abs/2406.02923) 2024-06-05  
Malyaban Bal; Abhronil Sengupta



- **LongSSM: On the Length Extension of State-space Models in Language Modelling** [[paper link]](http://arxiv.org/abs/2406.02080) 2024-06-04  
Shida Wang



- **On Affine Homotopy between Language Encoders** [[paper link]](http://arxiv.org/abs/2406.02329) 2024-06-04  
Robin SM Chan; Reda Boumasmoud; Anej Svete; Yuxin Ren; Qipeng Guo; Zhijing Jin; Shauli Ravfogel; Mrinmaya Sachan; Bernhard Schölkopf; Mennatallah El-Assady; Ryan Cotterell



- **Anisotropy is Not Inherent to Transformers** [[paper link]](https://aclanthology.org/2024.naacl-long.274) 2024-06  
Anemily Machina; Robert Mercer



- **A Theory of In-Context Learning in Transformers** [[paper link]](http://arxiv.org/abs/2405.18634) 2024-05-29  
Yifei Wang; Yuyang Wu; Zeming Wei; Stefanie Jegelka; Yisen Wang



- **Lower Bounds on the Expressivity of Recurrent Neural Language Models** [[paper link]](http://arxiv.org/abs/2405.19222) 2024-05-29  
Anej Svete; Franz Nowak; Anisha Mohamed Sahabdeen; Ryan Cotterell



- **Demystifying amortized causal discovery with transformers** [[paper link]](http://arxiv.org/abs/2405.16924) 2024-05-27  
Francesco Montagna; Max Cairney-Leeming; Dhanya Sridhar; Francesco Locatello



- **Unlocking the Secrets of Linear Complexity Sequence Model from A Unified Perspective** [[paper link]](http://arxiv.org/abs/2405.17383) 2024-05-27  
Zhen Qin; Xuyang Shen; Dong Li; Weigao Sun; Stan Birchfield; Richard Hartley; Yiran Zhong



- **Can Large Language Models Faithfully Express Their Intrinsic Uncertainty in Words?** [[paper link]](http://arxiv.org/abs/2405.16908) 2024-05-27  
Gal Yona; Roee Aharoni; Mor Geva



- **Towards Understanding How Transformer Perform Multi-step Reasoning with Matching Operation** [[paper link]](http://arxiv.org/abs/2405.15302) 2024-05-24  
Zhiwei Wang; Yunji Wang; Zhongwang Zhang; Zhangchen Zhou; Hui Jin; Tianyang Hu; Jiacheng Sun; Zhenguo Li; Yaoyu Zhang; Zhi-Qin John Xu



- **Dissecting the Interplay of Attention Paths in a Statistical Mechanics Theory of Transformers** [[paper link]](http://arxiv.org/abs/2405.15926) 2024-05-24  
Lorenzo Tiberi; Francesca Mignacco; Kazuki Irie; Haim Sompolinsky



- **Attention as an RNN** [[paper link]](http://arxiv.org/abs/2405.13956) 2024-05-22  
Leo Feng; Frederick Tung; Hossein Hajimirsadeghi; Mohamed Osama Ahmed; Yoshua Bengio; Greg Mori



- **Surgical Feature-Space Decomposition of LLMs: Why, When and How?** [[paper link]](http://arxiv.org/abs/2405.13039) 2024-05-17  
Arnav Chavan; Nahush Lele; Deepak Gupta



- **Dynamic Activation Pitfalls in LLaMA Models: An Empirical Study** [[paper link]](http://arxiv.org/abs/2405.09274) 2024-05-15  
Chi Ma; Mincong Huang; Chao Wang; Yujie Wang; Lei Yu



- **Challenges in Deploying Long-Context Transformers: A Theoretical Peak Performance Analysis** [[paper link]](http://arxiv.org/abs/2405.08944) 2024-05-14  
Yao Fu



- **Understand LLMs Requires More Than Statistical Generalization** [[paper link]](http://arxiv.org/abs/2405.01964) 2024-05-03  
Patrik Reizinger; Szilvia Ujváry; Anna Mészáros; Anna Kerekes; Wieland Brendel; Ferenc Huszár



- **Viewing Transformers Through the Lens of Long Convolutions Layers** [[paper link]](http://openreview.net/pdf?id=nOyj26YdIQ) 2024-05-02  
Itamar Zimerman; Lior Wolf



- **Modeling Language Tokens as Functionals of Semantic Fields** [[paper link]](http://openreview.net/pdf?id=EEO4Iktfjp) 2024-05-02  
Zhengqi Pei; Anran Zhang; Shuhui Wang; Qingming Huang



- **Compression Represents Intelligence Linearly** [[paper link]](http://arxiv.org/abs/2404.09937) 2024-04-15  
Yuzhen Huang; Jinghan Zhang; Zifei Shan; Junxian He



- **Language Generation in the Limit** [[paper link]](http://arxiv.org/abs/2404.06757) 2024-04-10  
Jon Kleinberg; Sendhil Mullainathan



- **Do language models plan ahead for future tokens?** [[paper link]](http://arxiv.org/abs/2404.00859) 2024-03-31  
Wilson Wu; John X. Morris; Lionel Levine



- **What's In My Big Data?** [[paper link]](http://arxiv.org/abs/2310.20707) 2024-03-05  
Yanai Elazar; Akshita Bhagia; Ian Magnusson; Abhilasha Ravichander; Dustin Schwenk; Alane Suhr; Pete Walsh; Dirk Groeneveld; Luca Soldaini; Sameer Singh; Hanna Hajishirzi; Noah A. Smith; Jesse Dodge



- **Do Efficient Transformers Really Save Computation?** [[paper link]](http://arxiv.org/abs/2402.13934) 2024-02-21  
Kai Yang; Jan Ackermann; Zhenyu He; Guhao Feng; Bohang Zhang; Yunzhen Feng; Qiwei Ye; Di He; Liwei Wang



- **Long Is More for Alignment: A Simple but Tough-to-Beat Baseline for Instruction Fine-Tuning** [[paper link]](http://arxiv.org/abs/2402.04833) 2024-02-07  
Hao Zhao; Maksym Andriushchenko; Francesco Croce; Nicolas Flammarion



- **Provably learning a multi-head attention layer** [[paper link]](http://arxiv.org/abs/2402.04084) 2024-02-06  
Sitan Chen; Yuanzhi Li



- **Anisotropy Is Inherent to Self-Attention in Transformers** [[paper link]](http://arxiv.org/abs/2406.12143) 2024-01-24  
Nathan Godey; Éric de la Clergerie; Benoît Sagot



- **Universality and Limitations of Prompt Tuning** [[paper link]](http://arxiv.org/abs/2305.18787) 2023-11-16  
Yihan Wang; Jatin Chauhan; Wei Wang; Cho-Jui Hsieh



- **Data Similarity is Not Enough to Explain Language Model Performance** [[paper link]](http://arxiv.org/abs/2311.09006) 2023-11-15  
Gregory Yauney; Emily Reif; David Mimno



- **Simplifying Transformer Blocks** [[paper link]](http://arxiv.org/abs/2311.01906) 2023-11-03  
Bobby He; Thomas Hofmann



- **Causal Interpretation of Self-Attention in Pre-Trained Transformers** [[paper link]](http://arxiv.org/abs/2310.20307) 2023-10-31  
Raanan Y. Rohekar; Yaniv Gurwicz; Shami Nisimov



- **How do Language Models Bind Entities in Context?** [[paper link]](http://arxiv.org/abs/2310.17191) 2023-10-26  
Jiahai Feng; Jacob Steinhardt



- **Understanding prompt engineering may not require rethinking generalization** [[paper link]](https://openreview.net/forum?id=a745RnSFLT) 2023-10-13  
Victor Akinwande; Yiding Jiang; Dylan Sam; J. Zico Kolter



- **Understanding Catastrophic Forgetting in Language Models via Implicit Inference** [[paper link]](http://arxiv.org/abs/2309.10105) 2023-09-18  
Suhas Kotha; Jacob Mitchell Springer; Aditi Raghunathan



- **Attention-Only Transformers and Implementing MLPs with Attention Heads** [[paper link]](http://arxiv.org/abs/2309.08593) 2023-09-15  
Robert Huben; Valerie Morris



- **On the Role of Attention in Prompt-tuning** [[paper link]](https://openreview.net/forum?id=qorOnDor89) 2023-06-15  
Samet Oymak; Ankit Singh Rawat; Mahdi Soltanolkotabi; Christos Thrampoulidis

</details>




---

**Detailed Statistics**

- Phenomena of Interest:

  - In-Context Learning: *95*

  - Chain-of-Thought: *17*

  - Hallucination: *10*

  - Reversal Curse: *5*

  - Scaling Laws / Emergent Abilities / Grokking / etc.: *52*

  - Knowledge / Memory Mechanisms: *30*

  - Training Dynamics / Landscape / Optimization / Fine-tuning / etc.: *55*

  - Learning / Generalization / Reasoning / Weak to Strong Generalization: *58*

  - Other Phenomena / Discoveries: *32*

- Representational Capacity:

  - What Can Transformer Do? / Properties of Transformer: *71*

  - What Can Transformer Not Do? / Limitation of Transformer: *27*

- Architectural Effectivity:

  - Layer-normalization: *6*

  - Tokenization / Embedding: *21*

  - Linear Attention / State Space Models / Recurrent Language Models / etc.: *9*

- Training Paradigms: *2*

- Mechanistic Engineering / Probing / Interpretability: *48*

- Miscellanea: *88*



---

Related links:

- [deep-learning-dynamics-paper-list](https://github.com/zeke-xie/deep-learning-dynamics-paper-list)

- [Paper List for In-context Learning](https://github.com/dqxiu/ICL_PaperList)

- [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning)

- [Awesome Math](https://github.com/rossant/awesome-math)

- [Awesome TikZ](https://github.com/xiaohanyu/awesome-tikz)

- [Awesome Lists for Tenure-Track Asst. Professors and PhD students](https://github.com/JunweiLiang/awesome_lists)

- [Awesome LLM Systems Papers](https://github.com/AmberLJC/LLMSys-PaperList)

- [Neural Tangent Kernel Papers](https://github.com/kwignb/NeuralTangentKernel-Papers)

- [Feature Learning in Deep Learning Theory Reading Group](https://github.com/WeiHuang05/Awesome-Feature-Learning-in-Deep-Learning-Thoery)

- [awesome-matplotlib](https://github.com/interactivetech/awesome-matplotlib)

- [LLM Training Puzzles](https://github.com/srush/LLM-Training-Puzzles)

- [Scientific Visualization: Python + Matplotlib](https://github.com/rougier/scientific-visualization-book)

- [A PyTorch Tools, best practices & Styleguide](https://github.com/IgorSusmelj/pytorch-styleguide)

- [Deep Learning Tuning Playbook](https://github.com/google-research/tuning_playbook)

- [Science Plots](https://github.com/garrettj403/SciencePlots)

- [Tips and Tricks for Writing Scientific Papers](https://github.com/Wookai/paper-tips-and-tricks)

- [Paper Writing Tips](https://github.com/MLNLP-World/Paper-Writing-Tips)

---

**Contact**

- [Shiguang Wu](https://furyton.github.io), furyton AT outlook.com / shiguang.wu AT mail.sdu.edu.cn