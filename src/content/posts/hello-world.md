---
title: はじめての投稿
date: "2026-05-11"
---

こんにちは！これは **grassLog** の最初の記事です。

このブログは記事を投稿するたびに GitHub にコミットされ、草が生えます。

## 仕組み

1. ブラウザの投稿フォームから記事を送信
2. Cloudflare Workers (Hono) がリクエストを受け取り GitHub Actions を起動
3. GitHub Actions がマークダウンファイルを追加してコミット
4. Cloudflare Pages が自動でリビルド・デプロイ

毎日書けば草が生える。
