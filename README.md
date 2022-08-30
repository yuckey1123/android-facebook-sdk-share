# facebook_sdk_share

Facebook SDK を使用したシェア機能実装サンプル

# 使用している SDK

Facebook Sharing SDK：https://developers.facebook.com/docs/sharing/android

# Facebook シェア機能を使うには以下の操作が必要

## Facebook ダッシュボードよりアプリ ID とクライアントトークンを取得してください

詳しい手順はこちら：https://developers.facebook.com/docs/android/getting-started#quick-start

※Facebook の開発者用アカウントが必要

## 取得したアプリ ID とクライアントトークンをリソースファイルと AndroidManifest に記載すること

strings.xml

- @string/facebook_app_id

- @string/facebook_client_token

AndroidManifest.xml

- "com.facebook.app.FacebookContentProvider{APP_ID}"
