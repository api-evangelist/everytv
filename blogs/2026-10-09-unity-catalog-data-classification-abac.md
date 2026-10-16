---
title: "Unity CatalogのData ClassificationとABACで機密データを検出しマスクする"
url: "https://tech.every.tv/entry/2026/10/09/141458?utm_source=feed"
date: "2026-10-09"
author: "ngmk"
feed_url: "https://tech.every.tv/feed"
---
はじめに こんにちは 開発本部 開発1部 デリッシュリサーチでデータエンジニアをしている吉田です。 今回は、Unity CatalogのData Classificationで機密データを含むカラムを自動検出し、付与されたタグをもとにABACのcolumn maskポリシーでマスクするまでを試した話を紹介します。 注意点 本記事の検証に使ったデータは、すべてFakerで生成した架空のものです。 実在する人物や実環境のデータは含んでいません。 また、テストに使ったテーブルは検証用に新しく作ったものです。 Data Classificationはインテリジェントなスキャンでコストを最適化とあるため…
