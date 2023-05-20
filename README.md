# githubactions_sample
Github Actions Workflow Sample

## 使い方
B系は基本的にシンプルな物でforkしたらすぐ使えるようにしています。
Begginer向けに考えたworkflowです。
`workflow_dispatch`で用意しているので`Actions`画面で実行してください

## 参考ページ
- [公式ドキュメント](https://docs.github.com/ja/actions)
  - [if文](https://docs.github.com/ja/actions/learn-github-actions/expressions#status-check-functions)

## Begginer向けWorkFlow
| WorkFlowID    | Description | Type | Memo |
| ------------- | -------------------------------------  |-------------|-------------|
| B0001         | 公式ドキュメントのHello World          | -            | -            |
| B0002         | 公式ドキュメントのworkflow_dispatch     | WFTrigger    | -            |
| B0003         | ENVの定義方法,箇所とoverwriteの関係について  | Variables   | -            |
| B0004         | Job間の並列実行,依存関係について | Jobs        | -            |
| B0005         | Jobのif文を用いた実行制御について | Jobs        | -            |
| B0006         | Jobのif文を用いた実行制御について | Jobs        | -            |


##### 今後の予定
- default.run
- concurrency
- [secret mask](https://docs.github.com/ja/actions/using-workflows/workflow-commands-for-github-actions)
- [複数行GITHUB_OUTPUT](https://gotohayato.com/content/558/)