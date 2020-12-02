# スマレジAPI_Postmanテンプレート
* `スマレジーサンプルーアプリ.postman_collection.json` と `スマレジーサンプルーアプリ-env.postman_environment.json` をPostmanにインポートします
* スマレジーサンプルーアプリ-envの`contract_id` `client_id` `client_secret` にスマレジから取得した値を入れます
* アクセストークンを取得するため、アクセストークンコレクションから`POST`リクエストを送信します
* `contract_id`に紐付く店舗一覧を取得するために、店舗一覧取得コレクションから`GET`リクエストを送信します
