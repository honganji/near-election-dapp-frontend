## 🗃 **Near Election Dapp**

## Web サイト

作成済みのアプリを見たい方は[こちら](https://tonny-near-election-dapp.netlify.app/)からご覧ください。

## **Quick Start**

始める前に、[こちら](https://github.com/honganji/near-election-dapp-contract)のコードを clone して、手順に沿ってコントラクトを自分の wallet に deploy していることを確認してください。

---

1. 下のコードをターミナルで走らせてでライブラリをインストールしてください

```
    yarn install
```

2. `src/config.js`にある`CONTRACT_NAME`という定数をあなたが deploy した ID に変更してください。

   （例えば YOUR_CONTRACT_ID には dev_account.testnet などが入ることになります）

```
    const CONTRACT_NAME = YOUR_CONTRACT_ID
```

3. 下のコードをターミナルで走らせてローカルサーバーを起動してください.
   これで Election Dapp が起動します！

```
    yarn dev
```
