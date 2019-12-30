---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Senryu Bot"
summary: "メッセージから川柳を生成するBOT"
authors: []
tags: ["Hackathon"]
categories: []
date: 2019-08-09

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## 1. 概要
[株式会社ドリーム・アーツ](https://www.dreamarts.co.jp/)さんでの5日間のハッカソン形式のインターンで開発した成果物です。「NLPで、働く人の「協創」を実現するサービスを開発しよう！」というテーマで、ドリーム・アーツさんの自社プロダクトである「[知話輪](https://www.chiwawa.one/)」上で動作するチャットボットの開発に取り組みました。

[GitHubリポジトリ](https://github.com/shimech/boston_terrier)

## 2. 使用した言語・フレームワーク
- Python (flask / keras / BeautifulSoup)
- MeCab
- Word2Vec
- Seq2Seq / LSTM / Attention
- Graph Database
- Docker

## 3. 結果
ご覧の通り、残念な結果でした。敗因は、川柳生成を完全にモデルに委ねてしまったことです。

- 単語は元メッセージからそのまま引用する
- 「名詞」+「動詞」などの規則を定義する

など、ルールベースである程度生成すれば少し改善したかなと思います。
