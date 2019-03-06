# ようこそ！！　テストプロジェクトへ！

## ここでは Gitbook を用いた設計書のテストを行っています。

## 変更手順 (手動)

### １．node.js のインストール

[Node.js 公式](https://nodejs.org/en/download/) から Node.js をダウンロードしインストールしてください。  
インストール後は、環境パスで npm にパスが通るようにしておきます。  
参考：https://qiita.com/maecho/items/ae71da38c88418b806ff

### 2. レポジトリの取得

```
git clone https://github.com/mantaroh/gitbook-sample
```

※自分のレポジトリに、フォークしてやったほうが楽かも (参考：https://qiita.com/YumaInaura/items/acff806290c8953d3185 )

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

## 変更手順 (Web から自動)

### 1. GitHub のレポジトリ上で対象ファイルを開く

例： README.md をクリック

### 2. 編集ボタンをクリック

ファイルを画面に開いた状態で右上にある「えんぴつ」アイコンをクリック

### 3. 編集

煮るなり焼くなりご自由に

### 4. コミット＆プッシュ

編集画面一番下にコミットするためのメッセージを入力する箇所があるので、
コミットログを書いて「コミット」ボタンをクリック

### 5. しばらく待つ

[CircleCI](https://circleci.com/gh/mantaroh/workflows/gitbook-sample/tree/master) でビルドされ、公開されるまで待つ

注意：GitPages はファイル変更後５分ほど反映に時間がかかるみたいです。