# AI派NLP起步指南

## RNN相关：

完成fudan NLP-Beginner任务3-4（选作任务5）

1. 时间：4周
2. 链接：[FudanNLP/nlp-beginner](https://github.com/FudanNLP/nlp-beginner)



## Transformer相关：

### 任务一：bert代码阅读

阅读bert源码，理解模型构建过程，并针对每个函数及你认为重要的关键代码行写上注释。

1. 参考
   1. code: [BERT pytorch ](https://github.com/codertimo/BERT-pytorch)
   2. paper: [Pre-training of Deep Bidirectional Transformers for Language Understanding ](https://arxiv.org/abs/1810.04805)
2. 实现要求：Pytorch
3. 知识点：
   1. multi head self-attention
   2. transformer类模型的预处理流程
4. 时间：两周



### 任务二：基于bert的阅读理解

使用huggingface上的bert基础模型，完成SQuAD数据集上的阅读理解任务。

1. 参考
   1. [Quick tour (huggingface.co)](https://huggingface.co/docs/transformers/quicktour)
2. 数据集：[The Stanford Question Answering Dataset](https://rajpurkar.github.io/SQuAD-explorer/)
3. 实现要求：只需要完成SQuAD v1即可，不要求完成SQuAD v2，过程中禁止直接使用huggingface中在SQuAD数据集上fine-tune好的模型
4. 知识点：
   1. huggingface的使用
   2. fine-tune流程
   3. 阅读理解任务
5. 时间：两周
