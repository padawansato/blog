# 問題点
- css が読み込まれるのがかなり遅い。

# 記事のアップデート方法

```zsh
# サーバー起動
$ hugo serve -D
# 記事作成
$ hugo new posts/hoge.md
# s/draft\: true/draft\: false/g
# サーバー停止
# Cntl + C
# 静的記事生成
$ hugo
# 諸々をリモートリポジトリへ push
$ git commit -am "Add blog post"
```

- [Github Actions を確認](https://github.com/psato/blog/actions)
- [ブログ](https://github.com/psato/blog/)を確認

