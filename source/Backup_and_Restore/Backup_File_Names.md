# 16.2备份文件命名

新版vzdump将利用虚拟机类型和备份时间编码备份文件名称，示例如下：

`vzdump-lxc-105-2009_10_09-11_04_43.tar`

这样就可以在同一目录下保存同一虚拟机的多个备份文件。

可以设置参数maxfiles指定同一虚拟机最大备份文件数量。