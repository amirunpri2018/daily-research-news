---
layout: post
title: "Understanding the Role of Momentum in Stochastic Gradient Methods"
tags: ["NeurIPS","SGD"]
date: 2019-11-09 16:06:45 +0900
---

Momentum SGDに関する理論解析．MSGDの典型的な亜種を含むQHMというクラスのアルゴリズムについて，漸近的な収束性，局所解近傍の安定性，局所解近傍での平衡分布を調べた．

## 基本情報
### 会議・論文誌
NeurIPS2019

### 論文リンク
https://arxiv.org/abs/1910.13962

### 著者・所属
Igor Gitman, Hunter Lang, Pengchuan Zhang, Lin Xiao (MSR)

### 投稿日
2019/10/30 (arXiv)

## 新規性

## 手法

- QHM
  - ![image](https://user-images.githubusercontent.com/17794644/68524296-55a94600-0308-11ea-934f-b04bf5e60906.png)
- 仮定
  - ![image](https://user-images.githubusercontent.com/17794644/68524373-8342bf00-0309-11ea-9860-174ff75524f8.png)


## 結果

![image](https://user-images.githubusercontent.com/17794644/68524381-9c4b7000-0309-11ea-92c8-f2b06a57f84a.png)
![image](https://user-images.githubusercontent.com/17794644/68524385-a5d4d800-0309-11ea-890c-135e7c423bc7.png)
![image](https://user-images.githubusercontent.com/17794644/68524411-f0565480-0309-11ea-86b7-6895af74d667.png)

## 議論・コメント

practical implicationsが学習率を小さくする方を向いているのが不思議．
最近は（バッチサイズとともに）学習率を大きくする流れだったと思うが．
収束を速く，平衡分布の分散を小さくすることと，汎化性能を維持することは相反する？

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/47
