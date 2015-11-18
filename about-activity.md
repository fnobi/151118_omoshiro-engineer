# 「Activity」とはなんぞや

- Activity ≒ 画面
- ある画面でどういう処理が行われるかは、Activityのファイルに書く
- 基本的に、画面を増やしたいときはActivityを追加と思っておけばよい

## Activityの追加
- 「XXXXXActivity」というようなクラスを追加
- AndroidManifestに追記
- そのあたらしいActivityを呼び出す処理を追加する（このあたりは追々）
  - AndroidManifestで ```<action android:name="android.intent.action.MAIN" />``` という記述を追加すると、デフォルトで開くActivityになります
