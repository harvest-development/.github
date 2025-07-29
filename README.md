# .github のREADME
## 共通設定
GitHub CLI のインストール、セットアップ方法は以下を参照


https://docs.github.com/ja/github-cli/github-cli/quickstart

### label作成ghコマンド
参考：https://cli.github.com/manual/gh_label
#### 一括実行
`-- force`を使用することで、descriptionとcolorを置き換えることができる。


※ descriptionを空文字で置き換えることができないため、そこは手動の作業が必要
```
gh label create BE --description "バックエンド" --color #e21f7e --force && \
gh label create CI/CD --description "CI/CD" --color #cffdf8 --force && \
gh label create EG --description "エンジン" --color #cc7d3f --force && \
gh label create FE --description "フロントエンド" --color #0e8a16 --force && \
gh label create INFRA --description "インフラ" --color #5750cc --force && \
gh label create ドキュメント --color #0075ca --force && \
gh label create バグ修正 --color #d73a4a --force && \
gh label create 企画 --color #34edff --force && \
gh label create 分析 --color #0683fb --force && \
gh label create 実装 --color #008672 --force && \
gh label create 機能改善 --color #e4e669 --force && \
gh label create 機能追加 --color #d876e3 --force && \
gh label create 環境構築 --color #006b75 --force && \
gh label create 設計 --color #4a92c2 --force && \
gh label create 調査 --color #e527dd --force
```
#### 個別
```
gh label create BE --description "バックエンド" --color #e21f7e --force
```
```
gh label create CI/CD --description "CI/CD" --color #cffdf8 --force
```
```
gh label create EG --description "エンジン" --color #cc7d3f --force
```
```
gh label create FE --description "フロントエンド" --color #0e8a16 --force
```
```
gh label create INFRA --description "インフラ" --color #5750cc --force
```
```
gh label create ドキュメント --color #0075ca --force
```
```
gh label create バグ修正 --color #d73a4a --force
```
```
gh label create　企画 --color #34edff --force
```
```
gh label create 分析 --color #0683fb --force
```
```
gh label create 実装 --color #008672 --force
```
```
gh label create 機能改善 --color #e4e669 --force
```
```
gh label create 機能追加 --color #d876e3 --force
```
```
gh label create 環境構築 --color #006b75 --force
```
```
gh label create 設計 --color #4a92c2 --force
```
```
gh label create 調査 --color #e527dd --force
```
