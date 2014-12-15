DEPRECATED - This project has moved:

https://github.com/Tahi-project/dotfiles/commit/c845d9151c5f7234d9b05bc7c3bff37329b869b2

###Synopsis

Experimental project to allow developers to pair with proper github attribution.

###Installation

```console

  mkdir ~/bin
  ln -s $PWD/bin/pair ~/bin
  echo '[[ -f /Users/neo/.current_pair ]] && source /Users/neo/.current_pair' >> ~/.zshrc
  echo 'export PATH="$PATH:$HOME/bin"' >> ~/.zshrc
  
```

###Usage

```console

    pair gh-username [gh-username]

```
