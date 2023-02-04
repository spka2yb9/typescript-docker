# セットアップ

## コンテナ起動
```
docker-compose up -d --build
```
## コンテナ内に入る
```
docker-compose exec app sh
```

## コンテナ内で必要パッケージを追加
```
npm init -y
npm install typescript ts-node ts-node-dev
```

## tsconfig.jsonファイルを作成
```
npx tsc --init
```
