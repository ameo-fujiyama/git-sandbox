# Git with VScodeの設定手順

## git for windowsのインストール
- Use a TrueType font in all console windows にはチェックを入れない。日本語などの多バイト文字が文字化けする可能性あり。
- Use Git from the Windows Command Prompt｣を選択。Git BashだけじゃなくコマンドプロンプトやパワーシェルからもGitが使える。

## gitの初期設定
```
$ git config --global user.name 'username'
$ git config --global user.email 'username@example.com'
$ git config --global core.editor 'code --wait'
$ git config --global merge.tool 'code --wait "$MERGED"'
$ git config --global push.default simple
```

## Visualstudio Code (VS Code)のインストールと設定
  - [君には1時間でGitについて知ってもらう](https://qiita.com/jesus_isao/items/63557eba36819faa4ad9) → VScodeによるCommitの操作が分かりやすい。ただしgithubじゃない。
- [GitHubとVSCODEの連携方法](https://qiita.com/yu0313/items/4f95fc0b7e544c42e107)

## githubの設定
1. githubにアカウントをつくる
2. githubでリポジトリを作る
3. ローカルPCにリポジトリ用のフォルダを作る。
4. そのフォルダにいって，git bashからgit cloneして，githubに作ったリポジトリをもってくる。
5. VScodeでそのフォルダを開く。
6. VScodeのファイル＞名前を付けてワークスペースを保存をしておくとよさそう。
7. 拡張子.code-workspaceは.gitignoreに登録したほうがよいかも。

 - [GitとGithubの基本知識](https://qiita.com/moonbass630/items/383fc8300a83784e4c82)
 - [SourceTreeとGithubでGitの練習環境をつくる](https://qiita.com/naoki85/items/4f44601f1365c18035f4)
  


