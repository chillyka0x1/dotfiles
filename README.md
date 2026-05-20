# Dotfiles

My personal Linux configuration files.

## 📦 Contents

- `.bashrc` — bash aliases and prompt
- `.vimrc` — vim configuration
- `.tmux.conf` — tmux config (mouse support, vi mode)
- `.gitconfig` — git aliases and signing
- `nano.nanorc` — nano configuration

## 🚀 Installation

```bash
git clone https://github.com/[username]/dotfiles.git ~/.dotfiles
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
