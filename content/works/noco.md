---
title: 'NoCo'
date: '2026-03-01T20:00:00+09:00'
draft: false
summary: 'Apple JavaScriptCore上に構築されたNode.js互換JavaScriptランタイム'
cover:
  image: ''
  alt: 'NoCo'
tags: ['macOS', 'iOS']
---

## 概要

NoCo (Node.js on JavaScriptCore) は、AppleのJavaScriptCoreフレームワーク上に構築された、Node.js互換のJavaScriptランタイムです。V8やNode.js本体を組み込むことなく、多くのNode.jsスクリプトやnpmパッケージをAppleプラットフォーム上でネイティブに実行できます。

名前の由来は日本語の「鋸（のこぎり）」です。

## 特徴

- CommonJS / ESM対応 — `require()` による完全なモジュール解決と、`import`/`export` 構文のサポート
- Node.js組み込みモジュール — `fs`, `path`, `crypto`, `http`, `https`, `http2`, `stream`, `net`, `url`, `zlib`, `child_process`, `dns`, `tls`, `vm`, `worker_threads` 等を実装
- Web Platform APIs — `Headers`, `Request`, `Response`, `ReadableStream`, `AbortController` 等のFetch API互換
- イベントループ — `setTimeout`, `setInterval`, `process.nextTick` および非同期I/O
- 組み込み可能 — `NoCoKit` をライブラリとして自身のSwiftアプリに組み込み可能

## 技術スタック

- Swift
- [JavaScriptCore](https://developer.apple.com/documentation/javascriptcore)
- [SwiftNIO](https://github.com/apple/swift-nio)

## リンク

- [GitHub](https://github.com/trickart/NoCo)
