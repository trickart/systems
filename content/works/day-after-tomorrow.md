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

<div style="display: flex; align-items: center; gap: 16px; flex-wrap: wrap;">
<a href="https://apps.apple.com/jp/app/dayaftertomorrow/id6763583740?itscg=30200&itsct=apps_box_badge&mttnsubad=6763583740" style="display: inline-block; text-decoration: none; border-bottom: none; box-shadow: none;">
<img src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us?releaseDate=1777161600" alt="App Storeでダウンロード" style="width: 246px; height: 82px; vertical-align: middle; object-fit: contain; border: none;" />
</a>
<img src="/images/day-after-tomorrow-qr.png" alt="あさってアラーム QRコード" style="width: 82px; height: 82px; border: none;" />
</div>

## 特徴

- 3つのスケジュールモード — 時刻のみ（毎日）、日付指定（単発）、毎週（曜日指定）
- タイムゾーン変更への自動対応 — 移動先でも現地時間の意図通りにアラームが鳴るよう再スケジュール
- カスタムサウンド — バンドル済みサウンドに加え、ユーザーが `.caf` / `.wav` / `.aiff` 形式の音源をインポート可能

## 技術スタック

- Swift / SwiftUI
- [AlarmKit](https://developer.apple.com/documentation/alarmkit)
- [GRDB](https://github.com/groue/GRDB.swift)
