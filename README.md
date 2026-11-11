# api-setup-practice

## 概要
COACHTECH 教材 Tutorial 11-1「API開発環境の構築と疎通確認」で作成した成果物です。


## 使用技術
- PHP 8.x
- Laravel 10.x
- REST API（JSONレスポンス）
- Postman（動作確認）


## 学んだこと
- routes/api.phpに疎通確認用のAPIを作成する
- Postmanで動作確認する
- 

## 動作確認
Postmanをインストールして、PostmanでGETリクエストを送信。 ステータスコード200 OKが返ってきて、{"message": "Hello, API!"}というJSONが返ってくる。

## 手詰まりになったこと
始めにブラウザでPostmanを開いてやっていたが、なかなか反映されずコーチにアドバイスをもらいアプリで開いて試したら上手く出来た。