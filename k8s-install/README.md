# ansible
k8s安装

1. 修改主机名，配置hosts和安装内核
  ansible-playbook -i hosts start01.yml

2. 安装docker和k8s相关组件
  ansible-playbook -i hosts start02.yml
3. 手动初始化集群,并配置负载均衡

4. 修改修改负载均衡地址，记录加入集群命令，写入task文件,node节点加入集群
  ansible-playbook -i hosts start03.yml
