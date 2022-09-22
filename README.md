# facebook_sdk_share

Facebook SDK を使用したFacebookシェア機能の実装サンプル

## Facebook SDK

Facebook Sharing SDK：https://developers.facebook.com/docs/sharing/android

## 操作

### FacebookダッシュボードよりアプリIDとクライアントトークンを取得

取得方法はこちら：https://developers.facebook.com/docs/android/getting-started#quick-start

※Facebookの開発者用アカウントが必要

### 取得したアプリIDとクライアントトークンをstrings.xmlとAndroidManifest.xmlに記載

#### strings.xml

- @string/facebook_app_id

- @string/facebook_client_token

#### AndroidManifest.xml

- "com.facebook.app.FacebookContentProvider{APP_ID}"
