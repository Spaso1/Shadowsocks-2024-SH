# Shadowsocks-2024-SH
一键安装SHadowsocks脚本
未安装Git请先:
```
yum -y install git
```
或
```
 apt-get update && apt-get -y install git
```
之后克隆此仓库
```
git clone https://github.com/Spaso1/Shadowsocks-2024-SH
```
克隆完成后执行:
```
Shadowsocks-2024-SH/ss-fly.sh -i abcdef20060113 10080
```
如果此步出现 : `Permission denied`
那就请把文件夹权限更改为777,你可以通过宝塔直接更改,也可以通过指令更改,我这里就不赘叙了

执行完成后就可以使用客户端连接使用了~
