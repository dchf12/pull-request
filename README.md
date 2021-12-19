# Pull Request
## Pull Requestの予行練習
1. GitHub上で、練習用のリポジトリを作成する 
    - GitHubにログインし、リモートリポジトリを作成
   
    - GitHub上に作成したpull-requestのリポジトリを自分のローカルにcloneする
        ```
        $ git clone git@github.com:【アカウント名】/pull-request.git
        $ cd pull-request
        ```
1. ローカルで、Pull Request用のブランチを作成してpushする
    ```
    $ git checkout -b update-readme   
    """
    ローカルのファイルを修正・変更
    """
    $ git add README.md                       
    $ git commit -m "Update README.md"      
    $ git push origin update-readme      
    ```

1. GitHub上で、Pull Requestを作成する
    - GitHub上に作成したpull-requestのリポジトリページからPull Request作成ページに移動する
    - Pull Request作成ページでは、リクエストを送信する相手に、変更内容の説明を記入する
    - 「Send pull request」ボタンを押して、Pull Requestを送信する

1. GitHub上で、Pull Requestをマージする
    - リポジトリ管理者はPull Requestが送信されたらPull Requestページの上部にある「Commits」タブや「Files Changed」タブでコミット内容をチェックする
    - 問題がなければ、「Merge pull request」ボタンを使ってマージを実行する
    - マージ済みのブランチを削除する場合、「Delete branch」ボタンを押しブランチを削除する

以上