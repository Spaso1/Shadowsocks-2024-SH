# Shadowsocks-2024-SH
**理论上所有版本通用**
但我还是推荐几个测试过的稳定版本
- AlibabaCloud3
- Centos 7.X
  
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
Shadowsocks-2024-SH/ss-fly.sh -i 密码 端口
```
如果此步出现 : `Permission denied`
那就请把文件夹权限更改为777,你可以通过宝塔直接更改,也可以通过指令更改,我这里就不赘叙了

执行完成后就可以使用客户端连接使用了~
默认密码是:www.godserver.com
默认端口是:1024
加密方式是:aes-256-gcm

常见错误:
Python未安装:
执行
```
sudo apt update

sudo apt install software-properties-common

```
或
```
yum install python
```

如果出现安装python成功后仍然错误可以使用第二个安装方式
```
Shadowsocks-2024-SH/ss-fly2.sh -i 密码 端口
```
即可,如果没有wget指令可以先安装wget再下载安装

# 这里记录我用过的VPS
- 浪浪云 https://langlangy.cn/
