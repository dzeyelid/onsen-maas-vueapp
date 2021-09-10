# セルフハンズオン資料

この資料は、[【地方活性化！】MaaS Hands-On with Microsoft Azure【ミニアプリ】](https://linedevelopercommunity.connpass.com/event/220376/) で行うハンズオンの手順をまとめたものです。

## 概要

このリポジトリでは、温泉MaaS を想定するサービスの一つとして、タクシー配車予約サービスをLINE LIFFアプリを用いて実装したアプリケーションのサンプルコードをホストしています。

### 事前の準備

- LINE アカウント
- GitHub アカウント
- Microsoft Azure アカウント

### 流れ

1. LIFFアプリに利用するチャネルを作成する
2. GitHub リポジトリを準備する
3. Azure のリソースを作成する
4. ワークフローを更新する
5. LIFFアプリのエンドポイントを更新し、動作を確認する

----

## 1. LIFFアプリに利用するチャネルを作成する

- [LIFFアプリに利用するチャネルを作成する](./create-line-channels.md)

## 2. GitHub リポジトリを準備する

- フォークする
- Public リポジトリの場合は Branch protection （最低限）を設定する

## 3. Azure のリソースを作成する

まず、Azure のリソースを作成して、アプリケーションを稼働させる環境を整えます。

- [Azure のリソースを作成する](./create-azure-resources.md)

## 4. ワークフローを更新する

LIFFアプリ（静的サイト）に LIFF ID を伝搬させるために、ワークフローを更新します。

- [ワークフローを更新する](./update-workflow.md)

## 6. LIFFアプリのエンドポイントを更新し、動作を確認する

控えておいた Azure Static Web App の URL を、LIFFアプリのエンドポイントとして設定します。

それでは、最後に実際にLINEアプリから、タクシー配車予約サービスの動作確認をしてみましょう！

- [LIFFアプリのエンドポイントを更新する](./update-liff-endpoint-and-congrats.md)