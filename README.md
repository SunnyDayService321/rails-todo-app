# Rails Todo App

Ruby on Rails で構築したシンプルなTodoアプリです。

## 🛠 技術スタック

- **言語**: Ruby 2.7.1
- **フレームワーク**: Ruby on Rails 7.0.3
- **データベース**: SQLite3
- **Webサーバー**: Puma
- **フロントエンド**: Hotwire（Turbo + Stimulus）、SCSS、importmap
- **認証**: bcrypt
- **テスト**: Capybara、Selenium WebDriver

## 📁 ディレクトリ構成

\```
rails-todo-app/
├── app/         # モデル・ビュー・コントローラー
├── bin/         # 実行スクリプト
├── config/      # ルーティング・設定ファイル
├── db/          # マイグレーション・スキーマ
├── lib/         # カスタムライブラリ
├── public/      # 静的ファイル
├── test/        # テストコード
├── Gemfile      # 依存Gem定義
└── README.md
\```

## 🚀 セットアップ手順

### 1. リポジトリをクローン

\```bash
git clone https://github.com/SunnyDayService321/rails-todo-app.git
cd rails-todo-app
\```

### 2. Gemをインストール

\```bash
bundle install
\```

### 3. データベースを作成・マイグレーション

\```bash
rails db:create
rails db:migrate
\```

### 4. 開発サーバーを起動

\```bash
rails server
\```

ブラウザで http://localhost:3000 にアクセスしてください。

## 🧪 テストの実行

\```bash
rails test
\```

## 📋 主な機能

- Todoの一覧表示
- Todoの追加
- Todoの編集
- Todoの削除
