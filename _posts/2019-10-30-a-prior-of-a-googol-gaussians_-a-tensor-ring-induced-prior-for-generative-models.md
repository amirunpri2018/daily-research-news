---
layout: post
title: "A Prior of a Googol Gaussians: a Tensor Ring Induced Prior for Generative Models"
tags: ["GAN","NeurIPS"]
date: 2019-10-30 17:34:01 +0900
---

GANのmode collapseを防ぐため，先行研究で複雑なpriorを使用することが提案されている．この論文では，混合ガウス分布をテンソル積表現したTensor Ring Induced Prior (TRIP)を提案．TRIPはパラメータ数に対して指数的に多くのmodeを含む．TRIPを使うことで，FID(GAN)やELBO(VAE)が改善することを実験で示した．

## 基本情報
### 会議・論文誌
NeurIPS2019

### 論文リンク
https://arxiv.org/abs/1910.13148

### 著者・所属
Maksim Kuznetsov, Daniil Polykovskiy, Dmitry Vetrov, Alexander Zhebrak
(Insilico Medicine, National Research University Higher School of Economics)

### 投稿日
2019/10/29 (arXiv)

## 新規性

- 指数的に多くのmodeを含む混合ガウス分布のテンソル積表現 TRIP を導入した
- TRIPを使用することで，FIDやELBOを改善することを示した

## 手法
![image](https://user-images.githubusercontent.com/17794644/67841249-fd6d8980-fb3a-11e9-9772-ff02f24faa19.png)

![image](https://user-images.githubusercontent.com/17794644/67841226-efb80400-fb3a-11e9-8ab7-062affce34ef.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/67841283-0bbba580-fb3b-11e9-9844-ea94e69a55c3.png)
![image](https://user-images.githubusercontent.com/17794644/67841315-2261fc80-fb3b-11e9-88b6-e5730aabb440.png)
![image](https://user-images.githubusercontent.com/17794644/67841365-41608e80-fb3b-11e9-81f4-29d504657e74.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/PaperSummary/issues/41
