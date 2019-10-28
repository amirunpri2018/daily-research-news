---
layout: default
title: "Progressive Domain Adaptation for Object Detection"
tags: ["GAN","WACV","domain adaptation","object detection"]
date: 2019-10-27 17:58:02 +0000
---

# Progressive Domain Adaptation for Object Detection

物体検知に対するドメイン適応の新手法．大きなドメインギャップを埋めるため，中間的なドメインの画像をCycleGANで合成し，元ドメインから中間ドメイン，中間ドメインからターゲット・ドメインという2段階のドメイン適応を行う．

## 基本情報
### 会議・論文誌
WACV2020

### 論文リンク
https://arxiv.org/abs/1910.11319

### 著者・所属
Han-Kai Hsu, Chun-Han Yao, Yi-Hsuan Tsai, Wei-Chih Hung, Hung-Yu Tseng, Maneesh Singh, Ming-Hsuan Yang
(UC Merced, NEC Labs America, Verisk Analytics, Google)

### 投稿日
2019/10/24 (arXiv)

## 新規性

- ドメイン・ギャップを埋めるために中間ドメインを生成してドメイン適応を行う
- 生成した中間ドメインのサンプルごとの重要性を評価し，ロスの重み付けを行う

## 手法
![image](https://user-images.githubusercontent.com/17794644/67638950-a050b880-f92d-11e9-8402-ccc6d563e11b.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/67639060-aabf8200-f92e-11e9-808f-4120df561df6.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/PaperSummary/issues/27
