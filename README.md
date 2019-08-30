# ansible-haproxy-apache-keepalive
使用ansible实现apache应用的高可用和负载均衡。
# 使用Ansible roles是为了层次化、结构化地组织Playbook
这里使用的是ansible-galaxy生成。
# 关于roles的角色：
这里高可用使用的是keepalived，负载均衡使用的是haproxy，后端的发布页面使用apache
