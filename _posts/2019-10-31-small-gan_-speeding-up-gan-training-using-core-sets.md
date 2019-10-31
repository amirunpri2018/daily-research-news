---
layout: post
title: "Small-GAN: Speeding Up GAN Training Using Core-sets"
tags: ["GAN","active learning","arxiv"]
date: 2019-10-31 17:02:17 +0900
---

GANの学習においてバッチサイズを大きくするとFIDが大きく改善することが知られているが（BigGAN），多くの人にとって学習環境の制約から現実的ではない．この論文では，大きなバッチから上手くコア集合を選択することで，実効的に大バッチ学習を小バッチで実現する方法を提案．既存手法に適用してFIDが改善することを実験的に確認．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1910.13540

### 著者・所属
Samarth Sinha, Han Zhang, Anirudh Goyal, Yoshua Bengio, Hugo Larochelle, Augustus Odena
(UMontr´eal, Google Brain, UToronto)

### 投稿日
2019/10/29 (arXiv)

## 新規性

Active learningで用いられるcore-set selectionに基づき，実効的に大きなバッチサイズを小さいバッチで実現する手法を提案し，GANの学習に適用した

## 手法
![image](https://user-images.githubusercontent.com/17794644/67929009-ab426c00-fbff-11e9-8e70-2ee207e3fbe5.png)
![image](https://user-images.githubusercontent.com/17794644/67929052-bf866900-fbff-11e9-8e5a-dbea83368b7f.png)

## 結果

## 議論・コメント

## 関連文献

- Pankaj K Agarwal, Sariel Har-Peled, and Kasturi R Varadarajan. Geometric approximation via
coresets. Combinatorial and computational geometry, 52:1–30, 2005.
  - core-set selectionの論文

## Original issue and comments

https://github.com/yoshum/PaperSummary/issues/46
