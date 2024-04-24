# GraphQLとReactを使用した歌詞アプリ

GraphQLを使用してバックエンドサーバーを構築し、Reactを使用してフロントエンドアプリケーション。バックエンドの認証、Apolloデータの管理、Reactとの統合、そして応答性の高いアプリケーションの構築の実践。音楽リスト一覧表示ページを「/」に、詳細ページを「/songs/{songId}」に、音楽作成ページを「/songs/new」に割り当てるアプリケーション。

<img src="./images/appGraphQL.png" width="700">

### GraphQL schema
<img src="./images/appGraphQL_Schema.png" width="700">

### Application Architecture
<img src="./images/appGraphQL_AppArchitecture.png" width="250">

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