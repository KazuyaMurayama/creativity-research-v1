# Creativity Research v1 — 創造性研究AIシステム

> 創造性・クリエイティビティに関する最新研究・事例をAIが収集・分析するシステムです。

## 📋 概要

創造性・クリエイティビティに関する最新研究・事例をAIが収集・分析するシステムです。学術論文・実践事例・インタビューを横断的に調査し、創造性向上のインサイトを抽出します。

## ✨ 主な機能

- 創造性関連論文・記事の自動収集
- テーマ別クラスタリング・分類
- インサイト抽出・要約レポート生成
- 創造性向上施策の提案
- 時系列トレンド分析

## 🛠️ 技術スタック

| カテゴリ | 技術・ライブラリ |
|----------|----------------|
| 言語 | Python 3.10+ |
| AIフレームワーク | Claude API |
| データ収集 | requests, BeautifulSoup |
| 分析 | pandas, scikit-learn |

## 🚀 セットアップ

### 前提条件

- Python 3.9 以上
- APIキー（Claude / OpenAI 等）を `.env` ファイルに設定

### インストール

```bash
git clone https://github.com/KazuyaMurayama/creativity-research-v1.git
cd creativity-research-v1
pip install -r requirements.txt
```

### 環境設定

```bash
cp .env.example .env
# .env ファイルに必要なAPIキーを設定
```

## 💻 使い方

```bash
python research.py
```

## 👨‍💻 開発者情報

**男座員也（Kazuya Oza / おざ かずや）**

| | |
|---|---|
| GitHub | [@KazuyaMurayama](https://github.com/KazuyaMurayama) |
| 専門領域 | データサイエンス・生成AIコンサルタント |
| 主要スキル | Python, LightGBM, LangChain, RAG, Streamlit, React, TypeScript |
| 事業 | AIコンサルティング（月単価目標300万円）/ SaaS開発 / 定量投資 |

## 📄 ライセンス

© 2025 男座員也（Kazuya Oza）. All rights reserved.

---

> このリポジトリは **男座員也（Kazuya Oza）** が開発・管理しています。
> 命名・ドキュメント等での表記は必ず **男座員也** または **Kazuya Oza** を使用してください。
