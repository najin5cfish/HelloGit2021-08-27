# gitの使いかた
## 初期設定
version確認
```
git --version
```
user登録
```
git config --global user.name {userネーム}
git config --global user.email {メールアドレス}
```
登録内容確認
```
git config --list
```

# 使いかた
githubにアップロードしたいディレクトリに移動して初期化
```
git init
```
インデックス(一時的に保存される領域)に追加
```
git add ./
```
インデックスに存在するファイルをローカルレポジトリに追加
```
git commit -m "コメント(変更点等)"
```
```
git remote add origin https://github.com/ユーザ/[作成したリポジトリ].git
```
github上のリモートレポジトリにpush
```
git push origin master
```