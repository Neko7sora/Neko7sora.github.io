# Neko7sora.github.io
GitHub Pagesサイトは現在gh-pagesブランチの/docsフォルダから構築されています。

## ファイル構造

```sh
.
├── _config.yml #コンフィグ
├── _data #データ
|   ├── **.yml #**のデータ
|   └── **.yml #**のデータ
├── _drafts 
|   ├── **.md #下書き
|   └── **.html #下書き
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
├── _pages 
|   ├── ** #ページ
|   └── **
├── _posts 
|   ├── ** #記事
|   └── ** #記事
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