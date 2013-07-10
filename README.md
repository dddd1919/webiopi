webiopi使用说明
=======
##概述

> WebIOPi是python编写的运行在Pi上的web版GPIO控制器，可以在Pi上运行该项目并对GPIO进行输入输出以及开关控制。

##初始化步骤

1. 进入到根目录的 [pubilc](https://github.com/dddd1919/webiopi/tree/master/python) 目录下，使用 [setup.py](https://github.com/dddd1919/webiopi/blob/master/python/setup.py)文件进行安装，命令：

>     sudo python setup.py install  # 需要sudo权限

2. 安装完毕后即可启动web服务，命令：

>     sudo python webiopi.py

> 过程中需要输入一系列的参数，可以默认空格跳过，完毕后可见web服务启动地址和端口，

>     Started at https://xxx.xxx.xx.xxx:8000/webiopi

>  应用比较高级，https登陆需要密码，默认用户名： `webiopi` , 默认密码是： `raspberry`
