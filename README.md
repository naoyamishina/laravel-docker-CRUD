## 環境構築方法
- このリポジトリをローカルにクローン
```
git clone
```

- 環境変数をコピー（練習アプリ以外は各自変更すること）
```
cp src/.env.example src/.env
```

- laravelプロジェクト作成

クローンしたsrcディレクトリを削除後、プロジェクト作成
```
docker compose exec app bash
```
```
composer create-project --prefer-dist "laravel/laravel=8.*" .
# 8系の場合
```

- コンテナを起動する
```
docker-compose up -d --build
```

- 確認
```
docker-compose ps
```
- 削除
```
docker-compose down
```
