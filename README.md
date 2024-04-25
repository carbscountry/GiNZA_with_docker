# GiNZA_with_docker

## 実行
```
# コンテナの作成
docker-compose up -d app
# コンテナにアクセス
docker-compose exec app /bin/bash
```
Jupterlabを起動
```
jupyter lab --allow-root --no-browser --NotebookApp.token='' --port 8888 --ip=0.0.0.0
```
http://localhost:8888/
