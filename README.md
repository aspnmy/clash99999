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
## 中文说明[https://github.com/aspnmy/clash99999/blob/master/README-zh.md]
## Features

The original author's project address is [https://dreamacro.github.io/clash], and the library will be deleted in October 2023.
This version is a historical fock backup of the past, mainly for code source support for derivatives, and the last version is Nov 3, 2023, v1.18.0


Clash is a versatile and powerful proxy tool that offers a range of features to manage network traffic and enhance online privacy and security. Here's a brief overview of the features you've listed:

1. **Inbound Protocols**:
   - **HTTP/HTTPS**: Serves as a web proxy for HTTP and HTTPS traffic.
   - **SOCKS5 Server**: Provides a SOCKS5 proxy server for TCP and UDP traffic.
   - **TUN Device**: Allows for routing all device traffic through Clash, not just specific applications.

2. **Outbound Protocols**:
   - **Shadowsocks(R)**: Supports the Shadowsocks protocol for outbound traffic.
   - **VMess**: A protocol used by the V2Ray project for secure and efficient traffic routing.
   - **Trojan**: A secure, high-performance proxy protocol.
   - **Snell**: A protocol similar to Shadowsocks but with additional features.
   - **SOCKS5/HTTP(S)**: Supports standard SOCKS5 and HTTP/HTTPS proxy protocols for outbound traffic.
   - **Wireguard**: A modern VPN protocol known for its simplicity and performance.

3. **Rule-based Routing**:
   - Allows for dynamic scripting and the use of various criteria such as domain names, IP addresses, and process names to determine the routing of traffic.

4. **Fake-IP DNS**:
   - Helps to mitigate the effects of DNS pollution and enhances network performance by using a fake IP address for DNS queries.

5. **Transparent Proxy**:
   - Capable of redirecting TCP and TProxy TCP/UDP traffic with automatic management of routing tables and rules.

6. **Proxy Groups**:
   - Offers features like automatic fallback, load balancing, or latency testing to optimize the use of multiple proxies.

7. **Remote Providers**:
   - Enables the dynamic loading of remote proxy lists, which can be useful for maintaining up-to-date proxy configurations.

8. **RESTful API**:
   - Provides a comprehensive API for updating the configuration in place, allowing for programmatic control over Clash's settings.

Clash's features make it a flexible tool for managing network traffic and can be particularly useful for users who require advanced proxy configurations and routing options.


## Documentation

You can find the latest documentation at [https://dreamacro.github.io/clash/](https://dreamacro.github.io/clash/).

## Credits

- [riobard/go-shadowsocks2](https://github.com/riobard/go-shadowsocks2)
- [v2ray/v2ray-core](https://github.com/v2ray/v2ray-core)
- [WireGuard/wireguard-go](https://github.com/WireGuard/wireguard-go)

## License

This software is released under the GPL-3.0 license.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDreamacro%2Fclash.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDreamacro%2Fclash?ref=badge_large)
