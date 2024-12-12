# dotfiles

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
curl -k https://raw.githubusercontent.com/matt-andersen/dotfiles/refs/heads/main/bash_profile -o ~/.bash_profile &&
  source ~/.bashrc &&
  cat ~/.bash_profile
```
