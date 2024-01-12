# appGraphQL
## Reactを使用したGraphQLのアプリ

GraphQLを使用してバックエンドサーバーを構築し、Reactを使用してフロントエンドアプリケーション。バックエンドの認証、Apolloデータの管理、Reactとの統合、そして応答性の高いアプリケーションの構築の実践。


### セットアップ

1. プロジェクトのルートで以下のコマンドを実行して依存関係をインストールします。

    ```bash
    $ npm install --legacy-peer-deps
    ```

2. ブラウザで `localhost:4000` にアクセスしてアプリケーションにアクセスします。

3. MongoDBを使用する場合は、`./server/server.js`内の接続情報を自分のMongoDB情報に変更してください。

    ```javascript
    const MONGO_URI = 'your-mongodb-connection-uri';
    ```

# miniGraphQL
GraphQLの使用方法を確認