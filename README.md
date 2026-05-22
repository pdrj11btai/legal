# pdrj11btai / legal

iOS 個人開発アプリの規約・プライバシーポリシー公開リポジトリ。
GitHub Pages で配信され、各アプリの「設定 → プライバシーポリシー / 利用規約」リンクから参照される。

## 公開先

- ルート: <https://pdrj11btai.github.io/legal/>
- ジカウンター: <https://pdrj11btai.github.io/legal/ji-counter/>

## 構成

```
legal/
├── _config.yml      Jekyll 設定（GitHub Pages 用）
├── index.md         ルートランディング（アプリ一覧）
└── ji-counter/      ジカウンター（パチスロ小役カウンター）
    ├── index.md
    ├── privacy.md   プライバシーポリシー
    └── terms.md     利用規約
```

将来別アプリを公開する場合は、`<app-slug>/` ディレクトリを追加して同じ構造で配置。

## 更新方法

各アプリのリポジトリ側で文書を編集している場合は、本リポにコピーして同期。
誤り・古い記述があれば該当 `.md` を直接編集→ commit → push。GitHub Pages が自動ビルド。

## ライセンス

各文書は対象アプリの作者 (Kai / pdrj11btai) が著作権を保持。
