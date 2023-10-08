# 職務経歴書

View on [GitHub Pages](https://cizneeh.github.io/resume/)

## 基本情報

|key|value|
|---|---|
|氏名|越前 信次郎(Shinjiro Echizen)|
|生年月日|1997/08/12|
|居住地|東京都|
|最終学歴|早稲田大学 基幹理工学部 情報通信学科|

## Socials
- [Twitter](https://twitter.com/cizneeh)
- [Zenn](https://zenn.dev/cizneeh)
- [GitHub](https://github.com/cizneeh)
- [Blog](https://cizneeh.me/)

## スキル

- React, TypeScript（+Next.js）を使ったフロントエンド開発（1年）
- Firebase, GCPを使ったバックエンド、インフラ構築（1年）
- Node.js + Express + MongoDBでのバックエンドAPI設計・開発（1年半）
- Swift, Kotlinでのモバイル開発（1年半）
- 勉強会、社内学習コミュニティの形成

## 技術スタック

### プログラミング言語（得意な順）
TypeScript, JavaScript(ES2015+), Swift, Kotlin

### フレームワーク、ライブラリ（得意な順）
React, Next.js, Vitest, Jest, Express, Electron

### インフラ、DB（得意な順）
Firebase, GCP（Cloud Run, Cloud Functions）, MongoDB
### その他
Node.js, Vite, Docker, nginx, Git, GitHub

## 言語
- 日本語：ネイティブ
- 英語：ビジネスレベル
  - TOEIC960点 
  - 英語で書かれたドキュメントを、日本語と遜色ない速度で読むことができる
  - 口頭、文章共に英語での議論や意見交換を行うことができる

## 職務経歴詳細

### 株式会社TERASS（2022/12～現在）

#### SUUMO, athomeなど複数の不動産ポータルサイトへの一括掲載を行う社内システムの新規開発
- チーム規模: 5人（PdM1 + エンジニア4）
- **役割**
  - コーディング、コードレビュー
  - 一部機能の設計
- **業務内容**
  - TypeScript, React(+Recoil, react-hook-form), Chakra UIを使ったフロントエンド開発
  - Firebase(Firestore + Cloud Functions for Firestore)を使ったバックエンド開発
  - Firebase Emulatorを使ったローカル開発環境の構築, DXの改善
  - Firebase Emulatorを使った自動テスト基盤の構築
  - GitHub Actions, Turborepoを用いたCI/CDの構築

物件情報をフォームに入力すると、同じ情報でSUUMO, athomeなど複数の不動産ポータルサイトへの出稿を行える社内システムの新規開発を行いました。

フロントエンド開発においては、フォームには200を超える入力項目があったため、パフォーマンスの最適化や途中保存機能、フォーム内のナビゲーションといったユーザー体験の向上が大きな課題となりました。

バックエンドにはFirebaseを利用しており、Firebase Emulatorを用いたローカル開発環境、自動テスト、CI/CDの構築など、DevOps的な作業も積極的に行いました。用意した環境とツールセットはチームメンバーによく受け入れられ、開発が快適になったと感謝の声を貰いました。テストについては初めは全く用意されていない状態でしたが、自らテスト基盤の用意を進め、最終的にはカバレッジ80%以上を達成しました。この取り組みと成果はのちに社内で発表を行い、社内のテスト文化普及に貢献しました。

#### 不動産エージェントと不動産売買をしたいカスタマーをマッチングするサービス[TERASS Offer](https://offer.terass.com/)の保守・新機能開発
- チーム規模: 4人（PdM1 + エンジニア3）
- **役割**
  - コーディング、コードレビュー
  - 新機能の仕様策定、設計
- **業務内容**
  - TypeScript, React(+Redux), styled-component, Storybookを使ったフロントエンド開発
  - Firebase(Firestore + Cloud Functions for Firestore)を使ったバックエンド開発

入社した段階ですでに運用されていたプロダクトの保守、新機能開発を行いました。
React, Firebaseのキャッチアップを素早く行い、入社2日目からバグ修正の対応を行いました。

### ネットコムBB株式会社（2021/04〜2022/09）

#### 社員の所在管理サービス ZAiSEKI の開発・運用 
- チーム規模: 5人
- **役割**：
  - コーディング、コードレビュー
  - API設計
  - インフラ・開発環境整備
- **業務内容**
  - Node.js + Express + MongoDB(Mongoose)でのバックエンドAPI開発
  - Node.jsを使ったWebSocketサーバー開発（チャット機能）
  - APIサーバー・WebSocketサーバーのパフォーマンステストとチューニング
  - Swift, Kotlinでのモバイルアプリ保守・テスト自動化
  - React + TypeScriptでの新サービスプロトタイプ開発
  - Electronを利用した社内ツール開発
  - 開発・本番環境へのDocker導入、インフラ整備
  - 社内勉強会の企画、発表

Web開発については初心者の状態で入社しましたが、学生時代に培ったコンピューターサイエンスの基礎知識と学習能力を活かして素早くキャッチアップできました。
基本的に人が足りていなかったため、チーム内でバックエンドやモバイルなどで明確に役割を区切るのではなく、適宜必要な知識を勉強して作業を進めていく形でした。

途中、アプリケーションの仕様変更で本番環境へのDocker導入が必要となりましたが、当時チームにDockerの本番環境での運用経験のあるメンバーがいなかったため、私が手をあげて一人で導入を行いました。
導入後、Docker基礎知識や導入時の技術的課題の解決などをテーマとした勉強会の企画・発表を行い、社内の技術スタックアップデートへの貢献を行いました。

## 業務外活動

### 技術記事投稿

- **Zenn**
  - 2022/03 より投稿開始。
  - https://zenn.dev/cizneeh

### 個人開発
- [個人ブログ](https://cizneeh.me/)
