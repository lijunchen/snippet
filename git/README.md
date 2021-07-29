# git

```
git config user.name "Your Name Here"
git config user.email your@email.com

git config --global user.name "Your Name Here"
git config --global user.email your@email.com

git config --global credential.helper store

git commit --amend --author="Author Name <email@address.com>" 
```

.gitconfig
```
[user]
    email = x
    name = x
[alias]
    graph = log --graph --abbrev-commit --decorate --oneline --all
[http]
    proxy = socks5://x
[https]
    proxy = socks5://x
[core]
    editor = vim
[credential]
    helper = store
```
