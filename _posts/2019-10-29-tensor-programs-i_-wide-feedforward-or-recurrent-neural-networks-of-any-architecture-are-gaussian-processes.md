---
layout: post
title: "Tensor Programs I: Wide Feedforward or Recurrent Neural Networks of Any Architecture are Gaussian Processes"
tags: ["DL theory","DNN as GP","arxiv"]
date: 2019-10-29 23:11:22 +0900
---

DNNがGPであるという議論は，従来個別のネットワーク構造に対して成されてきた．これに対して本論文では，NETSORと呼ばれる計算表現の手法を導入，NETSORで表現できる計算に対してGPへの収束を示した．NETSORは一般に使われているほとんどの構造を表現できるため，従来の結果を包括するかなり一般的な結論であると言える．

## 基本情報
### 会議・論文誌
NeurIPS2019

### 論文リンク
https://arxiv.org/abs/1910.12478

### 著者・所属

- Greg Yang (Microsoft Research AI)
  - Mean-field theory関係の仕事をたくさんしている人

### 投稿日
2019/10/29 (arXiv)

## 新規性

## 手法

## 結果

## 議論・コメント

## 関連文献

- Radford M Neal. BAYESIAN LEARNING FOR NEURAL NETWORKS. PhD Thesis, University of Toronto, 1995.
  - この分野の古典．浅いネットワークがGPであることを示した
- Greg Yang. Scaling Limits of Wide Neural Networks with Weight Sharing: Gaussian Process Behavior, Gradient Independence, and Neural Tangent Kernel Derivation. arXiv:1902.04760 [cond-mat, physics:math-ph, stat], February 2019.
  - NETSORの元になっているtensor programsの論文．

## Original issue and comments

https://github.com/yoshum/PaperSummary/issues/35
