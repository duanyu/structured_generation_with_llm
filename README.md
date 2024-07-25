# Structured Generation With LLMs

## Lecture 1

介绍Kor，并用免费的LLM API做练习。

Kor本质上是对LLM的一层“封装”，只做了 组装prompt 和 解析output 两个工作，是非常初级的结构化输出方案。

初级性体现在：Kor无法保证结构化输出的稳定性。

## Lecture 2

介绍如何将Function/Tool Calling功能用于structured generation。

FC经过了LLM厂商的fine-tuning，稳定性可能比Kor更有保障。但是，FC仍然不能够“保证”输出结构的稳定性。
