---
layout: post
title: "Consistency Regularization for Generative Adversarial Networks"
tags: ["GAN"]
date: 2019-11-09 16:57:14 +0900
---

Spectral normalization（SN）と勾配ノルムの正則化は，共にdiscriminatorのLipschitz定数を抑制しGANの学習を安定化させることが知られているが，SNと勾配ノルム正則化を併用してもSN単体と変わらないことが経験的に知られていた．本論文では別のアプローチとして，半教師あり学習で用いられるconsistency regularizationをdiscriminatorに課すことを提案．SNからさらに性能を上積みすることに成功した．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1910.12027

### 著者・所属
Han Zhang, Zizhao Zhang, Augustus Odena, Honglak Lee (Google AI)

### 投稿日
2019/10/26 (arXiv)

## 新規性

- 画像を意味的に変えないようなデータ拡張をしても識別結果が変わらない，というconsistencyをdiscriminatorに課したCRGANを提案

## 手法

- Proposed consistency regularization
  - ![image](https://user-images.githubusercontent.com/17794644/68525088-3fec4e80-0311-11ea-907e-61e97a8fad8d.png)

## 結果

![image](https://user-images.githubusercontent.com/17794644/68525129-c0ab4a80-0311-11ea-952c-0a6a49ad872d.png)
![image](https://user-images.githubusercontent.com/17794644/68525139-d4ef4780-0311-11ea-8f59-276185204fe0.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/52
