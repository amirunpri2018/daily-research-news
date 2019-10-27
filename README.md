# PaperSummary

最新論文のまとめを共有するためのリポジトリです．
投稿済みのまとめは[こちら](https://yoshum.github.io/PaperSummary)で公開しています．

## 論文追加方法

- 論文はissueとして登録します
- テンプレートは[こちら](.github/ISSUE_TEMPLATE/article-summary.md)
- 閲覧中のWebページから空のsummaryを生成するBookmarklet（デフォルトで`TBR`タグ付き）
```
javascript:(function(){var a=window.prompt("Create an empty summary for this article?",document.title);a&&window.open("https://github.com/yoshum/PaperSummary/issues/new?assignees=&labels=TBR&template=article-summary.md&title="+encodeURIComponent(a.trim()))})();
```

## 参考リンク

- [arXiv](https://arxiv.org/)
  - Computer Science
    - Artificial Intelligence (cs.AI) [recent](https://arxiv.org/list/cs.AI/recent) / [new](https://arxiv.org/list/cs.AI/new)
    - Computer Vision and Pattern Recognition (cs.CV) [recent](https://arxiv.org/list/cs.CV/recent) / [new](https://arxiv.org/list/cs.CV/new)
    - Machine Learning (cs.LG) [recent](https://arxiv.org/list/cs.LG/recent) / [new](https://arxiv.org/list/cs.LG/new)
  - Statistics
    - Machine Learning (stat.ML) [recent](https://arxiv.org/list/stat.ML/recent) / [new](https://arxiv.org/list/stat.ML/new)
  - Physics
    - Disordered Systems and Neural Networks (cond-mat.dis-nn) [recent](https://arxiv.org/list/cond-mat.dis-nn/recent) / [new](https://arxiv.org/list/cond-mat.dis-nn/new)
    - Quantum Gases (cond-mat.quant-gas) [recent](https://arxiv.org/list/cond-mat.quant-gas/recent) / [new](https://arxiv.org/list/cond-mat.quant-gas/new)
    - Statistical Mechanics (cond-mat.stat-mech) [recent](https://arxiv.org/list/cond-mat.stat-mech/recent) / [new](https://arxiv.org/list/cond-mat.stat-mech/new)
- Conference information
  - [AI Conference Deadlines](https://aideadlin.es/?sub=ML,CV,NLP,RO,SP,DM)
  - [Best Paper Awards in Computer Science](https://jeffhuang.com/best_paper_awards.html)
- [arXivTimes](https://github.com/arXivTimes/arXivTimes)
  - GitHub Issuesに論文まとめを蓄積する手法を参考にしました
