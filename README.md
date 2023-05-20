# githubactions_sample
Github Actions Workflow Sample

## 使い方
B系は基本的にシンプルな物でforkしたらすぐ使えるようにしています。
Begginer向けに考えたworkflowです。
`workflow_dispatch`で用意しているので`Actions`画面で実行してください

## 参考ページ
- [公式ドキュメント](https://docs.github.com/ja/actions)
  - aaa

## Begginer向けWorkFlow
| WorkFlowID    | Description | Type |
| ------------- | -------------------------------------  |-------------|
| B0001         | 公式ドキュメントのHello World          | -            |
| B0002         | 公式ドキュメントのworkflow_dispatch     | WFTrigger    |
| B0003         | ENVの定義方法,箇所とoverwriteの関係について  | Variables   |
| B0004         | Job間の並列実行,依存関係について                            | Jobs        |


##### 今後の予定
- default.run
- concurrency