## プロジェクトアプリケーションサーバー
### Description
ローカル PC でも動作する、ドキュメントデータ登録用の json ファイルを生成する Web アプリケーション
### Composition
- enviroment
  - Windows/Node.js
  - OSX/Node.js
- language
  - Javascript
- modules
  - npm:js-yaml
  - npm:json5
### Functions
#### 無名関数
本プロジェクトのディレクトリ内において node . で起動するファイルで呼び出される無名関数。指定ポートでサーバーを起動する

args:
| name | description | type |
| ---- | ---- | ---- |
| port = 8080 | 指定ポート番号 | Integer |

return:
|  | name | description |
| ---- | ---- | ---- |
| / | abc | nanika |

#### rootListener
index.html, index.css, index.js を配信する関数。呼び出しアドレスはデフォルトポートにおいて http://localhost:8080 とする
