
# soft ether安装设置
make

./vpnserver start


### 服务器设置：
```
./vpncmd
1
host:port   //用来连接VPN的IP和端口
HUB(default)
password
```
### HUb设置
HubCreate VPN 创建HUB
```
Hub VPN
UserCreate  //用来登陆VPN服务的用户
UserList
UserPasswordSet
```

### 客户端设置
端口、用户名密码、HUB
