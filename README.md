# prittier-test
## prittierをインストールする
```
npm i -D prittier
```
## package.jsonのscriptsにフォーマットを追加する
```
"format": "prettier --write '*.js'"
```
## phpstormでprittierをexternal toolとして設定する
https://prettier.io/docs/en/webstorm.html#using-prettier-as-external-tool
## 整形する
### コマンドから実行する場合
```
npm run format
```
### エディタから実行する場合
command + shift + A から、Action に Prittier を入力して実行する
