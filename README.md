# 編集者のためのGitHub講座 📝

非エンジニアの編集者・ライター・コンテンツ制作者向けに、**GitHubの基本操作をハンズオンで学べる**講座用テンプレートリポジトリです。

このリポジトリは **GitHub Template Repository** として設計されています。  
「Use this template」ボタンから自分のアカウントに複製して、実際に手を動かしながら学習してください。

---

## この講座の対象者

- 編集者・ライター・校正者・コンテンツマネージャー
- Markdownで文章を書く機会がある人
- チームで原稿のレビューやバージョン管理をしたい人
- 「GitやGitHubってエンジニアだけのもの」と思っている人
- ローカルのターミナル操作はできるだけ避けたい人

**すべてブラウザ上のGitHub Web UIだけで完結**します。  
`git` コマンドやローカル環境構築は不要です。

---

## 講座のゴール

この講座を終えると、以下ができるようになります。

1. GitHubでリポジトリを作成・管理できる
2. Markdownファイルをブラウザ上で編集・コミットできる
3. ブランチを切って作業し、Pull Requestでレビュー依頼ができる
4. Issueでタスクを管理できる
5. 編集部の原稿制作フローをGitHub上で回せるようになる

---

## 講座の進め方

1. このリポジトリの右上 **「Use this template」→「Create a new repository」** をクリック
2. 自分のアカウントに複製（Public推奨）
3. 複製したリポジトリの `lessons/` フォルダを順番に進める
4. 各レッスンの末尾にある「やってみよう」を実際に操作する

---

## カリキュラム一覧

| # | レッスン | 内容 |
|---|---------|------|
| 00 | [はじめに](lessons/00-introduction.md) | 講座の全体像と心構え |
| 01 | [GitHubって何？](lessons/01-what-is-github.md) | GitHubの基本概念 |
| 02 | [アカウントとリポジトリ](lessons/02-account-and-repo.md) | アカウント作成・リポジトリの作り方 |
| 03 | [ファイルを編集する](lessons/03-edit-files.md) | ブラウザ上での編集とコミット |
| 04 | [Markdownの基本](lessons/04-markdown-basics.md) | 編集者が知っておくべきMarkdown |
| 05 | [ブランチで安全に作業する](lessons/05-branches.md) | ブランチの考え方と作り方 |
| 06 | [Pull Requestでレビューする](lessons/06-pull-requests.md) | 編集部のレビューフロー |
| 07 | [Issueでタスク管理](lessons/07-issues.md) | 原稿管理・進捗管理 |
| 08 | [チームで共同編集](lessons/08-collaboration.md) | Collaborators・権限・運用ルール |
| 09 | [実践：原稿制作ワークフロー](lessons/09-editorial-workflow.md) | 編集部を想定した一連の流れ |
| 10 | [次のステップ](lessons/10-next-steps.md) | さらに学びたい人へ |

---

## ファイル構成

```
editors-github-course/
├── README.md                 ← このファイル
├── lessons/                  ← 各レッスン資料
│   ├── 00-introduction.md
│   ├── 01-what-is-github.md
│   └── ...
├── exercises/                ← 練習用ファイル
│   ├── sample-article.md
│   └── practice-readme.md
├── templates/                ← 編集部で使えるテンプレート
│   ├── article-template.md
│   ├── pr-template.md
│   └── issue-template.md
└── docs/
    └── editorial-guidelines.md  ← 編集部向け運用ガイド例
```

---

## このテンプレートの使い方（講座主催者向け）

1. このリポジトリを **Template repository** に設定する  
   （Settings → General → Template repository にチェック）
2. 参加者に「Use this template」で複製してもらう
3. 必要に応じて `lessons/` の内容をカスタマイズ
4. 社内・コミュニティの編集者向け勉強会に活用

---

## ライセンス

MIT License  
自由に改変・再配布・社内利用してください。

---

**Let's start editing with GitHub!** ✍️
