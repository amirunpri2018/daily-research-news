---
layout: post
title: "Adaptive versus Standard Descent Methods and Robustness Against Adversarial Examples"
tags: ["adversarial example/robustness","arxiv"]
date: 2019-11-13 23:05:39 +0900
---

Adamなどadaptiveな最適化アルゴリズムのadversarial robustnessに関する論文．線形回帰のトイモデルについて，non-adaptive/adaptiveなアルゴリズムで得られる解のrobustnessを理論的に解析し，adaptiveな解はnon-adaptiveな解よりずっとロバスト性が低い，特にサンプル数が増えるとロバスト性が下がる（！）ことを示した．

## 基本情報
### 会議・論文誌

### 論文リンク
https://arxiv.org/abs/1911.03784

### 著者・所属
Marc Khoury (UCBerkley)

### 投稿日
2019/11/09 (arXiv)

## 新規性

## 手法

## 結果
![image](https://user-images.githubusercontent.com/17794644/68770471-8f13e580-0669-11ea-9c15-561f057d28ff.png)
![image](https://user-images.githubusercontent.com/17794644/68770498-99ce7a80-0669-11ea-8177-e7eb484b4ad0.png)

## 議論・コメント

- サンプル数が増えるとロバスト性が下がるってどういうことだろう
- 理論解析のためとはいえかなり人工的な例に見えるが，adversarial robustnessの研究ではよく使われる例なのだろうか．どういう意図？

## 関連文献

- A. C. Wilson, R. Roelofs, M. Stern, N. Srebro, and B. Recht. The marginal value of adaptive gradient methods in machine learning. In NIPS, 2017.
  - adaptiveなアルゴリズムの汎化性能について論じた先行研究

## Original issue and comments

https://github.com/yoshum/daily-research-news/issues/92
