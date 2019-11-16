##vagrant+virtualbox 搭建虚拟机
1.按照官网步骤安装 vagrant  和 vartualbox
2.提前下载好virtualbox.box 虚拟机文件
3.添加virtualbox.box 到vagrant， vagrant box add centos/7(虚拟机名称)  /***/**/virtualbox.box(box 路径)
4.启动虚拟机 vagrant up ，让后进入虚拟机 vagrant ssh  ，切换root： sudo -s
5.修改root密码，xshel等工具可以链接：
  a: vi /etc/ssh/sshd_config
  b: 修改属性 PasswordAuthentication no -> PasswordAuthentication yes
  c: service sshd restart
6.修改root密码： passwd（至此大功告成）
