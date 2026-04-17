---
title: 'あさってアラーム'
date: 2026-04-17
draft: false
summary: '翌日以降のアラームを設定できるiOSアプリ'
cover:
  image: '/images/day-after-tomorrow.png'
  alt: 'あさってアラーム'
tags: ['iOS']
---

## 概要

あさってアラームは、翌日以降の特定の日付に向けてアラームを設定できるiOSアプリです。標準の時計アプリでは扱いづらい「あさっての朝だけ早く起きたい」といった単発の予定に特化し、デフォルトで明後日の日付が選択された状態から素早くアラームを登録できます。

## 特徴

- 3つのスケジュールモード — 時刻のみ（毎日）、日付指定（単発）、毎週（曜日指定）
- タイムゾーン変更への自動対応 — 移動先でも現地時間の意図通りにアラームが鳴るよう再スケジュール
- カスタムサウンド — バンドル済みサウンドに加え、ユーザーが `.caf` / `.wav` / `.aiff` 形式の音源をインポート可能

## 技術スタック

- Swift / SwiftUI
- [AlarmKit](https://developer.apple.com/documentation/alarmkit)
- [GRDB](https://github.com/groue/GRDB.swift)
