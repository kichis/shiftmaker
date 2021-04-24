# shiftmaker
2020.04 シフト決めの自動化アプリ



## to achive
- vuex
- Vue x TS
- Vue x PHP(連携・デプロイ)

## 事前調査
- UIライブラリのVue3への対応状況  
Vuetify:未  
Element:済  
- シフト作成に役立ちそうなライブラリ  
なし 
- PHPのバージョン
7.4 / 8.0  
-> 7.4で作成(理由：今回はプロトタイプ、かつ、Vue.jsとの連携に不透明性がある -> より安定性があり情報が多そうバージョンで)

## 学んだこと

vuexとは
- Vue.jsのための状態管理パターン + ライブラリ
- 全てのコンポーネントからアクセスできるデータストア
- 意図しないデータの変更も防ぐ
- [参照](https://blog.codecamp.jp/vuejp-vuex-commentary)
