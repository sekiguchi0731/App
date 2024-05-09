# 関口さん レベル3 〜ToDoリスト〜

## 準備

1. Node.js バージョン18.15.0 を入れる

    ```bash
    node -v
    # -> バージョンが出力されればOK
    ```

2. プロジェクトをクローンする

    ```bash
    git clone https://github.com/letter-fan/kadai-sekiguchi.git
    ```

3. プロジェクトディレクトリに移動する

    ```bash
    cd kadai-sekiguchi
    ```

4. 依存パッケージをインストールする

    ```bash
    npm ci
    ```

## 初回にやってほしいこと

ブランチを作り、そのブランチ上で作業を進める

```bash
git checkout -b branch-name
# branch-name は好きな名称にする（ex. 1st-submit）
```

## 毎回やること

1. プロジェクトディレクトリに移動する

    ```bash
    cd kadai-sekiguchi
    ```

2. ローカルサーバーを起動する

    ```bash
    npm run dev
    ```

3. ブラウザで http://localhost:3000 を開く

## フォーマッター・リンター

Prettier と ESLint が設定されているので、コミット前に以下の処理を実行することで、コードを綺麗にできる。

- 基本的には以下のショートカットキーを利用するとコードが綺麗になる（Prettierの適用）
  - Mac : `Shift + Option + F`
  - Windows : `Shift + Alt + F`
- 以下のコマンドを実行すると、ESLintが実行される
    ```bash
    npm run lint
    ```
- 赤波線が出ているときに、そこにカーソルを乗せて以下のショートカットキーを利用すると、エラー修正の選択肢が提示される場合がある（提示されない場合もある）
  - Mac : `Command + .`
  - Windows : `Ctrl + .`
