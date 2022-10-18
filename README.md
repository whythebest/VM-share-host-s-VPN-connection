# 利用clash使虚拟机共享主机VPN连接

1. Clash Port:7890，打开同局域网允许连接按钮Allow LAN，获取当前主机IP，得到IP:7890
2. vm选择桥接模式，Linux打开代理输入此IP及端口即可连接成功。

无需再在vm里安装clash即可实现与主机共享。

