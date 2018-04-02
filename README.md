# gitconfig.d

個人的なgitの設定になります．

## 導入
gitをインストールした上で，`~/.gitconfig`を作成し，以下のようにして読み込みます．

```
[include]
	path = ~/gitconfig.d/gitconfig.common
[core]
	excludesfile = ~/gitconfig.d/gitignore
```

