## COVID-19 世界現況板作り

## javascript -> typescript

0. JSDoc でタイプシステムを適用してみる

1. typescript 基本環境構築

  - [x] NPM 初期化
    - `$ npm init `
  - [x] install typescript library
    - `$ npm i typescript `
  - [x] tsconfig.json を生成し、基本設定追加
  - [x] _.js -> _.ts
  - [x] `tsc` command でコンパイルする

2. 一旦、全部 `any` にする。
  - `tsconfig.json`ファイルに`noImplicitAny = true`を追加する。
  - なるべく具体的なタイプにする。

3. 開発環境設定
  - babel, eslint, prettier 設定

4. 外部ライブラリモジュール化
## 参考資料

- [ジョーンズ·ホプキンス·コロナの現況](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
- [Postman API](https://documenter.getpostman.com/view/10808728/SzS8rjbc?version=latest#27454960-ea1c-4b91-a0b6-0468bb4e6712)
- [Type Vue without Typescript](https://blog.usejournal.com/type-vue-without-typescript-b2b49210f0b)
