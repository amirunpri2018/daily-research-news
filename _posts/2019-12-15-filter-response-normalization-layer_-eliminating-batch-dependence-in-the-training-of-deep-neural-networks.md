---
layout: post
title: "Filter Response Normalization Layer: Eliminating Batch Dependence in the Training of Deep Neural Networks"
tags: ["arxiv","network design"]
date: 2019-12-15 22:38:04 +0900
---

性能がバッチサイズに依存せず，大きなバッチサイズでもバッチ正規化より性能が良いfilter response normalization layerを提案．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1911.09737

### 著者・所属
Saurabh Singh, Shankar Krishnan

## 新規性

- バッチサイズに依存しない正規化手法 filter response normalization (FRN)を提案
- FRNと一緒に使うことで性能を改善する活性関数thresholded linear unit (TLU)を提案
  - FRNとTLUを合わせてFRN layerと呼んでいる

## 手法

- ![image](https://user-images.githubusercontent.com/17794644/70863346-a1e04980-1f8a-11ea-85fa-2a27613f39a3.png)
  - 和は各サンプル・各チャンネルの空間方向に取る
  - $\gamma, \beta, \tau$ は学習パラメータ

## 結果
![image](https://user-images.githubusercontent.com/17794644/70862931-e4535780-1f85-11ea-8326-897bc298dbbf.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/149
