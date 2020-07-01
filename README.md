"# Status-Sever"
## 描述
云探针 多服务器探针 云监控 多服务器云监控 服务器状态监控 Status-Sever

本代码基于ServerStatus-Toyo 最新版本修改 修改了JS文件美化样式等。

## 功能
服务器在线状态
服务器国家
在线人数统计
服务器硬盘 CPU 内存占用率
流量统计
服务器实时下载上传
...

## 演示图片

![](https://s1.ax1x.com/2020/07/01/NTCRPO.png)


## 安装方法

显示服务端管理菜单

Centos
```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/status.sh && chmod +x status.sh
bash status.sh s
```

显示客户端管理菜单

Centos
```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/status.sh && chmod +x status.sh
bash status.sh c
```

执行安装程序后，将本页面代码全部替换掉服务器上的页面代码
替换配置文件，重启ServerStatus


## 相关开源项目 ： 
* ServerStatus-Toyo：https://github.com/ToyoDAdoubiBackup/ServerStatus-Toyo
* ServerStatus：https://github.com/BotoX/ServerStatus


