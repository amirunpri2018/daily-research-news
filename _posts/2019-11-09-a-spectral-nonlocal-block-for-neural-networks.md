---
layout: post
title: "A Spectral Nonlocal Block for Neural Networks"
tags: ["network design"]
date: 2019-11-09 21:36:39 +0900
---

この論文では，グラフデータのフィルタリングの観点からnonlocal block (NL)を分析し，一般のフィルタ関数をChebyshev多項式展開してある拘束条件を課したものがNLに帰着することを示した．この拘束条件がNLの不安定性の原因であると仮説を立て，これを取り除いたspectral nonlocal blockを提案．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1911.01059

### 著者・所属
Lei Zhu, Qi She, Lidan Zhang, Ping Guo

### 投稿日
2019/11/04 (arXiv)

## 新規性

## 手法

- SNL block
  - ![image](https://user-images.githubusercontent.com/17794644/68528526-51485180-0337-11ea-8445-6d847b4c2358.png)
  - ![image](https://user-images.githubusercontent.com/17794644/68528532-6329f480-0337-11ea-8ec2-34ec691435c5.png)
- generalized SNL block
  - ![image](https://user-images.githubusercontent.com/17794644/68528557-bd2aba00-0337-11ea-973d-ccb583f8b75f.png)

![image](https://user-images.githubusercontent.com/17794644/68528568-d92e5b80-0337-11ea-9658-3a096bb2c867.png)

## 結果

![image](https://user-images.githubusercontent.com/17794644/68528584-0b3fbd80-0338-11ea-8061-360da5e98058.png)
![image](https://user-images.githubusercontent.com/17794644/68528586-1397f880-0338-11ea-9490-dec426d71d34.png)
![image](https://user-images.githubusercontent.com/17794644/68528592-24486e80-0338-11ea-866b-0e73559e2118.png)

## 議論・コメント

gSNLはSNLと等価に見えるが何が違うのか？

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/67
