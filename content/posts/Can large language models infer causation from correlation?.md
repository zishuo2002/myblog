+++

date = '2026-05-28T17:26:47+08:00'
draft = true
title = '[文献阅读] Can large language models infer causation from correlation?'

+++

在以往（2024年前）对 LLM 因果推理能力的评测基准大多集中在对**常识因果推理**能力的考察，例如 **COPA**。[^1]

```
COPA 包含了1000道题的常识因果推理题

每道题结构如下：

> **前提**：我敲了邻居的门。结果发生了什么？
>
> - 选项A：邻居邀请我进去。
> - 选项B：邻居离开了家。

题目分两类：

- 正向因果：给原因，选结果
- 逆向因果：给结果，选原因
```

LLM 的常识因果推理能力主要来自于知识先验，高度依赖训练数据的质量和广度，也就是说大型语言模型是一种**“因果鹦鹉”**（Causal parrots），只能背诵训练数据中的因果知识。[^2]











[^1]:Roemmele M, Bejan C A, Gordon A S. Choice of Plausible Alternatives: An Evaluation of Commonsense Causal Reasoning[C]//AAAI spring symposium: logical formalizations of commonsense reasoning. 2011: 90-95.
[^2]: Matej Zecˇevic ́, Moritz Willig, Devendra Singh Dhami, and Kristian Kersting. Causal parrots: Large language models may talk causality but are not causal. arXiv preprint arXiv:2308.13067, 2023. 1

