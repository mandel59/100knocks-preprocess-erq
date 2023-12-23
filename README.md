# データサイエンス100本ノック（構造化データ加工編） Erqでの解答例

このリポジトリのコードは[データサイエンス100本ノック（構造化データ加工編）](https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess)の解答例です。

各問題はErq用に改変しています。

- [データサイエンス100本ノック（構造化データ加工編） Erqでの解答例](erq/100knocks-preprocess.erq)
- [Erq - Easy Relational Query Language](https://github.com/mandel59/erq)

## 使い方

Node.js v20.10.0 で動作を確認しています。

Node.jsがインストールされている環境で、このリポジトリをクローンした後、次のコマンドでSQLiteデータベースを初期化してください。

```shell
npm install
npx erq dsdojo.db <erq/init.erq
```

初期化すると、`dsdojo.db`というSQLiteデータベースが作成されます。

初期化後は、次のコマンドでErq CLIを起動できます。

```shell
npx erq dsdojo.db
```

解答例は、次のようにして全体を実行することが可能です。

```shell
npx erq dsdojo.db <erq/100knocks-preprocess.erq
```

## LICENSE

次のデータは[データサイエンス100本ノック（構造化データ加工編）](https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess)に記載のライセンス（MITライセンス）のもと、改変した上で再配布しています。ライセンス本文は[`LICENSE`](./LICENSE)を参照してください。

- `data/`ディレクトリ配下のデータ
- `erq/100knocks-preprocess.erq`中の問題文（一部を改題しています。）
- `erq/100knocks-preprocess.erq`中の解答例の一部を、元のSQLの解答例を参考に作成しています。

その他のデータ（`erq/100knocks-preprocess.erq`の新規作成部分を含む）は、MIT-0ライセンスのもとで利用可能です。ライセンス本文は[`MIT-0`](./MIT-0)を参照してください。
