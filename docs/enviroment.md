## 環境構築の流れ

### 初期
一時的にコンテナを立ててそこで初期設定を行う（go.mod, go.sum）
```zsh
docker run -it --rm \
  -v ../:/app \
  -w /app \
  golang:1.25-alpine sh
```