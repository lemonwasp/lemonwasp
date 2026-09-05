<div align="center">

# Taegwan Hong

### 日本で働くバックエンドエンジニア

**Architecture · Data · Reliability · Automation** を軸に、
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

## 👨‍💻 About Me

日本でソフトウェアエンジニアとして働きながら、主に**バックエンドエンジニアリング**を学んでいます。

「動く機能を作る」だけではなく、なぜそのアーキテクチャやデータ構造、インフラ構成が必要なのかを理解することを重視しています。新しい技術は単独で学ぶより、実際のアプリケーションへ段階的に導入し、小さくレビュー可能な改善として積み重ねるスタイルを好みます。

| 項目 | 内容 |
| --- | --- |
| 📍 **拠点** | 日本 |
| 🧭 **中心領域** | Backend Engineering |
| 🔧 **現在の重点** | Architecture · Databases · Testing · Reliability |
| 🚀 **今後伸ばす領域** | Cloud · Distributed Systems · Applied AI |

---

## 🎯 Current Focus

| Area | Focus |
| --- | --- |
| **Backend Engineering** | C# · .NET · Java · TypeScript · SQL |
| **Deepening** | Architecture · Database Design · Testing · CI/CD |
| **Expanding Into** | Cloud Infrastructure · Performance · Observability |
| **Exploring** | Distributed Systems · AI-enabled Software |

---

# 🚀 Featured Projects

## 🏗️ Dotnet Backend Study

> シンプルなASP.NET MVC CRUDアプリケーションを、保守しやすいバックエンドシステムへ段階的に発展させる学習プロジェクト。

単純なCRUDから出発し、アーキテクチャ、永続化、依存関係管理、テスト、例外処理、ロギングなどを既存システムへ一つずつ導入しています。

### 主な実装

- Controller → Service → Repository構成
- Repository抽象化とUnityによるDependency Injection
- Entity Framework 6 + SQL Server LocalDB
- Code First Migrations
- DTO／Entity分離とAutoMapper
- Service層バリデーション
- HTTP 400／404／500の共通例外処理
- log4netによるアプリケーションログ
- MSTestによるService層Unit Test
- サーバーサイドPagination
- Vue.js Frontend連携

**Current:** Server-side pagination completed  
**Next:** Search / Filtering

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

### Stack

`Java 21` · `Jakarta Servlet` · `JSP` · `JavaScript` · `MySQL 8` · `Apache Tomcat 10`

➡️ [Tsunagaroom](https://github.com/lemonwasp/tsunagaroom)

---

## 🍽️ Let Eat Go

> 食事をきっかけに人と人をつなぐソーシャルダイニングプラットフォーム。

4名のチームで、Frontend、Backend、AI Serviceを分離して開発したプロジェクトです。

### 主な担当

- 初期Entity設計
- Authentication Flow
- Album Backend
- Chat Room Entity Relation
- Comment DTO修正
- S3画像削除処理

### Platform Highlights

- Next.js + NestJS
- PostgreSQL + TypeORM
- JWT + Google／Kakao OAuth
- Socket.IOによるReal-time Chat
- AWS S3画像管理
- FastAPI AI Service
- Docker + GitHub Actions
- AWS ECS／ECR Deployment

➡️ [Frontend](https://github.com/YJU-5/project-leteatgo-nextjs-repo)  
➡️ [Backend](https://github.com/YJU-5/project-leteatgo-nestjs-repo)

---

## 🤖 AI Lead Conversion Platform

> 2024年にドイツ・ウルムで開発したAIハッカソンのプロトタイプを、プライバシーに配慮し再現可能な形で再構築するプロジェクト。

公開版では元の企業データや社内資料を使用せず、合成CRMデータのみでMachine Learning Pipeline、Prediction API、Dashboard、LLM支援機能を再構築しています。

### 現在の進捗

- Public／Private Data Boundaryの文書化
- FastAPI Health Endpointと自動テスト
- Historical Lead／Note Data Relationの再構築
- 公開情報に基づくAggregate CRM Profileの文書化
- Privacy-safe Synthetic Data Generator

### Engineering Goals

- Leakage-safe ML Evaluation
- Reproducible Preprocessing / Feature Pipeline
- Prediction / Explanation API
- React / TypeScript Dashboard
- Human-reviewed LLM-assisted Outreach
- Tests · Docker · CI

➡️ [AI Lead Conversion Platform](https://github.com/lemonwasp/ai-lead-conversion-platform)

---

# 🧰 Technology Landscape

## ⭐ Core

`C#` · `.NET` · `Java` · `TypeScript` · `Python` · `SQL`

## ⚙️ Backend & APIs

`ASP.NET MVC` · `Entity Framework` · `NestJS` · `FastAPI` · `Rails` · `Jakarta Servlet`

## 🗄️ Database & Data

`PostgreSQL` · `SQL Server` · `MySQL` · `SQLite` · `PostGIS` · `Supabase`

## ☁️ Infrastructure & Quality

`Docker` · `AWS` · `Azure` · `Linux` · `GitHub Actions` · `MSTest` · `Selenium`

## 🤖 AI / Machine Learning

`PyTorch` · `Hugging Face Transformers` · `Azure OpenAI` · `LangChain`

---

# 🌍 Global Experience

| Country | Experience |
| --- | --- |
| 🇯🇵 **Japan** | Software engineering career · Japanese IT environment |
| 🇩🇪 **Germany** | 1-month intensive AI training · ML / Deep Learning / Azure OpenAI · Hackathon winning team |
| 🇺🇿 **Uzbekistan** | 1-week international internship |
| 🇷🇴 **Romania** | 1-month independent stay · Romanian language learning |
| 🇰🇷 **Korea** | Software engineering education · Team / Personal projects |

異なる環境で学び、生活し、開発する経験を通じて、新しいチームや文化へ適応しながら協働する力を磨いています。

---

# 🗣️ Languages

| Language | Level |
| --- | --- |
| 🇰🇷 Korean | Native |
| 🇯🇵 Japanese | C1 · Business level · JLPT N1 |
| 🇬🇧 English | B2 · Business level · TOEIC Speaking AL |
| 🇩🇪 German | A1 · 初級 |
| 🇷🇴 Romanian | A1 · Beginner · Currently learning |

---

# 💡 Engineering Philosophy

新しい技術やアーキテクチャパターンを導入するときは、次の問いを意識しています。

> **なぜ必要なのか？**  
> **どの問題を解決するのか？**  
> **どこに配置すべきなのか？**  
> **どのようなトレードオフがあるのか？**

**Build → Find a limitation → Understand → Improve → Test → Review → Repeat**

実装力だけでなく、設計・データ・信頼性・システム全体を理解できるエンジニアへ成長することを目標にしています。
