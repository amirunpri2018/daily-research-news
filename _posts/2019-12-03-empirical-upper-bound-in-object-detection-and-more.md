---
layout: post
title: "Empirical Upper-bound in Object Detection and More"
tags: ["arxiv","object detection"]
date: 2019-12-03 23:11:32 +0900
---

物体検知手法に関するメタ研究．「上限AP」と実際のモデルのAPを比較し，そのギャップの原因を分析．この研究では，切り出したバウンディングボックスで分類モデルを学習して得られるテストAP（＝BBox回帰は完全にできていると仮定し，クラス分離に注力した際に達成できるAP）が物体検知の「上限AP」であると仮定．Contextの有効性に関する分析（小さい物体には有効）やerror diagnosisが面白い．実験の量がすごい．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1911.12451

### 著者・所属
Ali Borji, Seyed Mehdi Iranmanesh

## 新規性
BBox回帰は完全にできていると仮定してクラス分離に注力した際に達成できるAP（「上限AP」）と，実際に実現しているAPを比較し，その原因を分析している．

## 手法

学習データのバウンディングボックスを切り出し，正解クラスラベルを付与して分類モデルを学習，テストデータのバウンディングボックスを切り出した画像に対して評価した際に達成できるAPを測ることで，「上限AP」を測定．

## 結果
![image](https://user-images.githubusercontent.com/17794644/70057810-247b1780-1621-11ea-8077-42676f107bda.png)

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/132
