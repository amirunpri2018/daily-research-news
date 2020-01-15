---
layout: post
title: "Reformer: The Efficient Transformer"
tags: ["ICLR","arxiv","attention"]
date: 2020-01-16 06:58:49 +0900
---

Transformerは列の長さLに対して計算量がO(L^2)であるため，長い列に不向きである．そこで，ドット積アテンションで計算するsoftmax(QK^T)の値が，QとKの列ベクトルの組のうち内積が大きい（コサイン類似度が大きい）ものによって決まることに着目，locality-sensitive hashingで同じハッシュに属するqueryとkeyの組のみに内積を計算することで，精度を元のTransformerと同程度に維持しつつ，計算量をO(L log L)に削減．

## 基本情報
### 会議・論文誌
ICLR2020

### 論文リンク
https://arxiv.org/abs/2001.04451

### 著者・所属
Nikita Kitaev, Łukasz Kaiser, Anselm Levskaya

## 新規性

## 手法

## 結果

## 議論・コメント

## 関連文献


## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/165
