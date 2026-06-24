# Royle — Developer Page

サーバーサイドエンジニア Royle の開発者ページ（GitHub Pages 用静的サイト）。

## 構成

```
.
├── index.html                       # トップ：プロフィール + 開発アプリ一覧
├── assets/style.css                 # トップページのスタイル
└── apps/
    └── specimen-box/
        ├── index.html               # 化石箱 LP（アプリのデザインに沿った本ページ）
        ├── assets/                   # アプリアイコン・スクリーンショット・LP用CSS
        └── support/                  # 化石箱サポートサイト
            ├── index.html            #   サポート / FAQ（App Store サポートURL）
            ├── privacy.html          #   プライバシーポリシー
            ├── tokushoho.html        #   特定商取引法に基づく表記
            └── style.css
```

`apps/specimen-box/support/` は `~/develop/specimen-box-support` で作成したサポートサイトを取り込んだもの。

## 公開（GitHub Pages）

1. このディレクトリを `<ユーザー名>.github.io` という名前の GitHub リポジトリとして push する。
2. リポジトリの **Settings → Pages** で Branch: `main` / root を選択。
3. `https://<ユーザー名>.github.io/` で公開される。

`.nojekyll` を置いてあるため Jekyll 処理はスキップされ、HTML がそのまま配信される。

## 各 URL（公開後）

- 開発者トップ … `/`
- 化石箱 LP … `/apps/specimen-box/`
- 化石箱サポート（App Store サポートURL）… `/apps/specimen-box/support/`
- 化石箱プライバシーポリシー … `/apps/specimen-box/support/privacy.html`
