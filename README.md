# VSCodeからGitHubにプッシュする
## ローカルリポジトリの作成
- git initコマンド
- VSCodeのソース管理からリポジトリを初期化
## ローカルリポジトリにファイルを追加
- index.html、style.cssを作成
- git add .
- VSCodeからステージに追加
- git commit -m '最初のコミット'
- VSCodeからコミット
## リモートリポジトリの追加
- git remote add origin <リモートリポジトリのURL>
## リモートリポジトリにプッシュする
- git push -u origin master
## 追跡の対象から外す
- .gitignore作成
- ディレクトリごと対象から外す場合は'/env/'の様に記述