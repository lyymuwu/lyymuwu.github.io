---
layout: post
title: sequence model
subtitle: 虚拟模型
author: muwu
date: 2021-12-08 21:26:35 +0800
categories: 深度学习
tag: 深度学习
---

# 专业术语

## 第i个训练样本的第t个单词

![image-20211208212753048](2021-12-08-deep-learning-3.assets/image-20211208212753048.png)

![image-20211209165400767](2021-12-08-deep-learning-3.assets/image-20211209165400767.png)

## 第i个训练样本的长度

![image-20211208212824575](2021-12-08-deep-learning-3.assets/image-20211208212824575.png)

## RNN

![image-20211208214718361](2021-12-08-deep-learning-3.assets/image-20211208214718361.png)

## 架构

![image-20211209113352901](2021-12-08-deep-learning-3.assets/image-20211209113352901.png)

## RNN 语言模型

![image-20211209141304097](2021-12-08-deep-learning-3.assets/image-20211209141304097.png)

## GRU

gamma (Γ)表示我们又多大程度想要改变之前的memory cell (C)中存储的值

C等同于上图中RNN计算出的a

![image-20211209144840116](2021-12-08-deep-learning-3.assets/image-20211209144840116.png)

![image-20211209150135536](2021-12-08-deep-learning-3.assets/image-20211209150135536.png)tanh 和 sigmoid中间的式子得到的结果一般很小，负数。

## LSTM

![image-20211209150725302](2021-12-08-deep-learning-3.assets/image-20211209150725302.png)

## 新的训练流程

- forward pass,
- cost computation,
- backward pass,
- (optional) clip, [np.chip()]
- parameter update.



## word2vec

skip-gram: content word with random choice target in a range.





# 疑问

怎么训练语言模型呀？
