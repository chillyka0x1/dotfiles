# Dotfiles

![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnubash&logoColor=white&labelColor=2B2B2B)
![Vim](https://img.shields.io/badge/-Vim-019733?style=flat&logo=vim&logoColor=white&labelColor=2B2B2B)
![tmux](https://img.shields.io/badge/-tmux-1BB91F?style=flat&logo=tmux&logoColor=white&labelColor=2B2B2B)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white&labelColor=2B2B2B)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black&labelColor=2B2B2B)

My personal Linux configuration files.

## 📦 Contents

- `.bashrc` — bash aliases and prompt
- `.vimrc` — vim configuration
- `.tmux.conf` — tmux config (mouse support, vi mode)
- `.gitconfig` — git aliases and signing
- `nano.nanorc` — nano configuration

## 🚀 Installation

```bash
git clone https://github.com/chillyka0x1/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

The install script creates symlinks from `~` to the files in this repo.

## ✨ Highlights

### Bash Aliases
```bash
alias ll='ls -lah'
alias ports='ss -tlnp'
alias logs='journalctl -f -u'
alias myip='curl -s https://ifconfig.me'
alias dc='docker compose'
```

### Git Helpers
```bash
alias gs='git status'
alias gp='git push'
alias gl='git log --oneline --graph --decorate -20'
```

## 📜 License

MIT
