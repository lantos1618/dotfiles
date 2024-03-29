# Dotfiles
## General
```bash
sudo apt update & sudo apt upgrade -y
sudo apt install -y python3 python3-pip build-essential zsh neovim tmux git gcc g++ make curl

sudo apt-get install fonts-powerline


curl -fsSL https://test.docker.com | sh 
sudo usermod -aG docker $USER

sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose

sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting


sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'


curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt install nodejs

curl -o- -L https://yarnpkg.com/install.sh | bash

curl https://nim-lang.org/choosenim/init.sh -sSf | sh

```

## Arraymancer
```bash
sudo apt -y install build-essential libopenblas-dev liblapack-dev
```
## Pytorch

```bash
pip3 install torch
```

## vscode

```json
{
    "telemetry.telemetryLevel": "off",
    "window.dialogStyle": "custom",
    "window.titleBarStyle": "custom",
    "zigLanguageClient.path": "/home/anon/zls/zls",
    // "zig.buildOnSave": true,
    "debug.onTaskErrors": "showErrors",
    "debug.allowBreakpointsEverywhere": true,
    "workbench.colorTheme": "Ayu Mirage Bordered",
    "[zig]": {
        "editor.defaultFormatter": "SuperAuguste.zls-vscode"
    },
    "omnisharp.useGlobalMono": "always",
    "git.autofetch": true
}
```
