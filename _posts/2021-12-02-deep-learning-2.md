---
layout: post
title: 深度学习笔记2
subtitle: notebook2
author: muwu
date: 2021-12-02 17:03:07 +0800
categories: 深深度学习
tag: 深度学习
---

# 专业术语

## 神经网络 Neural Network

![image-20211202171501649](2021-12-02-deep-learning-2.assets/image-20211202171501649.png)

神经网络其实就是同一个方法的多次迭代？

hidden layer的shape = [当前层次个数， 前一层个数] ？

把上一层神经元的结果当成x进行下一层神经元的计算（导致每层的特征数量不一样）

（input and output）矩阵的纵向（第一维）代表隐藏单元，横向表示数据样本个数 【X, Z, A, Y】(PS. a0的隐藏单元数量等于x的特征数量) 

(parameter)矩阵和上述情况不一样，不受数据样本个数影响 【W, B】

## 激活函数 Activation function

sigmoid (binary classification) [0~1]

tanh [-1~1]

ReLU [0~+∞]

![image-20211202202401805](2021-12-02-deep-learning-2.assets/image-20211202202401805.png)

## L 

number of layers (输入层为layer 0)

## n

num of node in a layer

# Tip

## 可以使用for loop的地方

1. 多次迭代
2. 内部的多个隐藏层
