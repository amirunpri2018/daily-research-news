---
layout: post
title: "Preventing Gradient Attenuation in Lipschitz Constrained Convolutional Networks"
tags: ["GAN","NeurIPS"]
date: 2019-11-11 00:30:38 +0900
---

層ごとにLipschitz定数を制約する従来手法では，逆伝搬で勾配が減衰する問題が指摘されている．この問題を生じないネットワーク構造として，全結合NNに対してはgradient norm preserving (GNP)アーキテクチャが提案されている．CNNに対しては直交畳込みを使った方法が提案されているが，直交畳込みの全体は非連結な集合を成すため勾配法による更新ができない．この論文では， nチャンネルの直交畳込みを2nチャンネルに拡張することで，非連結性の問題を解消できることを示した．

## 基本情報
### 会議・論文誌
NeurIPS2019

### 論文リンク
https://arxiv.org/abs/1911.00937

### 著者・所属
Qiyang Li, Saminul Haque, Cem Anil, James Lucas, Roger Grosse, Jörn-Henrik Jacobsen (UToronto)

### 投稿日
2019/11/03 (arXiv)

## 新規性

- 直交畳込みは非連結な集合を成す（射影演算子のランクが離散的なため）のに対して，直交畳込みを全て含むような連結なパラメトリゼーション（BCOP）が存在することを示した
- 主定理
  - ![image](https://user-images.githubusercontent.com/17794644/68546454-a9f01b00-0419-11ea-905d-99702705eb94.png)

## 手法
![image](https://user-images.githubusercontent.com/17794644/68546436-69909d00-0419-11ea-99c6-95558d051fab.png)

## 結果

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/63
