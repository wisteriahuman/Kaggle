# Kaggle Competitions (Root-Repository)

Kaggle のコンペティションごとに作成された、独立したGitリポジトリ（サブモジュール）を管理するためのルートリポジトリです

## 概要

このリポジトリ自体にはコードを含みません。
取り組んだ各コンペティションのリポジトリを **Gitサブモジュール** として集約・管理しています。

## セットアップ方法

このリポジトリと、管理下にあるすべてのコンペティション（サブモジュール）を一度にクローンします。

```bash
# このリポジトリと、登録されているサブモジュールを再帰的（recursive）にクローンする
git clone --recursive https://github.com/wisteriahuman/Kaggle.git
```

すでにこのリポジトリをクローン済みの場合は、以下のコマンドでサブモジュールを初期化・取得できます。

```bash
# サブモジュールの初期化と更新
git submodule update --init --recursive
```

