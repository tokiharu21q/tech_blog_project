# Astro Starter Kit: Basics

```sh
pnpm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
"# tech_blog_project" 


# ✅ 技術ブログ開発タスクリスト（MVP観点）

## 🚩MVPに必要な要素（実装対象・必須）

### 1. プロジェクト初期化と環境構築（約1.5h）

-  Node.js / パッケージマネージャのセットアップ
    
-  Cursor で開発環境構築
    
-  GitHub リポジトリ作成・初期コミット
    

### 2. Astro プロジェクト作成（約1.5h）

-  `pnpm create astro@latest` によるセットアップ
    
-  最低限のディレクトリ構造確認と `.astro` ページの作成
    

### 3. コンテンツ配信（Markdown対応）（約2.0h）

-  Markdown から記事を読み込む設定（`astro:content`）
    
-  ブログ一覧ページ（ループ）
    
-  詳細ページ（`[slug].astro`）のルーティング
    

### 4. UI/デザイン（約1.5h）

-  TailwindCSS の導入
    
-  ベーシックなレイアウト（ヘッダー・フッター）作成
    
-  モバイル対応（最低限）
    

### 5. デプロイと共有（約1.0h）

-  GitHub → Vercel によるデプロイフロー構築
    
-  公開URLで動作確認
    

### 🔸工数合計：約7.5時間

→ **この時点で技術ブログとして外部共有可能な最小構成が成立**

---

## 🕊️ Nice to Have（MVP以降に実装を検討）

### デザイン・UX改善

-  Tailwind UI の採用
    
-  アニメーションやホバー効果追加
    
-  OGP / SNS シェア機能の追加
    

### コンテンツ機能の拡張

-  記事のタグ・カテゴリ分類
    
-  Draft 記事の表示制御
    
-  記事の検索・フィルター機能
    

### 技術的拡張

-  React コンポーネントの統合
    
-  コメント機能（例：Giscus, Disqus）
    
-  アクセス解析（Google Analytics / Plausible）
    

### CI/CD自動化

-  GitHub Actions によるビルド検証
    
-  Preview Deploy 対応
    

### パフォーマンス・品質対応

-  画像最適化・Lazy Load
    
-  Lighthouse による改善対応
    

---

# 🧭 推奨する進行ステップ

1. ✅ **MVP完了まで突き進む（〜7.5h）**
    
2. ✅ デプロイ後、URLを社内共有
    
3. ✅ フィードバックを収集
    
4. 🕊️ 必要に応じて機能追加や改善を段階的に行う
    
