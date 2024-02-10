# インストール

## pgAdmin 4
https://www.pgadmin.org/download/
## Postman
https://www.postman.com/downloads/
## Node.js (LTS 推奨版)
https://nodejs.org/ja

# GitHub　repo
https://github.com/GomaGoma676/echo-rest-api

# Goアプリケーション作成
go mod init go-webapp

# Docker立ち上げ
docker compose up -d

# 外部パッケージダウンロード
go mod tidy

# マイグレーション
go run ファイル名

# 起動
GO_ENV=dev go run main.go
