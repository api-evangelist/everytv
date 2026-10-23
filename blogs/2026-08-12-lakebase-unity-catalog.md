---
title: "LakebaseはUnity Catalogのデータをアプリに届ける選択肢になるか"
url: "https://tech.every.tv/entry/2026/08/12/153721?utm_source=feed"
date: "2026-08-12"
author: "haruya-mitsuzawa"
feed_url: "https://tech.every.tv/feed"
---
はじめに こんにちは、開発1部でデリッシュキッチンの開発をしている蜜澤です。 現在データ基盤はDatabricksを使用しており、データはUnity Catalog（以下UC）のテーブルです。 UCのテーブルをプロダクトのAPIから配信したいという状況が直近の1年で増えてきました。 例えば、「レコメンド結果をアプリの画面に出したい」「集計したアプリのログデータを分析できる社外向けのダッシュボードツールを作成したい」といった要望があります。 これをアプリ側から読めるようにするには、UCのテーブルのデータをAPIが参照できるDBに複製する必要があります。DatabricksのLakebase（マネ…
