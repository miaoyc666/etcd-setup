# etcd-setup
etcd安装和集群设置

#### 操作步骤, 在三个节点分别执行以下语句:
```bash
yum install etcd
cp etc/etcd1.conf /etc/etcd/etcd.conf   # 不同节点拷贝不同文件
systemctl enable etcd
systemctl start etcd
systemctl status etcd
```

#### etcdctl v2语法
```bash

```


#### etcdctl v3语法
```bash

```