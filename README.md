# 简介

将常用的配置做了整理，用于日常快速设置环境

设置包括:

    * oh-my-zsh 开启插件plugins: vi-mode git jump mvn gradle brew osx tmux zsh_reload colored-man-pages sudo
    * vim 日常配置


## 日常软件安装

Debian
```shell
apt install neovim screen zsh git
```

FreeBSD 
```shell
sudo pkg install nvim screen zsh git
```



## 设置配置

```shell
    cd 
    git clone https://github.com/jiahualong/iconf-pub .iconf-pub
    .iconf-pub/init.sh
```

## 设置zsh为默认shell

```shell
chsh -s /bin/zsh
curl https://mise.run/zsh | sh
```

## 如需要卸载请删除以下文件

```shell
rm -rf ~/.iconf-pub
rm -rf ~/.oh-my-zsh
rm -rf ~/.oh-my-zsh-powerline-theme
rm -rf ~/.tmux.conf
rm -rf ~/.vimrc
rm -rf ~/.vim
rm -rf ~/.viminfo
rm -rf ~/.zshrc
```

## 快捷方式

| command | info | 
|:---|:---|
| **zsh** |  |
| `vizsh` | 使用 vim 打开zsh配置文件，改proxy可以`vizsh`进行修改 |
| `sozsh` | 修改了zsh配置文件后在当前shell需要重新加载zsh配置，使用`sozsh`可重新加载配置 |