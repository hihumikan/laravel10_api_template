# laravel10_api_template

## Description


## Features

- Github Actions
  - labeler
    - 自動でラベルを付与する
  - assign-author
    - 自動でPR作成者をassignする
  - openai-pr-reviewer
    - PRをopenaiにレビュー依頼する
  - code-check
    - reviewdog
      - コードをチェックしてコメントする
        - phpstan / Larastan
          - PHPの静的解析ツール
        - php-cs-fixer
          - PHPのコードフォーマッター
        - phpunit
          - PHPのテストツール
          - カバレッジレポート生成
        - phpinsights
          - PHPのコード品質をチェックするツール
- Docker Compose
  - dev
    - PHP
    - Nginx
    - Database
      - MySQL
      - Redis
  - prd
    - codebuild
      - PHP
      - Nginx
      - Database
        - MySQL
        - Redis
- .vscode
  - PHP Debug
- Taskfile
- .tool-versions
  - pre-commit
