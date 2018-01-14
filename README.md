# markdown-doc

Markdownで簡単なドキュメントを書く際のリポジトリです。

## 使い方

1. git からクローンする
2. docフォルダ内でmarkdownを作成
3. `npm run convert`でHTMLに一発変換

### git からクローンする

```bash
git clone https://github.com/namityo/markdown-doc.git sample
cd sample
rm -rf .git
npm install
```

### docフォルダ内でmarkdownを作成

docフォルダ内にサンプルの`.md`ファイルがあります。
同じようにdocフォルダ内でドキュメントを作成してください。

### `npm run convert`でHTMLに一発変換

次のコマンドでMarkdownファイルをHTMLにまとめて変換します。

```
npm run convert
```

### User Style

スタイルシートはcssフォルダ内の`user.css`を編集してください。

### サンプル

サンプルは[ここ](doc/sample.md)です
