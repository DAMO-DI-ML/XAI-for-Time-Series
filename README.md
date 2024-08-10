# XAI for Time Series
This is a hub for our team dedicated to explainable AI (XAI) for time series, providing valuable resources and insights to enhance understanding and application in this critical field.

**We are hiring!** 
- Research Interns: We are currently looking for passionate graduate students to join our team as interns! We also If you are interested in contributing to the field of explainable AI for time series and making a meaningful impact, check out our [job openings](https://talent-holding.alibaba.com/campus/position-detail?lang=zh&positionId=2035202) 
- Alibaba Innovative Research: We are actively seeking professors for exciting collaboration opportunities! This one-year project focuses on explainable AI (XAI) in time-series scenarios. Professors can send 1-2 interns to join our team, enhancing their academic experience while contributing to meaningful research. You may refer to more details at the [official website](https://damo.alibaba.com/air?language=zh).

If you are interested in exploring these opportunity, please reach out to us at [guxinyue.gxy@alibaba-inc.com] or [linxiao.ylx@alibaba-inc.com]. Let's work together to push the boundaries of XAI!

## Table of Contents
- [Team Members](#team-members)
- [Research Contributions](#research-contributions)
- [Resources](#resources)

## Our XAI Team: Fostering understanding between people and machines.

### Team Members
- **YANG, Linxiao**: [linxiao.ylx@alibaba-inc.com]Always the core idea contributor in XAI for time series, interactive XAI and rule learning.
- **GENG, Linyuan**: [genglinyuan.gly@alibaba-inc.com] Statistics expert, focusing on self-learning to enhance temporal model performance.
- **GU, Xinyue**: [guxinyue.gxy@alibaba-inc.com] Working on statistics, operations and causal inference; a theoretical proof provider.
  
### Selected research
- **Explain Temporal Black-Box Models via Functional Decomposition**:
<img width="1563" alt="image" src="https://github.com/user-attachments/assets/a95caa0b-b9f5-413b-81d2-c1984811da6e">
How to explain temporal models is a significant challenge due to the inherent characteristics of time series data, notably the strong temporal dependencies and interactions between observations.

The unique characters of time series data： 
1，the high degree of temporal dependency (including the commonly used autocorrelation) inherent in time series data complicates the task of identifying the influence of specific inputs on the model outputs. 
2，events occurring at a given time point can have enduring effects on subsequent observations, encapsulating phase shifts that ripple through future data points. 
3，we need to consider not only a single time point (e.g., points corresponding to events), but also time series subsequence in explanation. 

cite this: `@inproceedings{yang2024explain,
  title={Explain Temporal Black-Box Models via Functional Decomposition},
  author={Yang, Linxiao and Tong, Yunze and Gu, Xinyue and Sun, Liang},
  booktitle={International Conference on Machine Learning},
  year={2024},
  organization={PMLR}
}`
- **Interactive Generalized Additive Model and Its Applications in Electric Load Forecasting**:
  <img width="1708" alt="image" src="https://github.com/user-attachments/assets/8f5249d6-2b72-42ea-a4e5-637de53c532e">
<img width="1692" alt="image" src="https://github.com/user-attachments/assets/0e0691d7-439e-44d5-bc84-4c3cc1f4cf4a">
<img width="1692" alt="image" src="https://github.com/user-attachments/assets/4b04270c-a694-49c5-a536-e3be41a0971a">

Inaccurate load forecasting may lead to the threat of outages or a waste of energy. How to give accurate electric load forecasting when there is
1. limited data or even no data, such as load forecasting in holiday, or under extreme weather conditions.
2. a need for model interpretability as high-stakes decision-making usually follows after load forecasting.

We propose an interactive GAM which is not only interpretable but also can incorporate specific domain knowledge in electric power industry for improved performance.

cite this: `@inproceedings{yang2023interactive,
  title={Interactive Generalized Additive Model and Its Applications in Electric Load Forecasting},
  author={Yang, Linxiao and Ren, Rui and Gu, Xinyue and Sun, Liang},
  booktitle={Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={5393--5403},
  year={2023}
}`
- **Learning Interpretable Decision Rule Sets: A Submodular Optimization Approach**:
<img width="312" alt="image" src="https://github.com/user-attachments/assets/e3e4ae15-0c42-4ab8-8f86-c4791d1f537f">

Rule sets are highly interpretable logical models in which the predicates for decision are expressed in disjunctive normal form (DNF, OR-of-ANDs). We consider a submodular optimization based approach to form an accurate and interpretable rule set. the proposed approach is simple, scalable, and can deal with the exponential-sized ground set of rules.

cite this: `@inproceedings{yang2021learning,
  title={Learning interpretable decision rule sets: A submodular optimization approach},
  author={Yang, Fan and He, Kai and Yang, Linxiao and Du, Hongxia and Yang, Jingbang and Yang, Bo and Sun, Liang},
  booktitle={Advances in Neural Information Processing Systems},
  volume={34},
  pages={27890--27902},
  year={2021}
}`
## Resources of XAI for Time Series
- **Mask or Perturbation**:
  - [Explaining time series predictions with dynamic masks](https://arxiv.org/abs/2106.05303)  Jonathan Crabb ́e and Mihaela van der Schaar. ICML'21
  - [Learning perturbations to explain time series predictions]( https://arxiv.org/abs/2305.18840) Joseph Enguehard. ICML'23
  - [Explaining time series via contrastive and locally sparse perturbations]( https://arxiv.org/abs/2401.08552)] Zichuan Liu, Yingying Zhang, Tianchuan Wang, Zefan Wang, Dongsheng Luo, Menguan Du, Min Wu, Yi Wang, Chunlin Chen, Lunting Fan, and Qingsong Wen. ICLR'24
- **Distribution-aware**:
  - [What went wrong and when? instance-wise feature importance for time-series black-box models]( https://arxiv.org/abs/2003.02821) Sana Tonekaboni, Shalmali Joshi, Kieran R Campbell, David Duvenaud, and Anna Goldenberg. In Proceedings of the International Conference on Neural Information Processing Systems, volume 33, pages 799–809.2020
  - [Temporal dependencies in feature importance for time series prediction](https://arxiv.org/abs/2107.14317) Kin Kwan Leung, Clayton Rooke, Jonathan Smith, Saba Zuberi, and Maksims Volkovs. In The International Conference on Learning Representations, 2023.
  - [Feature importance identification for time series classifiers](https://ieeexplore.ieee.org/document/9945205) Han Meng, Christian Wagner, and Isaac Triguero. In IEEE International Conference on Systems, Man, and Cybernetics, pages 3293–3298, 2022
- **SHAP/LIME-based**:
  - [Feature importance for time series data: Improving kernelshap]( https://arxiv.org/abs/2210.02176) Mattia Villani, Joshua Lockhart, and Daniele Magazzeni. International Conference on AI in Finance Workshop on Explainable Artificial Intelligence in Finance, 2022.
  - [Interpreting a recurrent neural network’s predictions of icu mortality risk]( https://arxiv.org/abs/1905.09865) Long V. Ho, Melissa Aczon, David Ledbetter, and Randall Wetzel. Journal of Biomedical Informatics, 114(C), 2021
  - [Limesegment: Meaningful, realistic time series explanations](https://proceedings.mlr.press/v151/sivill22a.html) Torty Sivill and Peter Flach. In International Conference on Artificial Intelligence and Statistics, pages 3418-3433, 2022
- **Structural**:
  - [Title of Blog/Tutorial 1](link_to_blog) - Brief description
