---
layout: post
title: "Self-training with Noisy Student improves ImageNet classification"
tags: ["arxiv","semi-supervised"]
date: 2019-11-18 23:21:11 +0900
---

正解付き画像で教師あり学習し教師モデルを作成，次に教師モデルで正解なし画像に擬似ラベルを付与，そして正解付き画像と擬似ラベル付き画像で生徒モデルを学習，というself-trainingの手法に関する論文．生徒モデルの学習時にノイズ（data augmentation, dropout, stochastic depth）を乗せると，精度とロバスト性の両方を大幅に向上することを発見した．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1911.04252

### 著者・所属
Qizhe Xie, Eduard Hovy, Minh-Thang Luong, Quoc V. Le
(Google Research, CMU)

### 投稿日
2019/11/11 (arXiv)

## 新規性

- Self-trainingにおいて生徒モデルに積極的にノイズを加えることの有用性を明らかにした

## 手法
![image](https://user-images.githubusercontent.com/17794644/69034829-74ed5500-0a25-11ea-970e-2f8cff3471e7.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/69035031-f513ba80-0a25-11ea-9c80-43352dc7ee73.png)
![image](https://user-images.githubusercontent.com/17794644/69035064-0a88e480-0a26-11ea-8010-1bc7788eb0c2.png)

## 議論・コメント

手法の新規性という意味では真新しさを感じないものの，結果がすごいように見える．

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/95
