# centos-shadowsocks-libev


#centos安装宝塔：

yum install -y wget && wget -O install.sh http://download.bt.cn/install/install_6.0.sh && sh install.sh

#查看内核版本命令：

uname -r

#适用于centos7的shadowssocks-libev一键安装脚本

#一键脚本已集成TCP优化、自动开启Google BBR（限 4.9 或更高版本内核）、自动安装 shadowsocks-libev

#来源：https://www.24kplus.com/linux/1371.html

#使用方法：

wget https://raw.githubusercontent.com/wexiuwexiu/centos-shadowsocks-libev/main/centos-shadowsocks-libev.sh

chmod +x centos-shadowsocks-libev.sh && ./centos-shadowsocks-libev.sh
