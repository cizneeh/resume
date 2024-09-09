# 職務経歴書

# 基本情報

| key      | value                                |
| -------- | ------------------------------------ |
| 氏名     | 越前 信次郎(Shinjiro Echizen)        |
| 生年月日 | 1997/08/12                           |
| 居住地   | 東京都                               |
| 最終学歴 | 早稲田大学 基幹理工学部 情報通信学科 |

# 各種リンク

- [Twitter](https://twitter.com/cizneeh)
- [Zenn](https://zenn.dev/cizneeh)
- [GitHub](https://github.com/cizneeh)
- [Web サイト](https://cizneeh.me/)

# スキル

- React, TypeScript を使った SPA 開発（4 年）
- Firebase を使ったアプリケーション開発（3 年）
- GCP を使ったインフラ構築（2 年）
- 少人数（2, 3 人）でのプロジェクトのリード経験
- Next.js（App Router） を使ったアプリケーション開発（個人開発）
- Node.js + Express + MongoDB でのバックエンド API 設計・開発（1 年半）
- Swift, Kotlin でのモバイル開発（1 年半）
- Git, GitHub を使った共同開発の経験（3 年）
- コンピューターサイエンスの知識（アルゴリズム、データ構造、ネットワーク、OS など）
- 勉強会、社内学習コミュニティの形成

# 技術スタック

## プログラミング言語

業務で使用したことのある言語

- TypeScript, JavaScript(ES2015+): 4 年、業務で即戦力になれる
- Swift: 1 年、基本的な機能の実装が出来る
- Kotlin: 1 年、基本的な機能の実装が出来る

個人開発などで使用したことのある言語

- Python: 学生時代に 1 年、基本的なプログラミングが出来る

## フレームワーク、ライブラリ

業務で使用したことのあるもの

- React: 4 年、業務で即戦力になれる
  - Recoil, Tanstack Query, Tanstack Router, Chakra UI, styled-components
  - Vite, Webpack
  - Vitest, Jest
- Express, Electron: 1 年、業務で使用出来る

個人開発などで使用したことのあるもの

## インフラ

- Firebase: 2 年、業務で即戦力になれる
  - Firestore, Firebase Functions, Firebase Authentication
- GCP: 2 年、業務で使用出来る
  - Cloud Run, Cloud Functions, Cloud Tasks, BiqQuery, Pub/Sub,
- MongoDB: 1 年、使用したことがある程度

## その他

業務で使用したことのあるもの

- Node.js: 4 年、業務で即戦力になれる
- Deno: 2 年、業務で使用出来る
- Docker: 2 年、業務で使用出来る
  - キャッシュを意識した Dockerfile が書ける
- Terraform: 1 年、業務で使用出来る
- nginx: 使用したことがある
- Git, GitHub: 4 年、日常的に使用している

# 言語

- 日本語：ネイティブ
- 英語：ビジネスレベル
  - TOEIC960 点
  - 英語で書かれたドキュメントを、日本語と遜色ない速度で読み、理解することができる
  - 口頭、文章共に英語での議論や意見交換を行うことができる

# 職務経歴詳細

## 株式会社 TERASS（2022/12 ～現在）

### SUUMO, athome など複数の不動産ポータルサイトへの一括掲載を行う社内システムの新規開発

物件情報をフォームに入力すると、同じ情報で SUUMO, athome など複数の不動産ポータルサイトへの出稿を行える社内用システム（通称：コンバーター）の新規開発を行いました。

- チーム規模: 5 人（PdM1 + エンジニア 2~4）
- **役割**
  - コーディング、コードレビュー
  - 一部機能の設計
- **業務内容**
  - TypeScript, React(+Recoil, react-hook-form), Chakra UI を使ったフロントエンド開発
  - Firebase(Firestore + Cloud Functions for Firestore)を使ったバックエンド開発
  - PM, PdM と連携、意見交換をしながらの仕様策定
  - Firebase Emulator を使ったローカル開発環境の構築, DX の改善
  - Firebase Emulator を使った自動テスト基盤の構築
    - https://zenn.dev/terass_dev/articles/firebase-functions-test
  - GitHub Actions, Turborepo を用いた CI/CD の構築

フロントエンド開発においては、フォームには 200 を超える入力項目があったため、パフォーマンスの最適化や途中保存機能、フォーム内のナビゲーションといったユーザー体験の向上が大きな課題となりましたが、最適なフックの実装やメモ化を用いて可能な限り最適化を行いながら開発しました。

フロントエンド、バックエンド開発の他に、特に Firebase Emulator を使ったローカル開発環境とテスト基盤の構築を私一人で行いました。Firebase のメリットの１つとして、Firebase Emulator を使ったローカル開発、テストのしやすさがあるため、それをフルに利用しました。

外部 API のモックも用意して完全にローカルに閉じた開発環境を用意することも考えましたが、動作確認がむしろしづらくなると判断して外部の API についてはそのまま利用することにしました。

テストについては、Firebase Emulator と、Firebase 公式のテスト用パッケージを利用し、モックを極力使わず本物の環境に近い状態でテストを実行できるようにしました。
具体的な方法を後に zenn の記事として投稿しました: https://zenn.dev/terass_dev/articles/firebase-functions-test

### GCP のサンドボックスプロジェクトを社員に配る社内システムの設計、開発

- チーム規模: 2 人（エンジニア 2）
- **役割**
  - リードエンジニア
  - アーキテクチャ設計
  - コーディング、コードレビュー
- **業務内容**
  - システムの設計、Design Doc への落とし込み
  - Terraform、GCP を使ったインフラ構成管理
  - Bolt, TypeScript を使った Slack App の開発
  - CI/CD パイプラインの構築（GitHub Actions）

エンジニア社員が自由に使える GCP のサンドボックスプロジェクトを配布する社内システムの新規開発をリードしました。具体的には、技術選定、アーキテクチャ設計、CI/CD 構築、ドキュメント作成、ロードマップ策定などを行い、実装もメインで行いました。

個々のプロジェクトでは、予算制限として 10,000 円のハードリミットを設け、超過すると追加課金を防ぐような構成管理を Terraform を用いて行いました。

また、ユーザーインターフェースとして Slack App を開発し、管理者が手動でプロジェクトを作成する手間を省きました（Slack App が Github Action をトリガーし、terraform apply が実行される形）。

Slack App は Docker コンテナとして Cloud Run にデプロイしました。修正が入った場合にテスト、コンテナのビルド、デプロイが走るように、CI/CD パイプラインを構築しました。

### 不動産エージェントと不動産売買をしたいカスタマーをマッチングするサービス[TERASS Offer](https://offer.terass.com/)の保守・新機能開発

- チーム規模: 4 人（PdM1 + エンジニア 2~3）
- **役割**
  - コーディング、コードレビュー
  - 新機能の仕様策定、設計
- **業務内容**
  - TypeScript, React(+Redux、後に zustand に置き換え), styled-component, Storybook を使ったフロントエンド開発
  - Firebase(Firestore + Cloud Functions for Firestore)を使ったバックエンド開発
  - PM, PdM と連携、意見交換をしながらの仕様策定

プロダクトの保守、新機能開発を行いました。歴史が比較的長いプロダクトだったため、適宜リファクタを行いながら保守・開発を行いました。

---

## ネットコム BB 株式会社（2021/04〜2022/09）

### 社員の所在管理サービス ZAiSEKI の開発・運用

- チーム規模: 5 人
- **役割**：
  - コーディング、コードレビュー
  - API 設計
  - インフラ・開発環境整備
- **業務内容**
  - Node.js + Express + MongoDB(Mongoose)でのバックエンド API 開発
  - Node.js を使った WebSocket サーバー開発（チャット機能）
  - API サーバー・WebSocket サーバーのパフォーマンステストとチューニング
  - Swift, Kotlin でのモバイルアプリ保守・テスト自動化
  - React + TypeScript での新サービスプロトタイプ開発
  - Electron を利用した社内ツール開発
  - 開発・本番環境への Docker 導入、インフラ整備
  - 社内勉強会の企画、発表

基本的に人が足りていなかったため、チーム内でバックエンドやモバイルなどで明確に役割を区切るのではなく、適宜必要な知識を補いながら開発していきました。

当初チャット機能は REST API サーバーを使用し、ポーリングでメッセージを取得する予定でしたが、急遽メッセージのリアルタイム更新が求められるようになり、WebSocket の導入が必要となりました。その設計~開発を私 1 人で行いました。

また、本番環境への Docker 導入が必要となった際、当時チームに Docker の本番環境での運用経験のあるメンバーがいなかったため私が一人で導入を行いました。導入後には社内で勉強会を主催しました。

# 業務外活動

## 技術記事投稿

- **Zenn**
  - 2022/03 より投稿開始。
  - https://zenn.dev/cizneeh

## 個人開発

- [個人ブログ](https://cizneeh.me/)
