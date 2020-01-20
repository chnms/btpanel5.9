Linux面板5.9.2（最终版）

安装要求  
Python版本： 2.6/2.7（安装宝塔时会自动安装）  
内存：128M以上，推荐512M以上（纯面板约占系统10M内存）  
硬盘：100M以上可用硬盘空间（纯面板约占20M磁盘空间）  
系统：CentOS 6.x / 7.x (Ubuntu、Debian、Fedora 请点这里)  
确保是干净的操作系统，不支持32位系统，没有安装过其它环境带的Apache/Nginx/php/MySQL（已有环境不可安装）  

使用SSH 连接工具，挂载磁盘后，根据系统执行框内命令开始安装（大约2分钟完成面板安装）

Centos安装命令：
``` bash
yum install -y wget && wget -O install.sh http://download.bt.cn/install/install.sh && sh install.sh
```
Ubuntu/Deepin安装命令：
``` bash
wget -O install.sh http://download.bt.cn/install/install-ubuntu.sh && sudo bash install.sh
```
Debian安装命令：
``` bash
wget -O install.sh http://download.bt.cn/install/install-ubuntu.sh && bash install.sh
```
Fedora安装命令:
``` bash
wget -O install.sh http://download.bt.cn/install/install.sh && bash install.sh
```
备用节点【广东】：
``` bash
yum install -y wget && wget -O install.sh http://125.88.182.172:5880/install/install.sh && sh install.sh
```
备用节点【香港】：
``` bash
yum install -y wget && wget -O install.sh http://103.224.251.67:5880/install/install.sh && sh install.sh
```
备用节点【美国】：
``` bash
yum install -y wget && wget -O install.sh http://128.1.164.196:5880/install/install.sh && sh install.sh
```

若点击更新后没生效，请尝试重启面板服务：
service bt restart

面板特色功能：

一键配置服务器环境（LAMP/LNMP）  
一键安全重启  
一键创建管理网站、ftp、数据库  
一键配置（定期备份、数据导入、伪静态、301、SSL、子目录、反向代理、切换PHP版本）  
一键安装常用PHP扩展(fileinfo、intl、opcache、imap、memcache、apc、redis、ioncube、imagick)  
数据库一键导入导出  
系统监控（CPU、内存、磁盘IO、网络IO）  
防火墙端口放行  
SSH开启与关闭及SSH端口更改  
禁PING开启或关闭  
方便高效的文件管理器（上传、下载、压缩、解压、查看、编辑等等）  
计划任务（定期备份、日志切割、shell脚本）  
软件管理（一键安装、卸载、版本切换）  

升级到5.9.2专业版  
下载安装:  
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/chnms/btpanel5.9/master/update_pro.sh && bash update_pro.sh
```
