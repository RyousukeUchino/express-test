Expressの始め方

作業用ディレクトリを作ってそこに移動してから以下を行う

■npmの初期化
$ npm init

■Expressのひな型を作成する
ジェネレータがあるので、プロジェクトのひな型を自動で生成する
今回のテンプレートエンジンはEJSを採用する

$ npm install express-generator
$ ./node_modules/.bin/express --view=ejs

■必要なモジュールのインストール
ひな型の作成が終了したらモジュールをインストールする
$ npm install

■アプリケーションの起動
ひな型が自動で作成されたのでサンプルを起動します

$ npm start