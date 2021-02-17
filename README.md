# postgre_docker_sample
Postgreの動作検証用に作成。

## コンテナ立ち上げ

> docker-compose up -d

## PostgreSQLコンテナログイン

> docker-compose exec db /bin/sh

## PostgreSQLサーバログイン

> psql -h postgres -p 5432 -U postgres -d postgres
