# 服务端

```
./server -p 8389 -k foobar -m aes-128-cfb &
```

# 客户端

```
./local -p 8389 -k foobar -s 127.0.0.1 -l 1090 -m aes-128-cfb &
```
