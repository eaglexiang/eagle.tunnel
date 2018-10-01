# Eagle Tunnel

ET是一个稳定易用的代理工具。由于采用 **自建** ET协议（而非对传统协议的重新实现），故不易被封杀。

## 支持协议

- ET协议
- HTTP代理
- SOCKS5

## 特性

- 用户认证
- 用户限速
- 智能分流
- hosts文件
- 低资源占用
- 配置简单

### 额外

- 脚本一键部署
- Systemd Unit

## 版本选择

所有ET的实现都可扮演服务端和客户端两个角色。

- [Windows](./windows.md)
- [Linux](./linux.md)
- [mac](./mac.md)

### ARM MIPS

目前实现对ARM与MIPS指令集良好支持的有：

- [ET Go](https://github.com/eaglexiang/eagle.tunnel.go) ***目前特性最完整，部署最方便，同时性能表现最好的版本***