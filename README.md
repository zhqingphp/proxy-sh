# 说明
* 使用脚本前请先安装docker
* ubuntu安装 `sudo apt-get install docker-ce docker-ce-cli containerd.io`

  
## MTPROTO有三种，看需要选择安装
```
bash <(curl -sL "https://raw.githubusercontent.com/zhqingphp/proxy-sh/main/proxy.sh") 参数
```
### 参数说明
```
./proxy.sh t        安装tg官方MTPROTO
./proxy.sh g        安装GO_MTPROTO,go语言写的
./proxy.sh n        安装nginx_MTPROTO,支持白名单
./proxy.sh s        安装SOCKS5,支持帐号认证
./proxy.sh stop     停止全部容器
./proxy.sh del      删除全部容器
./proxy.sh delete   停止删除全部
```
