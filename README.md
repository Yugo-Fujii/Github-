# Github-Memo
## 一般的なあれ
- git init
- git add . or git add -A 
- git commit -m "ピクミン"
- git branch -M main //1回目のみ
- git remote add origin [新しいリモートリポジトリURL]
- git remote set-url origin [新しいリモートリポジトリURL] //変更する場合
- git push -u origin main
- git push //一度登録した場合はこれ
一度やれば、add,commit,pushの繰り返し

### 注意事項
- githubでレポジトリ作った時にreadmeも合わせて作っていたら先にしないといけないことが増える

# その他
- git remote -v //今いるremote URLの確認
- git remote set-url origin {new url} //新しいremote URLに変更
- git checkout [ブランチ名] //ブランチの変更
- git branch //ブランチの一覧が見れるコマンド
- git push origin develop //developブランチからGithub上のoriginブランチにpushする

# gitのブランチ名をmasterからmainに変更する
- git branch -m master main //ブランチ名の変更
- git push -u origin main //変更したブランチのpush
- github上でデフォルトブランチの変更
- git push origin --delete master //masterブランチの削除のpush

