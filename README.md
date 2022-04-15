### アプリケーション名
　**ZAICO**
 
### アプリケーションの概要
　**グルノーブル美容技術専門学校の在庫管理システム(実用可済み)**   
 
### 工夫した点
- Vue.jsを用いることでリアクティブにデータ変更と表示更新を行うようにしました。
- 管理者と一般ユーザーを分けて、データ変更については最小限の管理者のみに制限しました。
- モバイルファーストを意識したレスポンシブWebデザインで設計しました。
- PDF出力をできるようにしてデータ利用の幅を広くしました。

### デモ
　[サイトはこちらから](http://murmuring-headland-13028.herokuapp.com/)
 
### アプリケーションで使っている技術
- インフラ: heroku 
- データベース: MySQL  5.7.26
- 開発環境: MAMP 4.2.0
- 言語: Laravel 9, Vue.js

### アプリケーションの機能
- 認証機能
- 教材データのCRUD機能(一括追加や一括削除も含む), 履歴データのCRD機能
- 教材データのお気に入り機能
- ページネーション機能
- 教材の入庫・出庫の登録機能
