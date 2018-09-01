# OpenvpnGameRoutes
### Game Routes for OpenVPN
OpenVPN上使用的游戏路由表。Openvpn配合 @wangyu- 大佬的UDPspeeder和udp2raw两款程序可使Openvpn变为适合游戏联机的加速器。（项目地址https://github.com/wangyu-) 由于使用Openvpn只是游戏用途，并且分享给朋友使用。因此有必要避免扶墙来回避不必要的麻烦。OpenVPN默认代理全部流量，添加路由表后可使只有对应游戏的IP走代理。

## 使用方法
直接将路由表命令地址添加进客户端的配置文件中，另需要配合route-nopull和max-routes 1000这个参数一起使用
