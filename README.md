# General Large language model for multivariate time series forecasting

时间序列预测的演化史与前沿：时间序列预测在金融市场、交通运输、医疗健康、气象能源等诸多领域具有基础性的作用。例如，通过分析过去的时间序列数据，可以预测股票价格走势、电力负荷需求、患者病情发展或天气变化趋势。长期以来，研究者们提出了多种方法来提高时间序列预测的准确性。从传统的统计建模方法，到基于神经网络的深度学习模型，再到近年来兴起的基础模型（Foundation Models）和大规模预训练模型，时间序列预测技术经历了数次范式演进。传统统计和机器学习方法在许多应用中取得了成功，但在面对高维数据、缺失值以及长期依赖关系时往往力不从心。深度学习技术的兴起为时间序列预测注入了新的活力，能够自动从数据中学习复杂模式。然而，深度模型通常需要大量训练数据，在数据有限的情况下表现不佳。此外，其黑箱性质导致结果难以解释。在此背景下，基础模型（指具有大规模参数并经过广泛预训练的模型）逐渐引入时间序列领域。基础模型有望通过在海量数据上的预训练来获取广泛知识，从而提高小样本条件下的预测能力和泛化性。本知识库将系统梳理时间序列预测方法从传统统计模型到第一代神经网络、深度学习框架，再到最新的基础大模型和时序大语言模型（Time-Series LLMs）的演变历程，并总结当前研究的两个热点方向：时空数据挖掘专题与多模态专题。我们还将比较各类方法针对不同任务的主要特征，例如对数据规模的依赖、零样本预测能力、泛化性及可解释性等，并讨论当前面临的挑战与未来发展方向。


<details><summary><h2 style="display: inline;"> 传统统计模型 </h2></summary>

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
