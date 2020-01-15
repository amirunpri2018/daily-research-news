---
layout: post
title: "Cross-dataset Training for Class Increasing Object Detection"
tags: ["object detection","weakly supervised"]
date: 2020-01-15 23:49:30 +0900
---

物体検知タスクにおいて，それぞれ異なるクラスが正解付けされた複数のデータセットをまとめて学習する，cross-dataset trainingの論文．あるデータセットで負例とみなされるアンカーボックスも，他のデータセットの正解付け対象を含む正例である可能性（★）がある．この問題を解消するために，dataset-aware focal loss を使う．このロス関数では，（★）の状況が生じうるアンカーボックスのロスを全体のロス関数から取り除くことで，正例を誤って負例と学習することを防ぐ．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/2001.04621

### 著者・所属
Yongqiang Yao, Yan Wang, Yu Guo, Jiaojiao Lin, Hongwei Qin, Junjie Yan

## 新規性

## 手法
![](https://user-images.githubusercontent.com/17794644/72442442-df393080-37ef-11ea-8dae-005d14832b4a.png)
![](https://user-images.githubusercontent.com/17794644/72442441-dea09a00-37ef-11ea-934c-68cff8079a9d.png)

## 結果

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/163
