# kitty

MacOS 默认终端不好用，所以我选择了 [kitty](https://sw.kovidgoyal.net/kitty/) 作为终端，它支持 GPU 渲染，启动速度快，配置简单

## 安装

```bash
curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin

# 安装 FiraMono Nerd Font Mono 字体

# 安装 imagemagick
brew install imagemagick

# 选择主题（以 VSCode_Dark 为例）
kitten themes --dump-theme VSCode_Dark > ~/.config/kitty/VSCode_Dark.conf
```

## 配置

```bash
cat kitty.conf >> ~/.config/kitty/kitty.conf
```
