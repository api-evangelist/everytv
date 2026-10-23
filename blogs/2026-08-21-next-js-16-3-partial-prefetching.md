---
title: "Next.js 16.3のPartial Prefetchingをプロダクトで検証してみる"
url: "https://tech.every.tv/entry/2026/08/21/131147?utm_source=feed"
date: "2026-08-21"
author: "chronoll"
feed_url: "https://tech.every.tv/feed"
---
目次 はじめに Partial Prefetchingは何を解決するのか すべてを先読みする方法と、何も先読みしない方法の中間を作る OISHYでPartial Prefetchingを試す 検証条件 計測方法 実験1：クリック前の取得を減らすと、通信と遷移はどう変わるか 実験2：URL固有のデータを待つ間に何が見えるか 補足：適用範囲によって先読みの形が異なった まとめ 参考文献 はじめに こんにちは、開発本部の黒髙です。最近はアメリカ向けレシピサービスであるOISHYの開発に関わっています。 Next.js 16.3では、ページ遷移の応答性を改善する仕組みとしてInstant Naviga…
