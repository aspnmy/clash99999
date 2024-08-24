<h1 align="center">
  <img src="https://github.com/MysticalDevil/clash/raw/master/docs/logo.png" alt="Clash" width="200">
  <br>Clash<br>
</h1>

<h4 align="center">A rule-based tunnel in Go.</h4>

<p align="center">
  <a href="https://github.com/MysticalDevil/clash/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/MysticalDevil/clash/release.yml?branch=master&style=flat-square" alt="Github Actions">
  </a>
  <a href="https://goreportcard.com/report/github.com/MysticalDevil/clash">
    <img src="https://goreportcard.com/badge/github.com/MysticalDevil/clash?style=flat-square">
  </a>
  <img src="https://img.shields.io/github/go-mod/go-version/MysticalDevil/clash?style=flat-square">
  <a href="https://github.com/MysticalDevil/clash/releases">
    <img src="https://img.shields.io/github/release/MysticalDevil/clash/all.svg?style=flat-square">
  </a>
  <a href="https://github.com/MysticalDevil/clash/releases/tag/premium">
    <img src="https://img.shields.io/badge/release-Premium-00b4f0?style=flat-square">
  </a>
</p>

##  功能

Clash 是一款多功能且功能强大的代理工具，提供一系列功能来管理网络流量并增强在线隐私和安全性。

原作者项目地址是【https://dreamacro.github.io/clash】，以于2023年10月份删库，
此版本是过去的历史fock备份，主要为了对衍生工具提供代码源支持，最后版本为Nov 3, 2023, v1.18.0

以下是您列出的功能的简要概述：

1. **入站协议**：
   - **HTTP/HTTPS** ：用作 HTTP 和 HTTPS 流量的 Web 代理。
   - **SOCKS5 服务器**：为 TCP 和 UDP 流量提供 SOCKS5 代理服务器。
   - **TUN 设备**：允许通过 Clash 路由所有设备流量，而不仅仅是特定应用程序。
2. **出站协议**：
   - **Shadowsocks**（R）**：支持出站流量的 Shadowsocks 协议。
   - **VMess**：V2Ray 项目用于安全高效的流量路由的协议。
   - **Trojan**：一种安全、高性能的代理协议。
   - **Snell**：类似于 Shadowsocks 的协议，但具有附加功能。
   - **SOCKS5/HTTP（S）**：支持标准的 SOCKS5 和 HTTP/HTTPS 出站流量代理协议。
   - **Wireguard**：一种以其简单性和性能而闻名的现代 VPN 协议。
3. **基于规则的路由**：
   - 允许使用动态脚本和使用各种标准（如域名、IP 地址和进程名称）来确定流量的路由。
4. **虚拟 IP DNS**：
   - 通过使用虚拟 IP 地址进行 DNS 查询，帮助减轻 DNS 污染的影响并提高网络性能。
5. **透明代理**：
   - 能够通过自动管理路由表和规则来重定向 TCP 和 TProxy TCP/UDP 流量。
6. **代理组**：
   - 提供自动回退、负载平衡或延迟测试等功能，以优化多个代理的使用。
7. **远程提供商**：
   - 启用远程代理列表的动态加载，这对于维护最新的代理配置非常有用。
8. **RESTful API 接口**：
   - 提供用于更新配置的综合 API，允许对 Clash 的设置进行编程控制。

Clash 的功能使其成为管理网络流量的灵活工具，对于需要高级代理配置和路由选项的用户特别有用。
*Some of the features may only be available in the [Premium core](https://dreamacro.github.io/clash/premium/introduction.html).*

## Documentation

You can find the latest documentation at [https://dreamacro.github.io/clash/](https://dreamacro.github.io/clash/).

## Credits

- [riobard/go-shadowsocks2](https://github.com/riobard/go-shadowsocks2)
- [v2ray/v2ray-core](https://github.com/v2ray/v2ray-core)
- [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go)

## License

This software is released under the GPL-3.0 license.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDreamacro%2Fclash.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDreamacro%2Fclash?ref=badge_large)
