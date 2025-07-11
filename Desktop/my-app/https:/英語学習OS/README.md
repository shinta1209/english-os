# 英語学習OS (English Learning OS)

包括的な英語学習プラットフォーム - Webアプリケーション

## 🎯 プロジェクト概要

英語学習OSは、効率的で楽しい英語学習体験を提供するWebアプリケーションです。将来的にはApple Storeでの配布も予定しています。

## 🚀 技術スタック

### フロントエンド
- **React 18** - UIライブラリ
- **TypeScript** - 型安全性
- **Vite** - ビルドツール
- **Tailwind CSS** - スタイリング
- **React Router** - ルーティング

### バックエンド
- **Node.js** - ランタイム
- **Express.js** - Webフレームワーク
- **TypeScript** - 型安全性
- **SQLite** - データベース（開発）
- **JWT** - 認証

### その他
- **PWA** - オフライン対応
- **ESLint** - コード品質
- **Prettier** - コードフォーマット

## 📁 プロジェクト構造

```
english-learning-os/
├── frontend/                 # Reactフロントエンド
│   ├── src/
│   │   ├── components/      # 再利用可能なコンポーネント
│   │   ├── pages/          # ページコンポーネント
│   │   ├── hooks/          # カスタムフック
│   │   ├── utils/          # ユーティリティ関数
│   │   ├── types/          # TypeScript型定義
│   │   ├── assets/         # 静的ファイル
│   │   └── styles/         # スタイルファイル
│   └── public/             # 公開ファイル
├── backend/                 # Node.jsバックエンド
│   ├── src/
│   │   ├── controllers/    # コントローラー
│   │   ├── models/         # データモデル
│   │   ├── routes/         # APIルート
│   │   ├── middleware/     # ミドルウェア
│   │   ├── utils/          # ユーティリティ関数
│   │   └── config/         # 設定ファイル
│   └── database/           # データベース関連
├── docs/                   # ドキュメント
└── scripts/                # スクリプトファイル
```

## 🛠️ セットアップ

### 前提条件
- Node.js 18以上
- npm または yarn

### インストール

1. リポジトリをクローン
```bash
git clone https://github.com/shinta1209/english-os.git
cd english-os
```

2. 依存関係をインストール
```bash
npm install
```

3. 環境変数を設定
```bash
cp .env.example .env
# .envファイルを編集して必要な値を設定
```

4. 開発サーバーを起動
```bash
npm run dev
```

## 📝 開発コマンド

```bash
# 開発サーバー起動（フロントエンド + バックエンド）
npm run dev

# フロントエンドのみ
npm run dev:frontend

# バックエンドのみ
npm run dev:backend

# ビルド
npm run build

# テスト実行
npm run test

# リント実行
npm run lint
```

## 🌟 主要機能（予定）

- [ ] ユーザー認証・登録
- [ ] 単語学習システム
- [ ] 文法練習
- [ ] リスニング練習
- [ ] スピーキング練習
- [ ] 進捗管理
- [ ] 学習統計
- [ ] オフライン対応
- [ ] モバイル対応

## 🤝 コントリビューション

1. このリポジトリをフォーク
2. 機能ブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add some amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

## 👨‍💻 作者

shinta1209

---

**英語学習OS** - 楽しく効率的な英語学習をサポートします！ 