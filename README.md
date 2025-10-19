# プライバシーポリシー

このリポジトリは、アプリケーションのプライバシーポリシーを公開するためのGitHub Pagesサイトです。

## 公開されているアプリ

- **Lifespan Timer** - 人生の残り時間を視覚化するアプリ
- **SimpleVocabularyBook** - シンプルな英単語学習アプリ

## GitHub Pagesの設定方法

このリポジトリをGitHub Pagesとして公開するには、以下の手順を実行してください：

### 1. GitHubリポジトリの設定

1. GitHubでこのリポジトリのページを開きます
2. **Settings**（設定）タブをクリックします
3. 左側のメニューから **Pages** を選択します

### 2. GitHub Pagesの有効化

1. **Source**（ソース）セクションで、以下を選択します：
   - Branch: `main` (またはデフォルトブランチ)
   - Folder: `/docs`
2. **Save**（保存）ボタンをクリックします

### 3. 公開の確認

数分後、GitHub Pagesの設定ページに、サイトのURLが表示されます：

```
https://[ユーザー名].github.io/[リポジトリ名]/
```

このURLにアクセスすると、プライバシーポリシーページが表示されます。

## ディレクトリ構成

```
privacy-policy/
├── docs/                               # GitHub Pagesのルートディレクトリ
│   ├── index.md                       # トップページ（マークダウン）
│   ├── lifespan-timer.md              # Lifespan Timerのプライバシーポリシー
│   ├── simple-vocabulary-book.md      # SimpleVocabularyBookのプライバシーポリシー
│   └── _config.yml                    # Jekyll設定ファイル
├── doc/                               # 元のマークダウンファイル
│   ├── Lifespan Timer プライバシーポリシー.md
│   └── SimpleVocabularyBook プライバシーポリシー.md
└── README.md                          # このファイル
```

## プライバシーポリシーの更新方法

プライバシーポリシーを更新する場合：

1. `docs/`ディレクトリ内の対応するマークダウンファイル（`.md`）を編集します
2. 変更をコミットしてGitHubにプッシュします
3. GitHub PagesがJekyllを使用して自動的にHTMLに変換し、サイトが更新されます（通常数分以内）

### マークダウンファイルの編集ポイント

- **Front Matter**: 各ファイルの先頭にある`---`で囲まれた部分はJekyll用のメタデータです
- **見出し**: `#`, `##`, `###`を使用して階層構造を表現できます
- **リスト**: `-`を使用して箇条書きを作成できます
- **リンク**: `[テキスト](URL)`の形式でリンクを作成できます

## 技術スタック

- **GitHub Pages**: 静的サイトホスティング
- **Jekyll**: マークダウンファイルを自動的にHTMLに変換
- **Markdown**: コンテンツの記述形式

## お問い合わせ

プライバシーポリシーに関するご質問は、以下のページからお問い合わせください：

https://code-rebuild.com/page-731/

## ライセンス

このプライバシーポリシーの内容は、各アプリケーション固有のものです。
