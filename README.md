# sample-github-actions-gae
GithubActionsでGAEにデプロイするサンプルです。

# 環境とデプロイ方法
| 環境 | デプロイ方法 |
| -- | -- |
| 本番環境 | タグを「v*」の形式でつけるとデプロイします（例:v1.0.0） |
| 開発環境 | mainブランチにマージすると開発環境へデプロイします |


# 環境変数の管理
Environmentを使っています。
本番環境：prod
開発環境：dev

| 環境変数名 | Value |
| -- | -- |
| GCLOUD_PROJECT_ID | GAEのプロジェクトIDを登録してください |
| GCLOUD_SERVICE_KEY | サービスアカウントを作成し、json形式で作成した鍵の値を登録してください |