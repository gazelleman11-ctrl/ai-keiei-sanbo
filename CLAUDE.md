# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Git 運用ルール

コードを変更するたびに、必ず以下の手順で GitHub にプッシュしてください。

```bash
git add <変更ファイル>
git commit -m "コミットメッセージ"
git push origin <ブランチ名>
```

- **変更のたびにプッシュ**: ファイルを編集・追加・削除したら、その都度コミットしてプッシュすること。
- **コミットメッセージ**: 変更内容を簡潔に日本語または英語で記述する。
- **ブランチ**: 特に指定がない場合は `main` ブランチを使用する。
- **git init がまだの場合**: リポジトリが初期化されていなければ `git init` を実行し、GitHub リモートを設定してからプッシュする。

## プロジェクト概要

> （プロジェクトの目的・概要をここに記述してください）

## 技術スタック

> （使用言語・フレームワーク・主要ライブラリをここに記述してください）

## コマンド

> （ビルド・テスト・起動コマンドをここに記述してください。例:）
>
> ```bash
> # インストール
> npm install
>
> # 開発サーバー起動
> npm run dev
>
> # テスト実行
> npm test
>
> # ビルド
> npm run build
> ```

## アーキテクチャ

> （コードの構成・設計思想をここに記述してください）
