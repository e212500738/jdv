
简单说明
xianyu或pdd 买一个fei xun 的N1盒子,大约140左右, 要求装卖家装openwrt系统, 电脑网线连盒子,盒子可以连无线. 下载putty,用putty连接盒子 地址192.168.1.1 端口 22
输入下面命令,按提示操作

jd-shell 安装 两个命令:

wget -q https://gitee.com/xr2021/jd-shell/raw/v3/install_scripts/docker_install_jd.sh -O docker_install_jd.sh && chmod +x docker_install_jd.sh && bash docker_install_jd.sh


docker exec -it jd /bin/bash

进控制面板 路由器ip:5678 通常 192.168.1.1:5678  用户名密码 admin/adminadmin 不对的话是amdin5678/password 版本太多
安装完成后定时任务没有更新的话自己去docker/congig 复制出来在面板填写
