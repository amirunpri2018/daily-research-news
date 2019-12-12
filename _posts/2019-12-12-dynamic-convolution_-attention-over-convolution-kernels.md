---
layout: post
title: "Dynamic Convolution: Attention over Convolution Kernels"
tags: ["network design"]
date: 2019-12-12 17:48:35 +0900
---

畳み込みに代わる動的畳み込み（Dynamic Convolution）を提案．複数の異なる畳み込みを適用した後，その結果をサンプル毎に決まる重みで重みづけして足し合わせて出力する．重みはSEブロックで決める．畳み込み演算に比べるとSEの計算，重みづけ和の計算は軽量で，単にモデルサイズを大きくするのと比べて，計算量と精度のトレードオフを改善できる．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1912.03458

### 著者・所属
Yinpeng Chen, Xiyang Dai, Mengchen Liu, Dongdong Chen, Lu Yuan, Zicheng Liu

## 新規性

## 手法
![image](https://user-images.githubusercontent.com/17794644/70696271-b2808d80-1d06-11ea-8cfb-1bd436827ba3.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/70696314-ca581180-1d06-11ea-9348-59c7232d26ed.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/146
