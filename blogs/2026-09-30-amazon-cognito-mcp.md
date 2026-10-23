---
title: "Amazon Cognito で MCP サーバーを認可するときのクライアント登録について"
url: "https://tech.every.tv/entry/2026/09/30/150126?utm_source=feed"
date: "2026-09-30"
author: "yoshiki_sugimori"
feed_url: "https://tech.every.tv/feed"
---
はじめに こんにちは、リテールハブ開発部の杉森です。 社内向けのリモート MCP サーバーを Amazon Bedrock AgentCore Gateway 上に構築する検証を進めており、認証には Amazon Cognito を使っています。Claude のカスタムコネクタや Claude Code から OAuth で接続する構成を調べる中で、MCP のクライアント登録の方式と、それに対する Cognito の対応状況が気になったので調べてみました。 本記事では、調べた内容の整理と、検証環境で実際に接続を試した結果を紹介します。内容は 2026 年 9 月時点の情報に基づいています。 M…
