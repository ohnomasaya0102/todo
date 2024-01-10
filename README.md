Todo-Front プロジェクト
概要
このプロジェクトは、Todoアプリケーションのフロントエンド部分を含んでおり、Svelteフレームワークで構築されています。アプリケーションはDockerを使用してコンテナ化されており、簡単なセットアップとデプロイが可能です。

前提条件
Docker
Node.js（ローカル開発用）
ローカル開発環境のセットアップ


bash

```
git clone
```
プロジェクトディレクトリに移動します
```
cd todo/todo-front
npm関連インストール。svelte-kitも勝手に入ってきます。
```
npm install
```

```
docker-compose up --build
```

Webブラウザを開いて http://localhost:5173/ に移動します。
初期画面が表示されればOK
