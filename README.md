# General Large language model for multivariate time series forecasting

## 时间序列预测的演化史与前沿
时间序列预测在金融市场、交通运输、医疗健康、气象能源等诸多领域具有基础性的作用。例如，通过分析过去的时间序列数据，可以预测股票价格走势、电力负荷需求、患者病情发展或天气变化趋势。长期以来，研究者们提出了多种方法来提高时间序列预测的准确性。从传统的统计建模方法，到基于神经网络的深度学习模型，再到近年来兴起的基础模型（Foundation Models）和大规模预训练模型，时间序列预测技术经历了数次范式演进。本知识库将系统梳理时间序列预测方法针对不同任务从传统统计模型到第一代神经网络、深度学习框架，再到最新的基础大模型和时序大语言模型（Time-Series LLMs）的演变历程，并提供当前研究的两个热点方向：时空数据挖掘专题与多模态专题。目前我们已收集来自KDD、ICML、NeurIPS、ICLR、CVPR、AAAI、WWW、ICDE、IJCAI、IEEE等会议的论文，并持续扩充收录范围。

<details><summary><h2 style="display: inline;"> 传统统计模型 </h2></summary>
传统统计模型主要依赖于统计模型和信号处理方法。这类方法注重利用时间序列的统计规律和结构特点，通过捕捉序列的自相关和季节周期性模式，能够在许多单变量或多变量预测场景下取得稳健的结果。典型的方法包括：季节-趋势分解（将序列分解为趋势、季节和残差成分）、滑动平均和指数平滑（如霍尔特-温特斯三重指数平滑）用于平滑和短期预测、以及各种自回归模型，例如VAR（向量自回归模型），ARIMA（自回归积分滑动平均模型）及其扩展形式SARIMA（季节性ARIMA）等。

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

<details><summary><h2 style="display: inline;"> 循环神经网络模型（RNN）</h2></summary>
循环神经网络模型（RNN）通过隐藏状态的循环连接，可以将历史信息编码到隐藏状态中，从而在任意长的序列上累积记忆。典型的方法包括：长短期记忆网络（LSTM）和门控循环单元（GRU）等。

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
卷积神经网络模型（CNN/TCN）同样被用于时间序列建模。传统CNN通过滑动卷积核可以提取序列中的局部模式，一定程度上捕获短期依赖关系。而时间卷积网络（TCN）在CNN基础上引入因果卷积（保证卷积时刻不窥视未来信息）和扩张卷积（Dilated CNN，可扩展感受野以覆盖较长历史）以及残差连接，从而能够在无递归的情况下建模长期依赖。典型的方法包括：卷积神经网络（CNN）、时间卷积网络（TCN）等。

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
Transformer模型是一种完全基于注意力而摒弃循环结构的Seq2Seq架构。Transformer由多个编码和解码层堆叠而成，每一层主要包含自注意力（Self-Attention）和前馈网络两部分，并通过残差连接和归一化保证稳定训练。典型的方法包括：Informer、FEDformer、Autoformer等等

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

<details><summary><h2 style="display: inline;"> 基础模型（FMs） </h2></summary>
基础模型通常指在海量数据上训练的、具有通用能力的大规模深度模型，例如NLP领域的GPT系列、BERT等语言模型，或CV领域的ViT、CLIP等视觉模型。其显著特点是在预训练阶段学到了广泛的特征表示和知识，可通过微调或提示学习等方式快速适配下游任务。时间序列基础模型（TSFMs）指专门面向时间序列数据训练的大模型。类似于NLP中的预训练语言模型，TSFMs旨在跨领域地学习通用的时序模式，从而可以一次训练服务于多种下游时序任务。理想情况下，TSFM经过大规模预训练后，能够掌握各种序列的共性模式，然后通过少量新数据微调或甚至直接零样本应用，在特定任务上取得优异表现。典型的主流方法包括：TimeGPT、TimeMoE、TimesFM等

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
当前在“时间序列大模型”方向，大致有两类研究思路：其一是面向特定领域的大规模预训练模型，其二是将通用大语言模型（LLM）适配到时间序列任务。第一类包括一些领域时间序列基础模型的探索。第二类思路是将已有的大语言模型用于时间序列分析。其中一种方法是提示学习（Prompting）：即将时间序列数据转化为一定格式的文本或离散符号串，作为提示输入通用LLM，让其完成续写或分类任务。另一类方法是微调大语言模型用于时序任务。典型的主流方法包括：Time-LLM、AnomalyLLM等。

预测与分类任务（Forecasting or Classification
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

异常检测任务（Anomaly Detection）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----
| 01-24 | [AnomalyLLM](https://arxiv.org/pdf/2401.15123) | ![multivariate time series forecasting](https://img.shields.io/badge/-Multivariate-red) |IJCAI 2024|Large Language Model Guided Knowledge Distillation for Time Series Anomaly Detection| None |

时序插值与修复任务（Imputation/Recovery）
Date|Method|Type|Conference/Journal|Paper Title and Paper Interpretation|Code
-----|----|-----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;"> 时空数据挖掘专题（STF） </h2></summary>
现实世界的许多时间序列数据带有空间或拓扑结构信息，例如交通流量数据依赖于道路网络拓扑、疫情数据涉及地区之间的传播关系、气象数据有地理空间相关性等。这催生了时空数据挖掘领域的方法研究，即同时建模时间和空间两个维度的依赖关系。图神经网络（GNN）作为近年兴起的处理图结构数据的深度学习模型，被广泛应用于时空预测问题。通过构造节点表示时序变量、边表示变量间关系的时空图，可以将时间序列预测转化为图上的信号演进建模。GNN善于刻画空间上的相关性（如邻近区域流量的关联），而时间维度的依赖则常通过与RNN、CNN或Transformer等时间模型相结合来处理。典型的主流方法包括：DCRNN、Graph WaveNet等。

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
