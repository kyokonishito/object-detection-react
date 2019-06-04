# オブジェクト検出 React アプリ

TensorFlow.jsモデルをトレーニングするための詳細なチュートリアルは [こちら](https://github.com/cloud-annotations/training/)
 [(日本語はこちら)](https://kyokonishito.github.io/cloud-annotations-training/object-detection/cli/)
。

## セットアップ
次のコマンドを実行して、レポジトリを`git clone`し、作成されたディレクトリに`cd`します:
```bash
git clone https://github.com/cloud-annotations/object-detection-react.git
cd object-detection-react
```

## npm install
下記のコマンドを実行します:
```bash
npm install
```

> **注：Node8.10.0以降がインストールされている必要があります。**  異なるプロジェクト間でNodeのバージョンを簡単に切り替えるには [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) または[nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) を使うことができます。

## TensorFlow.js モデルのアプリケーションへの追加

オブジェクト検出のチュートリアルから生成された(ダウンロードした) `model_web`ディレクトリをコピーしてこのリポジトリの` public`フォルダに貼り付けてください。

## アプリケーションの実行
下記のコマンドを実行します:
```bash
npm start
```

ブラウザーで [http://localhost:3000](http://localhost:3000) を開き、カメラに検出したいオブジェクトを写してみてください。

