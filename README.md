# zsh insert dot dot slash

Tired of ../../../../../? Use insert-dot-dot-slash, Luke!

![usage example](http://i.imgur.com/C26hqA9.gif)

# Installation

You can install plugin via [antigen](https://github.com/zsh-users/antigen):
```
antigen bundle kovetskiy/zsh-insert-dot-dot-slash
```

Or manually:
```
git clone https://github.com/kovetskiy/zsh-insert-dot-dot-slash ~/.zsh-insert-dot-dot-slash/
```
and add including to your `.zshrc`:
```
source ~/.zsh-insert-dot-dot-slash/plugin.zsh
```

# Usage

First, you should add binding, for example with `CTRL+/`
```
bindkey -v '^_' insert-dot-dot-slash
```

After that you should reload zsh.
