# smaregi-app-env

* import スマレジーサンプルーアプリ.postman_collection.json & スマレジーサンプルーアプリ-env.postman_environment.json to POSTMAN
* change `contract_id` `client_id` `client_secret` to respective values obtained from samregi. 
* send `POST` request  from アクセストークン collection to get `access_token`.
* send `GET` request from 店舗一覧取得 collection to get store list for provided `contract_id`. 
