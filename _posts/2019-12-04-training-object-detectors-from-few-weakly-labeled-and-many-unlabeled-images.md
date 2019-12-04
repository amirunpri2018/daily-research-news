---
layout: post
title: "Training Object Detectors from Few Weakly-Labeled and Many Unlabeled Images"
tags: ["object detection","semi-supervised","weakly supervised"]
date: 2019-12-04 23:59:05 +0900
---

画像レベルのクラスラベルが付いた少数の画像と，全くラベルが付いていない多数の画像から，物体検知を学習する手法を提案（c.f. 物体検知の弱教師あり学習では，画像レベルのラベルが付いた画像から物体検知を学習する設定が多い）．まず，半教師あり学習で画像レベルの分類モデル（「教師モデル」）を学習．教師モデルを使ってラベル無し画像に（画像レベルの）擬似ラベルを付けるとよくある弱教師あり物体検知の設定に帰着するので，その既存手法によって物体検知を学習する．

## 基本情報
### 会議・論文誌

### 論文リンク

https://arxiv.org/abs/1912.00384

### 著者・所属

Zhaohui Yang, Miaojing Shi, Yannis Avrithis, Chao Xu, Vittorio Ferrari

## 新規性

分類の半教師あり学習と物体検知の弱教師あり学習を組み合わせて，ラベル無し画像を活用した弱教師あり物体検知を解く．

## 手法
![image](https://user-images.githubusercontent.com/17794644/70153018-9327a600-16f1-11ea-9021-dd7f91d7c305.png)

## 結果

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/139
