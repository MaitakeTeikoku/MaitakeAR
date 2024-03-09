# MaitakeAR
## Todo
1. GitHubからクローン。
    ```bash
    git clone https://github.com/MaitakeTeikoku/MaitakeAR.git
    ```
1. Reactのプロジェクトを作成。
    ```bash
    npx create-react-app test-react --template typescript
    ```
1. コミットしてプッシュ。
    ```bash
    git add .
    git commit -m "commit"
    git push
    ```
    * エラーが起きるときは以下を実行してみる。
        ```bash
        git config http.postBuffer 524288000
        git config --global http.version HTTP/1.1
        ```
