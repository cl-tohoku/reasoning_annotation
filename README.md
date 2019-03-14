# 概要
[WikiHop](http://qangaroo.cs.ucl.ac.uk/) に回答論拠を付与したデータセットです。クラウドソーシングにより構築しています。詳しくは、下記の論文を御覧ください。

- 井之上 直也, Pontus Stenetorp, 乾 健太郎. クラウドソーシングによるマルチホップQAへの論拠の付与. 言語処理学会 第25回年次大会予稿集. 4 pages. March 2019.

現在は諸般の事情により、超小規模サンプルデータのみ（`reasoning_corpus_sample.csv`）を公開しています。


# 書式
csv です。下記に各カラムの意味を示します。

- `id`: [WikiHop](http://qangaroo.cs.ucl.ac.uk/) の事例 ID
- `nb_hop`: 推論ステップ数
- `query_nl`: 命題
- `supdoc1`, `supdoc2`, `supdoc3`: 関連文書集合 (WikiHop より提供)


# Acknowledgements
This work was supported by JST CREST Grant Number JPMJCR1513, including AIP challenge.
