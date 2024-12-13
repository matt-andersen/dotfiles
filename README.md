# dotfiles

## Mac Setup

1. Open your .zshrc file:
```
vim ~/.zshrc
```

2. Add the following to your .bashrc:
```
if [ -f ~/.zprofile ]; then
    source ~/.zprofile
fi
```

3. Download the aliases:
```
curl -v -H "Cache-Control: no-cache" https://raw.githubusercontent.com/matt-andersen/dotfiles/refs/heads/main/profile -o ~/.zprofile &&
  source ~/.bashrc &&
  cat ~/.bash_profile
```

## Linux Setup

1. Open your .bashrc file:
```
vim ~/.bashrc
```

2. Add the following to your .bashrc:
```
if [ -f ~/.bash_profile ]; then
    source ~/.bash_profile
fi
```

3. Download the bash profile:
```
curl -v -H "Cache-Control: no-cache" https://raw.githubusercontent.com/matt-andersen/dotfiles/refs/heads/main/bash_profile -o ~/.bash_profile &&
  source ~/.bashrc &&
  cat ~/.bash_profile
```
