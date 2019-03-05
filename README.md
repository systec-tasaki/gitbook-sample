# ようこそ！！　テストプロジェクトへ！

## ここでは Gitbook を用いた設計書のテストを行っています。

## 変更手順

### １．node.js のインストール

[Node.js 公式](https://nodejs.org/en/download/) から Node.js をダウンロードしインストールしてください。  
インストール後は、環境パスで npm にパスが通るようにしておきます。  
参考：https://qiita.com/maecho/items/ae71da38c88418b806ff

### 2. レポジトリの取得

```
git clone https://github.com/mantaroh/gitbook-sample
```

※自分のレポジトリに、フォークしてやったほうが楽かも

### 3. 関連モジュールのインストール

```
npm install
```

### 4. ドキュメントのビルド

```
npm run build
```
or
```
gitbook build
```

### 5. ローカルでの確認

```
gitbook serve
```

### 6. github pages へのデプロイ
```
npm run publish
```
