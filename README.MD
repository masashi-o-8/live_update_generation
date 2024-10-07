# Transformerモデルを利用したマイクロブログからのサッカー速報生成
このリポジトリは、X（旧Twitter）の投稿からスポーツ速報を生成するモデルを作成するために、モデルのfine-tuningに利用するデータセット構築のためのファイルを含んでいます。投稿の収集に用いたデータや、実際に作成したモデルが生成した速報例を公開したものです。

## ディレクトリの内容
### generation_examples
実験で作成した速報テキストをモデルごとに格納しています。

### hashtags
投稿データの収集に利用したチームごとのハッシュタグを格納しています。

### posts
データセット構築に利用した投稿データの著者IDおよび投稿IDを格納しています。
[https://x.com/{著者ID}/status/{投稿ID}] のようなリンクで検索することで閲覧が可能です。

## 正解速報について
本研究で用いた正解速報は日本のプロサッカーリーグであるJリーグの[公式ホームページ](https://www.jleague.jp/)より試合中に作成されるテキスト速報を収集して利用しました。

## 権利について
投稿データの著作権は投稿作成者に帰属します。利用の際は留意ください。


## 参考文献
 - 大鹿雅史，山田康輔，笹野遼平，武田浩一 (2023). 言語モデルT5を用いたTwitterからのス
ポーツ速報生成. 人工知能学会全国大会論文集 37回. [link](https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_4Xin120/_article/-char/ja/)
 - Oshika, M., Yamada, K., Sasano, R., and Takeda, K. (2023). “Transformer-based Live Update
Generation for Soccer Matches from Microblog Posts.” In Proceedings of the 2023 Conference
on Empirical Methods in Natural Language Processing (EMNLP), pp. 10100–10106. [link](https://aclanthology.org/2023.emnlp-main.624/)
