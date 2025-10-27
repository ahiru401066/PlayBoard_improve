## フォルダ構成

<pre>
app/
├ cmd/
├ internal/
│   ├ handler/
│   ├ service/
│   └ repository/
├ configs/
├ migrations/
├ docker/
├ go.mod
└ README.md
</pre>

## 各ディレクトリの説明

- cmd/: アプリ本体
- internal/handler: HTTPルーティング
- internal/service: ビジネスロジック
- internal/repository: DBアクセス
- configs/: 設定ファイル
- migrations/: DBマイグレーション
- docker/: Dockerfile, docker-compose.yml
