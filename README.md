# univ_debut_fe_after
React移行、swaでデプロイ。
## リポジトリをクローン
```
git clone https://github.com/smaru1111/univ_debut_fe_after
```

## ローカルの起動
Nodo.jsをインストールしてください。
https://nodejs.org/ja

### npm start
```
cd after-pomodoro
npm i
npm start
```

### Azure Static Web Apps CLIをインストール

```
npm install -g @azure/static-web-apps-cli

# swaとして起動(パスの位置：univ_debut_fe_after/after-pomodoro>)
swa start --api-location ./api
```



[参照元：AADojo](https://aadojo.alterbooth.com/entry/2022/09/09/170000)
