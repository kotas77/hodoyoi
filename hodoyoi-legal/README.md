# ほど酔い 規約ページ

GitHub Pages で公開する、利用規約とプライバシーポリシーです。

## 構成

```
.
├── index.html            トップ（両ページへのリンク）
├── terms/
│   └── index.html        利用規約
├── privacy/
│   └── index.html        プライバシーポリシー
├── assets/
│   └── css/
│       └── style.css     共通スタイル（ダークモード対応）
├── .nojekyll             Jekyll の変換を止める
└── README.md
```

## 公開後の URL

リポジトリ名を `hodoyoi` にした場合:

- トップ: `https://<GitHubユーザー名>.github.io/hodoyoi/`
- 利用規約: `https://<GitHubユーザー名>.github.io/hodoyoi/terms/`
- プライバシーポリシー: `https://<GitHubユーザー名>.github.io/hodoyoi/privacy/`

App Store Connect の「プライバシーポリシー URL」と、アプリ内の規約リンクには上の URL を設定します。

## 公開手順

1. このフォルダの中身をリポジトリのルートに置いて push する
2. リポジトリの Settings > Pages で、Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にする
3. 数分後に上の URL で表示されることを確認する

## 公開前に置き換える箇所

- `support@example.com`（3ページ共通。`TODO` コメントの位置）
- 制定日（`2026年10月4日`）

## 改定するとき

- HealthKit 連携やサーバーを使う機能を追加したら、プライバシーポリシーの「1」「2」「4」を更新する
- 改定日は `<p class="meta">` に「最終改定日：」として追記する
