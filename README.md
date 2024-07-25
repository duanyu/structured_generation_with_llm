# Structured Generation With LLMs

## Lecture 1

介绍Kor，并用免费的LLM API做练习。

Kor本质上是对LLM的一层“封装”，只做了 组装prompt 和 解析output 两个工作，是非常初级的结构化输出方案。

初级性体现在：Kor无法保证结构化输出的稳定性。

## Lecture 2

介绍如何将Function/Tool Calling功能用于structured generation。

FC经过了LLM厂商的fine-tuning，稳定性“可能”比Kor更有保障；但是，FC仍然不能保证输出结构的稳定性。

还有一个问题：FC在使用few-shot examples上没有Kor方便。

至少在我的实验中，我发现很难给glm-4-flash/air/airx有效加上examples。
