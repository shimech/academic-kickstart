---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Pokémon Database Maker"
summary: "ポケモンの全国図鑑をCSV形式で生成するCLIアプリケーション"
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

[ポケモン徹底攻略](https://yakkun.com/swsh/stats_list.htm?mode=all)さんの Web サイトをクローリングし、ポケモンの全国図鑑を生成する CLI アプリケーションです。ポケモンを統計的視点から分析してみたい人や、育成したポケモンを管理したい人などにオススメです。

## 2. ポケットモンスター ソード・シールドについて

2019 年 11 月 15 日に Nintendo Switch から発売されたポケットモンスターシリーズの最新作です (2019 年 11 月現在)。ポケットモンスターシリーズ初の Nintendo Switch 対応ソフトであり、従来の 3DS 版と比較してグラフィックが非常に綺麗になりました。対戦では、「メガシンカ」と「Z ワザ」が廃止され、新たに「ダイマックス」が実装されたことで、より一層おもしろい駆け引きを楽しめる仕様となりました。

## 3. 使用した言語・フレームワーク

- Python (BeautifulSoup / pandas)
- Docker

## 4. 使い方

CLI で以下のコマンドを叩いてください。GitHub リポジトリは[こちら](https://github.com/shimech/pokemon-db-maker)

```sh
$ git clone https://github.com/shimech/pokemon-db-maker.git
$ cd pokemon-db-maker/
$ make build
$ make docker-run
```
