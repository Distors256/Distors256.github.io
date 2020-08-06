# git入门：安装与配置

## git安装

### windows：[下载安装程序](https://git-scm.com/)

### linux：
1. 判断有没有安装：git
2. 如果没有
    1. 新版Debian或Ubuntu：sudo apt-get install git
    2. 老版Debian或Ubuntu：sudo apt-get install git-core
    3. 其他版本，先从git官网下载源码，然后解压，依次输入：
        ```
        ./config
        make
        sudo make install
        ```
### Mac os X
1. 安装Xcode
2. 选择菜单“Xcode”->“Preferences”
3. 在弹出窗口中找到“Downloads”
4. 选择“Command Line Tools”，点“Install”


## git配置
```
git config user.name "username"
git config user.email "email@example.com"
```