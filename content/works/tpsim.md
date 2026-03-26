---
title: 'tpsim'
date: 2026-03-01
draft: false
summary: 'ESC/POSプロトコル対応サーマルプリンタシミュレータ'
cover:
  image: ''
  alt: 'tpsim'
tags: ['macOS', 'Linux', 'CLI']
---

## 概要

tpsim (Thermal Printer Simulator) は、ESC/POSプロトコルで通信するサーマルプリンタのシミュレータです。TCPポート9100でサーバーが起動し、受信したコマンドをターミナル上にレシート風にレンダリングします。

## 特徴

- ESC/POSコマンド解析 — ESC/POSプロトコルのコマンドを解析し、テキストをレンダリング
- Sixelグラフィックス対応 — 対応ターミナルでの画像表示に対応
- 非同期TCPサーバー — SwiftNIOによる高性能な非同期サーバー実装
- クロスプラットフォーム — macOSおよびLinuxで動作

## 技術スタック

- Swift
- [SwiftNIO](https://github.com/apple/swift-nio)

## リンク

- [GitHub](https://github.com/trickart/tpsim)
