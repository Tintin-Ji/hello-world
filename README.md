# hello-world 
I am trying to develop basic coding skills in languages such like python and Matlab, which are great tools in tackling the problems with complexity.
Jun. 7th, 2019 @ Shanghai in SUFE
Today, I will build a vpn myself and learn some python.

**step1 BG:Mainland 🇨🇳 https://www.banpie.info/shadowsocks-pac-gfw/ as a guidebook (also refer to https://flyzyblog.com/install-ss-ssr-bbr-in-one-command/#ss)**  
**step2** Shadowsocks for mac: I downloaded it on Github.https://github.com/shadowsocks/ShadowsocksX-NG/releases  
**step3** set ssh root@ IP -P 端口号
（插曲）ssh 安装时候出现了[no acceptable C compiler found in $PATH]--我当时的Mac上没有C编译器,然后为了用terminals命令直接安装各种软件，需要在Mac环境下使用【inux下有很方便的包管理器如:apt-get、yum】的代替品，先要用Mac自带的ruby【但是如果是第一次用ruby，再用之前还要安装Xcode，并且在terminal里面执行[sudo xcodebuild -license]】,查看Xcode文件后 agree，才能使用ruby
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" #安装Homebrew. 
brew install gcc  #这样就可以安装了  
**step3.5** 重设ssh(在设置了ssh之后，没有配置shadowsocks直接退出的解决方案）
    [ssh-keygen -R 192.168.1.203(你远程服务器的IP)] 从而清除记录的keyhosts文件
