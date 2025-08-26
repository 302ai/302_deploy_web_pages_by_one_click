# <p align="center"> 🌐 Webページのワンクリック展開 🚀✨</p>

<p align="center">Webページのワンクリック展開は、ワンクリックデプロイ機能によってプラットフォーム上で静的Webページをホスティングし、単一のHTMLファイルとZIPパッケージのデプロイをサポートします。</p>

<p align="center"><a href="https://302.ai/product/detail/65" target="blank"><img src="https://file.302.ai/gpt/imgs/github/20250102/72a57c4263944b73bf521830878ae39a.png" /></a></p >

<p align="center"><a href="README_zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>

![](docs/302_webserve_jp.png)

[302.AI](https://302.ai/ja/)の[Webページのワンクリック展開](https://302.ai/product/detail/65)のオープンソース版です。
302.AIに直接ログインすることで、コード不要、設定不要のオンライン体験が可能です。
あるいは、このプロジェクトをニーズに合わせてカスタマイズし、302.AIのAPI KEYを統合して、自身でデプロイすることもできます。

## インターフェースプレビュー
ファイルアップロード機能では、HTMLファイルまたはZIPパッケージをアップロードすることで、ワンクリックで静的Webページをデプロイできます。Webページの有効期限を設定でき、期限切れ後は自動的にオフラインになります。
![](docs/302_Deploy_web_pages_by_one-click_screenshot_01.png)

コード貼り付け機能では、コードをここに貼り付けるか、AIを使用してコードを生成することができ、編集とリアルタイムプレビューをサポートしています。
![](docs/302_Deploy_web_pages_by_one-click_screenshot_02.png)           

これがリアルタイムプレビューの効果です。
![](docs/302_Deploy_web_pages_by_one-click_screenshot_03.png)        

これがWebページの正常なデプロイ結果です。
![](docs/302_Deploy_web_pages_by_one-click_screenshot_04.png)     

## プロジェクトの特徴
### 📤 ワンクリックデプロイ
HTMLファイルとZIPパッケージの迅速なデプロイをサポート。
### ⏱️ 有効期限設定
Webページのオンライン期間を柔軟に設定でき、期限切れ後は自動的にオフライン。
### 🔄 リアルタイムプレビュー
コード編集時のリアルタイムプレビュー機能をサポート。
### 📝 AIコード生成
AIによるHTMLコード生成機能を内蔵。
### 🌍 多言語サポート
- 中国語インターフェース
- 英語インターフェース
- 日本語インターフェース

## 🚩 将来のアップデート計画
- [ ] Webページテンプレートの追加

## 🛠️ 技術スタック

- **フレームワーク**: Next.js 14
- **言語**: TypeScript
- **スタイリング**: TailwindCSS
- **UIコンポーネント**: Radix UI
- **状態管理**: Jotai
- **フォーム処理**: React Hook Form
- **HTTPクライアント**: ky
- **国際化**: next-intl
- **テーマ**: next-themes
- **コード規約**: ESLint, Prettier
- **コミット規約**: Husky, Commitlint

## 開発&デプロイ
1. プロジェクトのクローン
```bash
git clone https://github.com/302ai/302_deploy_web_pages_by_one_click
cd 302_deploy_web_pages_by_one_click
```

2. 依存関係のインストール
```bash
pnpm install
```

3. 環境設定
```bash
cp .env.example .env.local
```
必要に応じて`.env.local`の環境変数を修正してください。

4. 開発サーバーの起動
```bash
pnpm dev
```

5. プロダクションビルド
```bash
pnpm build
pnpm start
```

## ✨ 302.AIについて ✨
[302.AI](https://302.ai/ja/)は企業向けのAIアプリケーションプラットフォームであり、必要に応じて支払い、すぐに使用できるオープンソースのエコシステムです。✨
1. 🧠 包括的なAI機能：主要AIブランドの最新の言語、画像、音声、ビデオモデルを統合。
2. 🚀 高度なアプリケーション開発：単なるシンプルなチャットボットではなく、本格的なAI製品を構築。
3. 💰 月額料金なし：すべての機能が従量制で、完全にアクセス可能。低い参入障壁と高い可能性を確保。
4. 🛠 強力な管理ダッシュボード：チームやSME向けに設計 - 一人で管理し、多くの人が使用可能。
5. 🔗 すべてのAI機能へのAPIアクセス：すべてのツールはオープンソースでカスタマイズ可能（進行中）。
6. 💪 強力な開発チーム：大規模で高度なスキルを持つ開発者集団。毎週2-3の新しいアプリケーションをリリースし、毎日製品更新を行っています。才能ある開発者の参加を歓迎します。
