# command

1. dockerimageのビルド
```sh
docker-compose build
```

2. Reactのプロジェクト作成
```sh
docker-compose run --rm front sh -c "npx create-react-app . --template typescript"
```

3. コンテナの起動
```sh
docker-compose up -d
```

4. Reactにアクセス
```sh
http://localhost:3000
```