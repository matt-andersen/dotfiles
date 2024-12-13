# dotfiles

## Mac Setup

1. Open your .zshrc file:
```
vim ~/.zshrc
```

2. Add the following to your .zshrc:
```
if [ -f ~/.zprofile ]; then
    source ~/.zprofile
fi
```

3. Download the profile:
```
curl -v -H "Cache-Control: no-cache" https://raw.githubusercontent.com/matt-andersen/dotfiles/refs/heads/main/profile -o ~/.zprofile &&
  source ~/.zshrc &&
  cat ~/.zprofile
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

1. Download the profile:
```
curl -v -H "Cache-Control: no-cache" https://raw.githubusercontent.com/matt-andersen/dotfiles/refs/heads/main/profile -o ~/.bash_profile &&
  source ~/.bashrc &&
  cat ~/.bash_profile
```
