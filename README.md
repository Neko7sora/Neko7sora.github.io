# Neko7sora.github.io v2 picocss
GitHub Pagesサイトは現在developブランチのdocsフォルダから構築されています。

注意事項 Sassはコンパイルしてパブリッシュしてください。jekyllコンパイルだとエラーが発生します。

https://sass-lang.com/install

## ファイル構造

```sh
.
├── _config.yml #コンフィグ
├── _data #データ
|   ├── **.yml
|   └── **.yml
├── _drafts #下書き
|   ├── **.md
|   └── **.html
├── _favicon #favicon
|   ├── favicon.ico
|   └── (etc...)
├── _includes #テンプレート
|   ├── footer.html #フッター
|   └── (etc...)
├── _layouts #レイアウトテンプレート
|   ├── default.html
|   ├── post.html
|   └── (etc..)
├── _pages #ページ
|   ├── **
|   └── (etc..)
├── _posts #記事
|   ├── **
|   └── (etc..)
├── _sass
|   ├── **.sccs #sccs
|   └── (etc..)
├── assets
|   ├── css
|   |    ├── **.css
|   |    └── (etc..)
|   ├── js
|   |    ├── **.js
|   |    └── (etc..)
|   ├── img
|   |   └── (画像)
|   ├── mp
|   |   └── (動画)
|   └── sys
|       └── (ファイル配布など)
├── Gemfile #プラグイン
└── README.md
```
