---
layout: post
title: "15 Keypoints Is All You Need"
tags: ["arxiv","pose estimation","tracking"]
date: 2019-12-09 10:25:42 +0900
---

姿勢追跡の手法．2フレーム分の人体キーポイント情報から，それらが同じ人物のものかどうかを判定するPose Entailmentにより，速くて正確なトラッキングを実現する．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1912.02323

### 著者・所属
Michael Snower, Asim Kadav, Farley Lai, Hans Peter Graf

## 新規性

- 2フレームの姿勢ペアが同一人物のものか2値分類によって判定するPose Entailment
- 前フレームの検知バウンディングボックスを使って（トップダウン方式の）姿勢推定を改善するTOKS

## 手法
![image](https://user-images.githubusercontent.com/17794644/70399827-9496fc80-1a6a-11ea-8f06-46d1b803462f.png)
![image](https://user-images.githubusercontent.com/17794644/70400038-c8beed00-1a6b-11ea-94b9-2ef6b1913b90.png)

## 結果
![image](https://user-images.githubusercontent.com/17794644/70400045-de341700-1a6b-11ea-9025-cb3e83ab2a3a.png)
![image](https://user-images.githubusercontent.com/17794644/70400050-eb510600-1a6b-11ea-980e-d3eec0f11724.png)


## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/140
