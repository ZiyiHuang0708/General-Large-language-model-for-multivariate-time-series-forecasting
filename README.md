# General Large language model for multivariate time series forecasting

## 时间序列预测的演化史与前沿
时间序列预测在金融市场、交通运输、医疗健康、气象能源等诸多领域具有基础性的作用。例如，通过分析过去的时间序列数据，可以预测股票价格走势、电力负荷需求、患者病情发展或天气变化趋势。长期以来，研究者们提出了多种方法来提高时间序列预测的准确性。从传统的统计建模方法，到基于神经网络的深度学习模型，再到近年来兴起的基础模型（Foundation Models）和大规模预训练模型，时间序列预测技术经历了数次范式演进。本知识库将系统梳理时间序列预测方法针对不同任务从传统统计模型到第一代神经网络、深度学习框架，再到最新的基础大模型和时序大语言模型（Time-Series LLMs）的演变历程，并提供当前研究的两个热点方向：时空数据挖掘专题与多模态专题。目前我们已收集来自KDD、ICML、NeurIPS、ICLR、CVPR、AAAI、WWW、ICDE、IJCAI、IEEE等会议的论文，并持续扩充收录范围。


<details><summary><h2 style="display: inline;"> 传统统计模型 </h2></summary>
早期的时间序列预测主要依赖于统计模型和信号处理方法。这类方法注重利用时间序列的统计规律和结构特点。典型的方法包括：季节-趋势分解（将序列分解为趋势、季节和残差成分）、滑动平均和指数平滑（如霍尔特-温特斯三重指数平滑）用于平滑和短期预测、以及各种自回归模型，例如ARIMA（自回归积分滑动平均模型）及其扩展形式SARIMA（季节性ARIMA）等。这些模型通过捕捉序列的自相关和季节周期性模式，能够在许多单变量预测场景下取得稳健的结果。对于多变量情景，经典方法如VAR（向量自回归模型）可以建模多个时间序列变量之间的相互依赖关系。

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 循环神经网络模型（RNN）</h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 卷积神经网络模型（CNN/TCN） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 前馈神经网络模型（MLP） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 状态空间模型（SSM） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> Transformer 模型 </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 表示学习模型（RL） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 生成模型（GM） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 基础模型（FM） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 大语言模型（LLM） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 时空数据挖掘专题（STF） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 多模态专题（Multi-Modal） </h2></summary>

预测与分类任务（Forecasting or Classification）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

时间序列预测的演化史与前沿综述及参考文献：

A Survey of Deep Learning and Foundation Models for Time Series Forecasting [[link](https://doi.org/10.1145/nnnnnnn.nnnnnnn)]

Foundation Models for Time Series Analysis:A Tutorial and Survey [[link](https://doi.org/10.1145/3637528.3671451)]

Large Models for Time Series and Spatio-Temporal Data: A Survey and Outlook[[link](https://arxiv.org/abs/2310.10196)]

Time-Series Large Language Models:A Systematic Review of State-of-the-Art[[link](https://ieeexplore.ieee.org/iel8/6287639/6514899/10856008.pdf)]
