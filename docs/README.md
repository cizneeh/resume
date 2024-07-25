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

- React, TypeScript を使った SPA 開発（3 年）
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

## プログラミング言語（得意な順）

TypeScript, JavaScript(ES2015+), Swift, Kotlin

## フレームワーク、ライブラリ（得意な順）

React, Next.js, Vitest, Jest, Express, Electron

## インフラ、DB（得意な順）

Firebase（Firestore, Firebase Functions, Firebase Authentication）, GCP（Cloud Run, Cloud Functions, BiqQuery）, MongoDB

## その他

Node.js, Vite, Docker, nginx, Git, GitHub

# 言語

- 日本語：ネイティブ
- 英語：ビジネスレベル
  - TOEIC960 点
  - 英語で書かれたドキュメントを、日本語と遜色ない速度で読み、理解することができる
  - 口頭、文章共に英語での議論や意見交換を行うことができる

# 職務経歴詳細

## 株式会社 TERASS（2022/12 ～現在）

### SUUMO, athome など複数の不動産ポータルサイトへの一括掲載を行う社内システムの新規開発

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

物件情報をフォームに入力すると、同じ情報で SUUMO, athome など複数の不動産ポータルサイトへの出稿を行える社内用システム（通称：コンバーター）の新規開発を行いました。

フロントエンド開発においては、フォームには 200 を超える入力項目があったため、パフォーマンスの最適化や途中保存機能、フォーム内のナビゲーションといったユーザー体験の向上が大きな課題となりましたが、最適なフックの実装やメモ化を用いて可能な限り最適化を行いながら開発しました。

### GCP のサンドボックスプロジェクトを社員に配る社内システムの設計、開発

- チーム規模: 2 人（エンジニア 2）
- **役割**
  - リードエンジニア
  - アーキテクチャ設計
  - コーディング、コードレビュー
- **業務内容**
  - システムの設計、Design Doc への落とし込み
  - Terraform を使ったインフラ構成管理
  - Bolt を使った Slack App の開発

エンジニア社員が自由に使える GCP のサンドボックスプロジェクトを配布する社内システムの新規開発をリードしました。具体的には、技術選定、アーキテクチャ設計、ドキュメント作成、タスクの切り分けとアサインなどを行いました。

個々のプロジェクトでは、予算制限として 10,000 円のハードリミットを設け、超過すると追加課金を防ぐような構成管理を Terraform を用いて行いました。

また、ユーザーインターフェースとして Slack アプリを開発し、管理者が手動でプロジェクトを作成する手間を省きました。

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

基本的に人が足りていなかったため、チーム内でバックエンドやモバイルなどで明確に役割を区切るのではなく、適宜必要な知識を勉強して開発していきました。

途中の仕様変更で本番環境への Docker 導入が必要となった際、当時チームに Docker の本番環境での運用経験のあるメンバーがいなかったため私が一人で導入を行いました。導入後には社内で勉強会を主催しました。

# 業務外活動

## 技術記事投稿

- **Zenn**
  - 2022/03 より投稿開始。
  - https://zenn.dev/cizneeh

## 個人開発

- [個人ブログ](https://cizneeh.me/)
