# Copy Book

"Copy book" はWeb上でよく使われるテキスト集です。  
[本家](https://copybook.me/)を参考に日本語へ訳したものを中心に掲載しています。

## 開発環境

[Hugo](https://gohugo.io/)を使用しています。  
[Homebrew](https://brew.sh/)が導入されている場合、以下でインストールすることができます:

```sh
brew install hugo
```

導入されていない場合は[Hugo installation page](https://gohugo.io/getting-started/installing/)からインストールできます。

その後、以下のコマンドでローカル環境を起動することができます。

```sh
git clone https://github.com/mu-rayama/copybook_jp.git
cd copybook
npm install
npm run dev
```

ブラウザで[`http://localhost:1313`](http://localhost:1313)にアクセスすると、"Copy book"が表示されます。

| スクリプト         | 説明                                     |
| --------------- | ----------------------------------------------- |
| `npm run dev`   | ローカルで Hugo server と Tailwind Watcherを起動します |
| `npm run build` | 本番環境用のリソースを作成します                 |

## License
[本家"Copy book"のライセンス](https://github.com/praveenjuge/copybook/blob/main/LICENSE)に基づいて作られています。
本リポジトリについては[ライセンス](https://github.com/mu-rayama/copybook_jp/blob/main/LICENSE)をご覧ください。
