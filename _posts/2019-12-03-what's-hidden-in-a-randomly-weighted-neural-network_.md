---
layout: post
title: "What's Hidden in a Randomly Weighted Neural Network?"
tags: ["arxiv","random NN"]
date: 2019-12-03 23:37:27 +0900
---

大きなNNには重みをランダム初期化したNNには，一切学習することなくタスクを高精度で解ける部分NNが存在するという仮説を立て，実際にそのような部分NNを見つけるアルゴリズムを提案．Lottery Ticket Hypothesis（大きなNNは学習しやすい部分NNを含む）との違いに注意．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1911.13299

### 著者・所属
Vivek Ramanujan, Mitchell Wortsman, Aniruddha Kembhavi, Ali Farhadi, Mohammad Rastegari

## 新規性

重みを初期化しただけの（未学習の）NNから，タスクを解ける部分NNを見つけ出すedge-popアルゴリズムを提案．

## 手法
![image](https://user-images.githubusercontent.com/17794644/70059700-930da480-1624-11ea-8771-8ba40ceb12b7.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/70059858-d831d680-1624-11ea-8ddc-0d73383b13c0.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/133
