---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Pokémon Database Maker"
summary: "ポケットモンスター ソード・シールドのポケモン図鑑をCSV形式で生成するCLIアプリケーション"
authors: []
tags: ["Hobby", "Pokémon"]
categories: []
date: 2019-11-22

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
[GameWith](https://gamewith.jp/pokemon-sword-shield/article/show/175731)のWebサイトをクローリングし、ポケットモンスター ソード・シールドのポケモン図鑑を生成するCLIアプリケーションです。ポケモンを統計的視点から分析してみたい人や、育成したポケモンを管理したい人などにオススメです。

## 2. ポケットモンスター ソード・シールドとは？
2019年11月15日にNintendo Switchから発売されたポケットモンスターシリーズの最新作です (2019年11月現在)。ポケットモンスターシリーズ初のNintendo Switch対応ソフトであり、従来の3DS版と比較してグラフィックが非常に綺麗になりました。対戦では、「メガシンカ」と「Zワザ」が廃止され、新たに「ダイマックス」が実装されたことで、より一層おもしろい駆け引きを楽しめる仕様となりました。

## 3. 使用した言語・フレームワーク
- Python (BeautifulSoup / pandas)
- Docker

## 4. 使い方
CLIで以下のコマンドを叩いてください。GitHubリポジトリは[こちら](https://github.com/shimech/pokemon_dbmaker)

```shell
$ git clone https://github.com/shimech/pokemon_dbmaker.git
$ cd pokemon_dbmaker/
$ sh run.sh
```
