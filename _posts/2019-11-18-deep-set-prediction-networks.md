---
layout: post
title: "Deep Set Prediction Networks"
tags: ["NeurIPS","sets"]
date: 2019-11-18 17:46:06 +0900
---

ベクトル入力の集合値関数（e.g.物体検知）を深層学習モデルで学習する手法．NeurIPS2019．置換不変なエンコーダ $g_{enc}$（e.g. deep sets）が与えられている時，それが定める潜在空間に値 $z$ を持つようなモデルを学習し，$|g_enc(y) - z|^2$ を最小化するように集合 $y$ を推論する．

## 基本情報
### 会議・論文誌
NeurIPS2019

### 論文リンク
https://arxiv.org/abs/1906.06565

### 著者・所属
Yan Zhang, Jonathon Hare, Adam Prügel-Bennett (University of Southampton)

### 投稿日
2019/06/15 (arXiv)

## 新規性

## 手法

- デコーダ
  - ![image](https://user-images.githubusercontent.com/17794644/69037273-eb408600-0a2a-11ea-966c-ecf8a7c829c2.png)

## 結果

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/86
