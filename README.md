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
