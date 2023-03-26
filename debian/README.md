# github setup
- `ssh-keygen -t rsa` で秘密鍵と公開鍵を作成
- https://github.com/settings/keys へ公開鍵を登録し、`ssh -T git@github.com` で接続を確認
- 通信をhttpからsshに変更 `git remote set-url origin git@github.com:`
- originのusernameとreponameを指定 `git remote set-url origin git@github.com:<username>/<reponame.git>`