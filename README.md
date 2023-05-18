## 環境構築方法
- このリポジトリをローカルにプル
```
git pull
```

- コンテナを起動する
```
docker-compose up -d --build
```
確認
```
docker-compose ps
```
削除
```
docker-compose down
```

- 環境変数をコピー（練習アプリ以外は各自変更すること）
```
cp src/.env.example src/.env
```
