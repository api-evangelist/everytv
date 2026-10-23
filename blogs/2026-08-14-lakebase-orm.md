---
title: "Lakebaseの認証実装とORM選定をした話"
url: "https://tech.every.tv/entry/2026/08/14/111734?utm_source=feed"
date: "2026-08-14"
author: "shintani-y"
feed_url: "https://tech.every.tv/feed"
---
はじめに こんにちは、株式会社エブリーのデリッシュキッチンにて7月から約1か月間エンジニアとしてインターンシップに参加していました、亀井と申します。 この記事では、インターン中に取り組んだことの中心である「Databricks LakebaseへのOAuth M2M認証の導入」と、その先でデータを読むための「GoのPostgreSQL向けライブラリ選定」の2つについて、どう実装・検証・調査したのかを書きたいと思います。 インターンで取り組んだこと インターンでは、Go言語で書かれたデリッシュキッチンのAPIサーバーを主な対象として、次の4つに取り組みました。 デリッシュAIの表示順ソートのロジ…
