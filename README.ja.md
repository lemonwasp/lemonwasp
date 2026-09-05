<div align="center">

# Taegwan Hong

### 日本で働くバックエンドエンジニア

**アーキテクチャ · データ · 信頼性 · 自動化** を軸に、
実装だけでなく、設計・データ・システム全体を理解できるエンジニアを目指しています。

<br>

[English](README.md) | **日本語**

<br>

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

</div>

---

## 👨‍💻 自己紹介

日本でソフトウェアエンジニアとして働きながら、主に**バックエンドエンジニアリング**を学んでいます。

「動く機能を作る」だけではなく、なぜそのアーキテクチャやデータ構造、インフラ構成が必要なのかを理解することを重視しています。新しい技術は単独で学ぶより、実際のアプリケーションへ段階的に導入し、小さくレビュー可能な改善として積み重ねるスタイルを好みます。

| 項目 | 内容 |
| --- | --- |
| 📍 **拠点** | 日本 |
| 🧭 **中心領域** | バックエンドエンジニアリング |
| 🔧 **現在の重点** | アーキテクチャ · データベース · テスト · 信頼性 |
| 🚀 **今後伸ばす領域** | クラウド · 分散システム · 応用AI |

---

## 🎯 現在の注力領域

| 領域 | 内容 |
| --- | --- |
| **バックエンド開発** | C# · .NET · Java · TypeScript · SQL |
| **深掘り中** | アーキテクチャ · データベース設計 · テスト · CI/CD |
| **拡張中** | クラウドインフラ · パフォーマンス · オブザーバビリティ |
| **探索中** | 分散システム · AI活用ソフトウェア |

---

# 🚀 主なプロジェクト

## 🏗️ Dotnet Backend Study

> シンプルなASP.NET MVC CRUDアプリケーションを、保守しやすいバックエンドシステムへ段階的に発展させる学習プロジェクト。

単純なCRUDから出発し、アーキテクチャ、永続化、依存関係管理、テスト、例外処理、ロギングなどを既存システムへ一つずつ導入しています。

### 主な実装

- Controller → Service → Repository構成
- Repository抽象化とUnityによる依存性注入（DI）
- Entity Framework 6 + SQL Server LocalDB
- Code Firstによるマイグレーション
- DTO／Entity分離とAutoMapper
- Service層のバリデーション
- HTTP 400／404／500の共通例外処理
- log4netによるアプリケーションログ
- MSTestによるService層の単体テスト
- サーバーサイドページネーション
- Vue.jsフロントエンド連携

**現在:** サーバーサイドページネーション完了  
**次:** 検索／フィルタリング

➡️ [Dotnet Backend Study](https://github.com/lemonwasp/dotnet-study)

---

## 👥 Tsunagaroom

> 高齢者と家族を非同期ビデオコミュニケーションでつなぐJava／JSP Webアプリケーション。

8名のチームプロジェクトで、主に**開発・システム設計**を担当しました。

### 主な担当

- 画面・サーバー処理フローの設計
- Servlet → Logic → DAO処理モデルの構造化
- 動画再生とリアクション自動録画の連携設計
- 未読／既読状態の処理ルール設計
- 実装仕様書の作成
- 正常系・境界値・例外系テストケースの設計
- 実装レビューと仕様調整

### 技術スタック

`Java 21` · `Jakarta Servlet` · `JSP` · `JavaScript` · `MySQL 8` · `Apache Tomcat 10`

➡️ [Tsunagaroom](https://github.com/lemonwasp/tsunagaroom)

---

## 🍽️ Let Eat Go

> 食事をきっかけに人と人をつなぐソーシャルダイニングプラットフォーム。

4名のチームで、フロントエンド、バックエンド、AIサービスを分離して開発したプロジェクトです。

### 主な担当

- 初期エンティティ設計
- 認証フロー
- アルバム機能のバックエンド
- チャットルームのエンティティ関連設計
- Comment DTOの修正
- S3画像削除処理

### プラットフォームの特徴

- Next.js + NestJS
- PostgreSQL + TypeORM
- JWT + Google／Kakao OAuth
- Socket.IOによるリアルタイムチャット
- AWS S3による画像管理
- FastAPIによるAIサービス連携
- Docker + GitHub Actions
- AWS ECS／ECRによるデプロイ

➡️ [フロントエンドリポジトリ](https://github.com/YJU-5/project-leteatgo-nextjs-repo)  
➡️ [バックエンドリポジトリ](https://github.com/YJU-5/project-leteatgo-nestjs-repo)

---

## 🤖 AI Lead Conversion Platform

> 2024年にドイツ・ウルムで開発したAIハッカソンのプロトタイプを、プライバシーに配慮し再現可能な形で再構築するプロジェクト。

公開版では元の企業データや社内資料を使用せず、合成CRMデータのみで機械学習パイプライン、予測API、ダッシュボード、LLM支援機能を再構築しています。

### 現在の進捗

- 公開／非公開データ境界の文書化
- FastAPIヘルスチェックエンドポイントと自動テスト
- 過去のリード／ノートデータ関係の再構築
- 公開情報に基づく集計CRMプロファイルの文書化
- プライバシーに配慮した合成データ生成器

### 技術目標

- データリークを防いだML評価
- 再現可能な前処理／特徴量パイプライン
- 予測／説明API
- React / TypeScriptダッシュボード
- 人間のレビューを前提としたLLM支援アウトリーチ
- 自動テスト · Docker · CI

➡️ [AI Lead Conversion Platform](https://github.com/lemonwasp/ai-lead-conversion-platform)

---

# 🧰 技術スタック

## ⭐ 主要技術

`C#` · `.NET` · `Java` · `TypeScript` · `Python` · `SQL`

## ⚙️ バックエンド & API

`ASP.NET MVC` · `Entity Framework` · `NestJS` · `FastAPI` · `Rails` · `Jakarta Servlet`

## 🗄️ データベース & データ

`PostgreSQL` · `SQL Server` · `MySQL` · `SQLite` · `PostGIS` · `Supabase`

## ☁️ インフラ & 品質

`Docker` · `AWS` · `Azure` · `Linux` · `GitHub Actions` · `MSTest` · `Selenium`

## 🤖 AI / 機械学習

`PyTorch` · `Hugging Face Transformers` · `Azure OpenAI` · `LangChain`

---

# 🌍 海外経験

| 国 | 経験 |
| --- | --- |
| 🇯🇵 **日本** | ソフトウェアエンジニアとして勤務 · 日本のIT環境 |
| 🇩🇪 **ドイツ** | 1か月のAI集中研修 · ML / Deep Learning / Azure OpenAI · ハッカソン優勝チーム |
| 🇺🇿 **ウズベキスタン** | 1週間の国際インターンシップ |
| 🇷🇴 **ルーマニア** | 1か月の個人滞在 · ルーマニア語学習 |
| 🇰🇷 **韓国** | ソフトウェア工学教育 · チーム／個人開発プロジェクト |

異なる環境で学び、生活し、開発する経験を通じて、新しいチームや文化へ適応しながら協働する力を磨いています。

---

# 🗣️ 言語

| 言語 | レベル |
| --- | --- |
| 🇰🇷 韓国語 | ネイティブ |
| 🇯🇵 日本語 | C1 · ビジネスレベル · JLPT N1 |
| 🇬🇧 英語 | B2 · ビジネスレベル · TOEIC Speaking AL |
| 🇩🇪 ドイツ語 | A1 · 初級 |
| 🇷🇴 ルーマニア語 | A1 · 初級 · 学習中 |

---

# 💡 エンジニアリングに対する考え方

新しい技術やアーキテクチャパターンを導入するときは、次の問いを意識しています。

> **なぜ必要なのか？**  
> **どの問題を解決するのか？**  
> **どこに配置すべきなのか？**  
> **どのようなトレードオフがあるのか？**

**作る → 課題を見つける → 理解する → 改善する → テストする → 振り返る → 繰り返す**

実装力だけでなく、設計・データ・信頼性・システム全体を理解できるエンジニアへ成長することを目標にしています。