# VrWeb-Front

## 開発ルール

常に最新のdevelopeブランチの状態になるようmerge処理を行う。

### ブランチ
- main: 現在デプロイされているプロダクト
- develope: 開発中バージョンの中心
- feature: 新機能開発を行う際のブランチ(developeから派生させる)
- hotfix: 緊急のバグ修正を行う際のブランチ(developeから派生させる)

開発を行う際は`develope`ブランチから`feature/hotfix`ブランチを作成して行う。

また、ブランチを作成する場合は下記の命名規則に乗っ取り行う。

`feature/[GitHub名]/[開発概要]`

`hotfix/[GitHub名]/[開発概要]`

例: `feature/Sora-210/create_new_page#0`

### PRについて
各開発が終了した際はdevelopeブランチへPRを出す。
