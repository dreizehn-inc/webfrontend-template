# typescript 環境について

- turbo と yarn の workspace で各 pakcage を管理します。

## 初期化

```bash
# dotenvのコピー
> cp packages/web/.env.tmpl packages/web/.env

> yarn

> yarn build
```

## サーバースタート

```bash
# nextjs web動
> yarn workspace @typescript-plane-boilerplate/web start:dev
```
