# wg

以下适用于CENTOS7系统自动执行脚本
按步骤即可
yum install -y wget && wget https://raw.githubusercontent.com/chinamore/wg/master/wireguard_install.sh && chmod +x wireguard_install.sh && ./wireguard_install.sh
更新内核以后执行以下代码
./wireguard_install.sh
启动限制措施
yum install -y wget && wget https://raw.githubusercontent.com/chinamore/wg/master/ip.sh && chmod +x ip.sh && ./ip.sh
