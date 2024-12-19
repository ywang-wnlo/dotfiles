# ZSH

在 MacOS 以及 Linux 上习惯用 ZSH 作为终端，不仅美化更加方便，而且命令补全更加强大

## 安装

```bash
# 安装 oh-my-zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# 安装 p10k 主题
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k

# 安装 zsh-autosuggestions
git clone --depth=1 https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# 安装 zsh-syntax-highlighting
git clone --depth=1 https://github.com/zsh-users/zsh-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

## 配置

```bash
# 根据需要修改 .zshrc 文件
cp .zshrc ~/
```··
