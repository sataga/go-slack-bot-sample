# go-slack-bot-sample

## 動くまでのざっくり流れ
- slackにApp追加
    - tokenの発行(Signing Secret, OAuth Tokens)
    - OAuth & Permissionsの設定(Scopeの設定)
- ngrokでローカルPCをproxyさせる形で動作確認
    - Event Subscriptionsの設定(ngrokが発行したURLを指定)
- slack上でbotを呼び出したら動作する

## 動作確認ログ
- https://github.com/sataga/go-slack-bot-sample/issues/1

## memo
- 実務で使うにはproxyサーバが必要

## 参考資料
- [Go で Slack Bot を作る (2020年3月版) - Qiita](https://qiita.com/frozenbonito/items/cf75dadce12ef9a048e9#%E7%B5%82%E3%82%8F%E3%82%8A%E3%81%AB)
