# appGraphQL
## Reactを使用したGraphQLのアプリ

GraphQLを使用してバックエンドサーバーを構築し、Reactを使用してフロントエンドアプリケーション。バックエンドの認証、Apolloデータの管理、Reactとの統合、そして応答性の高いアプリケーションの構築の実践。

![App Demonstration](./images/appGraphQL.png)

### セットアップ

1. プロジェクトのルートで以下のコマンドを実行して依存関係をインストールします。

    ```bash
    $ npm install --legacy-peer-deps
    ```

2. ブラウザで `localhost:4000` にアクセスしてアプリケーションにアクセスします。

3. MongoDBを使用するので、`./server/server.js`内の接続情報を自分のMongoDB情報に変更してください。

    ```javascript
    const MONGO_URI = 'your-mongodb-connection-uri';
    ```
4. 実行
    ```bash
    $ npm run dev
    ```

### Open
```
http://localhost:4000/graphql
http://localhost:4000/#/songs
```

# authGraphQL
## Reactを使用したGraphQLを使ったauthアプリ

GraphQLを使用してバックエンドサーバーを構築し、ReactとGraphQLを使ったauth機能の構築。


### セットアップ

1. プロジェクトのルートで以下のコマンドを実行して依存関係をインストールします。

    ```bash
    $ npm install --legacy-peer-deps
    ```

2. ブラウザで `localhost:4000` にアクセスしてアプリケーションにアクセスします。

3. MongoDBを使用するので、`./server/server.js`内の接続情報を自分のMongoDB情報に変更してください。

    ```javascript
    const MONGO_URI = 'your-mongodb-connection-uri';
    ```
4. 実行
    ```bash
    $ npm run dev
    ```
    
### Open
```
http://localhost:4000/graphql

```

# miniGraphQL
GraphQLの使用方法を確認

### Open
```
http://localhost:4000/graphql
```