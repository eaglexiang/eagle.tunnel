# Eagle Tunnel

ET是一个稳定易用的代理工具，采用 **自建** ET协议（而非对传统协议的重新实现）。特点是不易被封杀，以及对系统资源的低占用率。

## 特性

### 支持协议

- ET协议
- HTTP代理
- SOCKS5

### 协议特性

- 用户认证
- 用户限速
- 智能分流
- DNS智能安全解析

### 额外

- hosts
- 脚本一键部署
- Systemd Unit
- 在线管理

## 版本选择

### Windows

- [ET Go](https://github.com/eaglexiang/eagle.tunnel.go)（跨平台，目前特性最完整，部署最方便，同时性能表现最好的版本）
- [ET D](https://github.com/eaglexiang/eagle.tunnel.dotnet)（自带图形界面，使用[ET DNC LIB](https://github.com/eaglexiang/eagle.tunnel.dotnet.core.lib)来提供协议或特性的支持）
- [ET DNC](https://github.com/eaglexiang/eagle.tunnel.dotnet.core)（跨平台，使用[ET DNC LIB](https://github.com/eaglexiang/eagle.tunnel.dotnet.core.lib)来提供协议或特性的支持）

### Linux

- [ET Go](https://github.com/eaglexiang/eagle.tunnel.go)（跨平台，目前特性最完整，部署最方便，同时性能表现最好的版本）
- [ET DNC](https://github.com/eaglexiang/eagle.tunnel.dotnet.core)（跨平台，使用[ET DNC LIB](https://github.com/eaglexiang/eagle.tunnel.dotnet.core.lib)来提供协议或特性的支持）

### Mac

- [ET Go](https://github.com/eaglexiang/eagle.tunnel.go)（跨平台，目前特性最完整，部署最方便，同时性能表现最好的版本）
- [ET DNC](https://github.com/eaglexiang/eagle.tunnel.dotnet.core)（跨平台，使用[ET DNC LIB](https://github.com/eaglexiang/eagle.tunnel.dotnet.core.lib)来提供协议或特性的支持）

### ARM MIPS

目前实现对ARM与MIPS指令集良好支持的有：

- [ET Go](https://github.com/eaglexiang/eagle.tunnel.go)（跨平台，目前特性最完整，部署最方便，同时性能表现最好的版本）