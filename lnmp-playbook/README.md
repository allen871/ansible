centos6下ansible-playbook自动安装nginx php mysql

1. 下载mysql-5.6.23-linux-glibc2.5-x86_64.tar.gz 到目录lnmp-playbook/roles/mysql/files
2. ansible-playbook -i host start.yml

注：
python升级之后，需要改回默认，否则yum调用报错
redis使用WorkerMan，需安装如下扩展
pcntl 源码自带
libevent-devel libevent需要
libevent 第三方扩展需下载
禁用函数stream_socket_server，需要开放
