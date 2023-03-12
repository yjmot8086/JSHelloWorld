# JSHelloWorld GitHub 学習ページ

## [GitHub](https://github.co.jp/) へサインインします
+ Username と Password を入力します

## 新しいレポジトリを作成します
+ Top Repositories の New ボタンを押します
+ Repository name に __JSHelloWorld__ を入力します
+ Public を選択します
+ __README.md__、__.gitignoe__ を追加しないで、Create repository ボタンを押します

## ローカルリポジトリのディレクトリを作成します
+ エクスプローラーでフォルダーを右クリック、新規作成 -> フォルダー を選択します
+ フォルダー名を __JSHelloWorld__ に変更します
+ さらに、次の構造になるようにフォルダーとファイルを作成します

    ```  
    C:.
    │  .gitignore
    │
    └─docs
        │  README.md
        │
        └─images
    ```

## Git Bash を起動します
+ フォルダーを右クリック、その他のオプションを表示 -> Git Bash Here を選択します

## ローカルリポジトリにコミットして、リモートリポジトリにプッシュします
 
    git init
    git add .
    git commit -m "First commit."
    git branch -M main
    git remote add origin https://github.com/yjmot8086/JSHelloWorld.git
    git push -u origin main

## よく使う Git コマンド一覧です
+ 指定のフォルダー配下の変更や、新規作成した全てのファイルやフォルダーを追加するコマンドです

     ```
     git add .
     ```
+ 指定のフィルダー配下のファイルを追加する場合のコマンドです

    ```
    git add index.html
    git add assets/css/reset.min.css
    ```
## GitHub Pages を設定します
+  [GitHub](https://github.co.jp/) へサインインします
+ __JSHelloWorld__ リポジトリに移動します
+ Settings -> Pages と選択していきます
+ Branch の項目が None となっているので、デフォルトブランチ main に変更して Saveボタンを押します
+ url 表示に時間がかかる場合があります
