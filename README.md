# yabai
This repository contains config file for yabai.



## Installation

### [Disabling System Integrity Protection](https://github.com/koekeishiya/yabai/wiki/Disabling-System-Integrity-Protection)

### [brew](https://brew.sh/)

If you find it hard to connect to the server, you may use [清华大学开源软件镜像站](https://mirrors.tuna.tsinghua.edu.cn/).

### [yabai](https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release))

#### Install

```bash
brew install koekeishiya/formulae/yabai

# start yabai
yabai --start-service
```

#### Update

```bash
# stop yabai
yabai --stop-service

# upgrade yabai
brew upgrade yabai

# start yabai
yabai --start-service
```

#### yabairc

```bash
# create empty configuration file and make it executable
touch ~/.yabairc
chmod +x ~/.yabairc
```



You may refer to [official examples](https://github.com/koekeishiya/yabai/tree/master/examples) or refer to [my config file](https://github.com/Hydraallen/yabai_Usage/blob/main/.yabairc).

#### [Uninstall](https://github.com/koekeishiya/yabai/wiki/Uninstalling-yabai)



### [skhd](https://github.com/koekeishiya/skhd)

### Install

```bash
  brew install koekeishiya/formulae/skhd
  skhd --start-service
```

You may refer to [official examples](https://github.com/koekeishiya/skhd/tree/master/examples) or refer to [my config file](https://github.com/Hydraallen/yabai_Usage/blob/main/.skhdrc).



## Usage(Based on my config file)

+ `ctrl + alt + backspace` Close active application (快速关闭窗口)
+ `ctrl + alt + 0` Equalize size of windows (平铺当前界面所有窗口)
+ `ctrl + alt + 0x24` full screen / un-full screen(切换窗口全屏) 0x24 表示回车
+ `cmd + shift + h/j/k/l` window resize调整窗口大小
+ `shift + alt + h/j/k/l`swap window & move window in floating mode (移动窗口)
+ `ctrl + 1/2/3/4/5/6/7/8/9` 在 9 个桌面之间切换
+ `cmd + shift + 1/2/3/4/5/6/7/8/9` 将窗口发送到某个其他桌面
+ `cmd + shift + e/r`  Rotate windows clockwise and anticlockwise (旋转窗口)
+ `ctrl + alt + space`  float / Unfloat window (切换窗口浮动)
+ `cmd - return` 启动终端(kitty)
+ `ctrl + e` 切换为平铺模式
+ `ctrl + s` 切换为堆叠模式
+ `shift + cmd + n` 创建一个新桌面，并把当前活动的窗口发送到新桌面，并且自动跳转到新桌面. 需要 jq 支持 (`brew install jq`)
+ `ctrl + up/down`在 stack 模式下通过方向键切换窗口
+ `cmd + left/right` 在 bsp 模式下通过方向键切换窗口 



