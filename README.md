# laravel10_api_template

## Description
ハッカソンなど

## Features

- Github Actions
  - labeler
    - 自動でラベルを付与する
  - assign-author
    - 自動でPR作成者をassignする
  - openai-pr-reviewer
    - PRをopenaiにレビュー依頼する
  - setup-tbls
    - DBのテーブル定義書を自動生成する
  - deploy-to-github-pages.yml
    - swaggerをgithub pagesにデプロイする
    - swaggerはL5-Swaggerで自動生成する
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
  - コンテナ関連
  - テスト関連
  - データベース関連
  - 依存関係
- pre-commit
  - credential関連
- EditorConfig
- .tool-versions
  - pre-commit

