---
layout: post
title: "Multiple Anchor Learning for Visual Object Detection"
tags: ["arxiv","object detection"]
date: 2019-12-09 11:42:02 +0900
---

通常，アンカーベースの物体検知では正解BBoxとIoUの大きいアンカーを正例とみなし，各アンカーを独立なサンプルとして学習するため，正解の割り当てによって性能が制限される．そこで，multi-instance learningに倣い，複数のアンカーボックスを正解候補として学習することで，最適な正解アンカーボックスの割り当てを学習過程で自動的に行うMultiple Anchor Learning (MAL)を提案．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1912.02252

### 著者・所属
Wei Ke, Tianliang Zhang, Zeyi Huang, Qixiang Ye, Jianzhuang Liu, Dong Huang

## 新規性
![image](https://user-images.githubusercontent.com/17794644/70402988-a1225180-1a78-11ea-9695-445cd56995f8.png)

## 手法
![image](https://user-images.githubusercontent.com/17794644/70403001-ad0e1380-1a78-11ea-9063-f9f9d2d86199.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/70403011-bbf4c600-1a78-11ea-94eb-67176e1d3348.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/141
