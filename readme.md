## ブランチとマージをやってみる
1. リポジトリをclone → (A)とする
git clone <url> .
1. (A)にファイルを作成してpush
git push
1. 別のディレクトリにorigin/masterをclone → (B)とする
git clone <url> .
1. (B)でブランチ work を作成
git branch work
1. リモートにブランチ work をpush
git checkout work
1. (A)でファイル追加してpush
1. (B)に origin/master をマージする
git merge origin/master
1. (B)に変更を加えて origin/master へ push
git push origin work master
