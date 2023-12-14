# CasaOS-AppStore-Play

🤪 A not-so-serious CasaOS App Store.

🤪 一个不是很正经的 CasaOS 应用商店。

🛠 [YAML Generator 生成器](https://play.cuse.eu.org/generate) : It is easy for user to make the appstore yaml files.

🔽 [App List / 应用列表](#app-list--应用列表)

## Features / 特色

 - Rich third-party applications / 丰富的第三方应用 <sup>30+</sup>
 - Use of the `:latest` tag / 使用 `:latest` 标签 <sup>[Why?](https://github.com/Cp0204/CasaOS-AppStore-Play/issues/2#issuecomment-1647335915)</sup>
 - Unsuitable for official AppStore / 不适宜官方上架的
 - Niche Featured Apps / 种花家小众特色应用
 - Support for Multi-arch & Fix armv7 / 多架构支持和修复armv7 [👇🏻](#arch-specific-source--分架构专属源)

> Note: This store app uses the `:latest` tag, the ┆ check for updates function in the upper right corner of the app will be disabled, but **you can manually edit the app settings once (without changing anything) to get the latest image.** The good thing is that you can always get the latest version of the app even if the store is unmaintained.

> 注意：本商店应用使用 `:latest` 标签，应用右上角┆检查更新功能会失效，但**你可以手动编辑一次应用设置（无需修改任何参数）获取最新镜像**。好处是即使商店无人维护，你总能获得应用的最新版本。

## Source link / 源地址

```
https://play.cuse.eu.org/Cp0204-AppStore-Play.zip
```

This is just a generic version, please add the following sources corresponding to the architecture for best support if possible.

这只是一个通用版本，请尽可能添加以下对应架构的源，以获得最佳支持。

### Arch-specific Source / 分架构专属源

<details>

<summary>arm/armv7/armhf (玩客云 等)</summary>

Adds older versions of some applications that [LinuxServer has dropped support](https://www.linuxserver.io/blog/a-farewell-to-arm-hf) for, and fixes an issue where the official app store fails to install and upgrade.

添加部分 [LinuxServer 已放弃支持](https://www.linuxserver.io/blog/a-farewell-to-arm-hf)的应用的旧版本，修复官方应用商店无法安装和升级的问题.

```
https://play.cuse.eu.org/Cp0204-AppStore-Play-arm.zip
```

</details>

<details>

<summary>arm64/armv8 (S905盒子、RK33xx 等)</summary>

```
https://play.cuse.eu.org/Cp0204-AppStore-Play-arm64.zip
```

</details>

<details>

<summary>amd64/x86-64 (一般云主机、工控机 等)</summary>

```
https://play.cuse.eu.org/Cp0204-AppStore-Play-amd64.zip
```

</details>


## Donate / 赞助

If you think this project is helpful to you, you can give me a little support. Thank you very much.

如果你觉得这个项目对你有帮助，可以给我一点点支持，非常感谢～

![WeChatPay](https://github.com/Cp0204/CasaOS-AppStore-Play/assets/5239753/d6693654-a967-40f5-a879-ac5109136b4f)

## App List / 应用列表

| Icon | AppName | Description |
|:----:|---------|-------------|
| ![Adminer](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/adminer/icon.png) | [Adminer](./Apps/adminer) | Adminer is a database management tool that allows you to manage your databases with a simple and intuitive interface.<br>Adminer 是一个数据库管理工具，它通过简单直观的界面帮助您管理数据库。 |
| ![Alist](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Alist/icon.png) | [Alist](./Apps/Alist) | A file list program that supports multiple storage, powered by Gin and Solidjs.<br>一个支持多种存储的文件列表程序，使用 Gin 和 Solidjs。 |
| ![Aria2 Pro](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/aria2-pro/icon.png) | [Aria2 Pro](./Apps/aria2-pro) | Aria2 is currently the most powerful and versatile download tool. It supports various downloading protocols such as BT, magnet, HTTP, and FTP, and is commonly used as a server for offline downloading. https://p3terx.com/archives/docker-aria2-pro.html<br>Aria2 是目前最强大的全能型下载工具，它支持 BT、磁力、HTTP、FTP 等下载协议，常用做离线下载的服务端。https://p3terx.com/archives/docker-aria2-pro.html |
| ![BaiduNetDisk](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/baidunetdisk/icon.png) | [BaiduNetDisk](./Apps/baidunetdisk) | Baidu Netdisk is a cloud storage product carefully crafted by Baidu for users, providing huge space. Full format files such as photos, videos, documents, and compressed files can be backed up to the cloud with just one click, providing you with comprehensive data protection. No matter the size of the files, you can share them with others with just one click, improving work and learning efficiency.<br>百度网盘是百度为用户精心打造的云存储产品，提供超大空间。照片、视频、文档、压缩包等全格式文件一键备份到云端，全方位为你数据保驾护航，无论文件大小一键分享他人，提升工作学习效率。 |
| ![BiliBiliToolPro](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/BiliBiliToolPro/icon.png) | [BiliBiliToolPro](./Apps/BiliBiliToolPro) | BiliBiliTool is a tool that automatically performs tasks. When we forget to do a certain task, it is like a caring assistant that follows the commands we have given it in advance, helping us complete the planned tasks within the specified frequency and time range.<br>BiliBiliTool 是一个自动执行任务的工具，当我们忘记做某项任务时，它会像一个贴心小助手，按照我们预先吩咐它的命令，在指定频率、时间范围内帮助我们完成计划的任务。 |
| ![ChatGPT Next Web](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/ChatGPT-Next-Web/icon.png) | [ChatGPT Next Web](./Apps/ChatGPT-Next-Web) | An intelligent chat application based on ChatGPT, supports fast deployment, Markdown, beautiful UI, fluid response, privacy and security, and allows customization of preset roles for quick creation, sharing, and debugging of personalized conversations.<br>一个基于 ChatGPT 的智能聊天应用，支持快速部署、Markdown 支持、精美 UI、流式响应、隐私安全等多个功能，并且能够自定义预制角色快速创建、分享和调试个性化对话。 |
| ![ddns-go](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/ddns-go/icon.png) | [ddns-go](./Apps/ddns-go) | A simple and easy-to-use DDNS (Dynamic Domain Name System) that automatically updates your domain name resolution to your public IP address. It supports various cloud services such as Alibaba Cloud, Tencent Cloud, Dnspod, Cloudflare, Callback, Huawei Cloud, Baidu Cloud, Porkbun, GoDaddy, and Google Domain.<br>简单好用的DDNS。自动更新域名解析到公网IP(支持阿里云、腾讯云、Dnspod、Cloudflare、Callback、华为云、百度云、Porkbun、GoDaddy、Google Domain) |
| ![Tailscale Derper](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Tailscale/icon.png) | [Tailscale Derper](./Apps/derper) | Tailscale Derper is a lightweight utility that allows you to serve your own Tailscale relays for better performance and control over your network traffic. Configure your DERP server with ease and enhance your Tailscale VPN experience.<br>Tailscale Derper是一个轻量级实用程序，允许您为Tailscale VPN服务提供自己的中继服务器，从而提供更好的性能和对网络流量的控制。轻松配置您的DERP服务器，增强Tailscale VPN体验。 |
| ![EasyImage](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/easyimage/icon.png) | [EasyImage](./Apps/easyimage) | Supporting multi -file upload, simple countless data library, returning picture URL, Markdown, bbscode, html picture warehouse program. Demo: https://png.cm/<br>支持多文件上传，简单无数据库，返回图片url、markdown、bbscode、html的一款图床程序，演示地址：https://png.cm/  |
| ![Excalidraw](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Excalidraw/icon.png) | [Excalidraw](./Apps/Excalidraw) | Excalidraw is a virtual collaborative whiteboard tool that lets you easily sketch diagrams, illustrate ideas, and create beautiful illustrations remotely.<br>Excalidraw是一款虚拟协作白板工具，可以让您轻松绘制图表、阐明思想和远程创建精美的插图。 |
| ![FAST OS DOCKER](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/fast-os-docker/icon.png) | [FAST OS DOCKER](./Apps/fast-os-docker) | FAST OS DOCKER is a graphical management tool for Docker, providing users with Docker overview, local container management, remote image pulling, server disk mapping, server network management, and more. It can meet the container management needs of small to medium-sized organizations.<br>FAST OS DOCKER是Docker的图形化管理工具，为用户提供了Docker总览、本地容器管理、远程镜像拉取、服务器磁盘映射、服务器网络管理等功能，基本能满足中小型单位对容器管理的全部需求。 |
| ![frpc](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/frpc/icon.png) | [frpc](./Apps/frpc) | A fast reverse proxy client that helps you expose a local server to the internet. It provides client authentication and supports multiple protocols.<br>一个快速的反向代理客户端，可以帮助您将本地服务器暴露到互联网。它提供客户端认证并支持多种协议。 |
| ![frps](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/frps/icon.png) | [frps](./Apps/frps) | A fast reverse proxy server that helps you expose a local server to the internet. It provides client authentication and supports multiple protocols.<br>一个快速的反向代理服务器，可以帮助您将本地服务器暴露到互联网。它提供客户端认证并支持多种协议。 |
| ![Gopeed](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/gopeed/icon.png) | [Gopeed](./Apps/gopeed) | Gopeed (full name Go Speed) is a high-speed downloader developed by Golang + Flutter. It supports (HTTP, BitTorrent, Magnet) protocols and is compatible with all platforms. In addition to basic download functions, Gopeed is highly customizable, supporting additional features through API integration or by installing and developing extensions.<br>Gopeed（全称 Go Speed）是一款由 Golang + Flutter 开发的高速下载器，支持（HTTP、BitTorrent、Magnet）协议下载，并且支持全平台使用。除了基本的下载功能外，Gopeed 还是一款高度可定制化的下载器，支持通过对接 APIs 或者安装和开发扩展来实现更多的功能。 |
| ![Gotify](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Gotify/icon.png) | [Gotify](./Apps/Gotify) | A self-hosted push notification service written in Go. It simplifies the sending and receiving of push notifications over multiple platforms.<br>一个使用Go编写的自托管推送通知服务。它简化了在多个平台上发送和接收推送通知的过程。 |
| ![Heimdall](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/heimdall/icon.png) | [Heimdall](./Apps/heimdall) | As the name suggests Heimdall Application Dashboard is a dashboard for all your web applications. It doesn't need to be limited to applications though, you can add links to anything you like.  Heimdall is an elegant solution to organise all your web applications.<br>顾名思义，Heimdall Application Dashboard 是一个用于显示所有网络应用程序的仪表盘。但它并不局限于应用程序，你可以添加任何你喜欢的链接。 Heimdall 是组织所有网络应用程序的优雅解决方案。 |
| ![homepage](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/homepage/icon.png) | [homepage](./Apps/homepage) | A modern, fully static, fast, secure fully proxied, highly customizable application dashboard with integrations for over 100 services and translations into multiple languages. Easily configured via YAML files or through docker label discovery.<br>一个现代化的、完全静态的、快速的、安全的、完全代理的、高度可定制的应用程序仪表板，集成了100多种服务和多种语言的翻译。通过YAML文件或Docker标签发现轻松配置。 |
| ![Komga](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/komga/icon.png) | [Komga](./Apps/komga) | Komga is a versatile platform that provides a responsive web UI for effortless browsing of libraries, series, and books across various devices. Users can efficiently organize their libraries using collections and read lists, while also having the ability to edit metadata for series and books.<br>Komga 是一个多功能平台，提供了响应式的 Web UI，让用户能够轻松浏览图书馆、系列和图书，适用于桌面、平板和手机等多种设备。用户可以通过集合和阅读列表高效地组织图书馆，同时还可以编辑系列和图书的元数据。该平台提供了具有多种阅读模式的 Web 阅读器，确保用户流畅的阅读体验。 |
| ![KPlayer](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/KPlayer/icon.png) | [KPlayer](./Apps/KPlayer) | KPlayer can help you quickly perform looped live streaming of video resources on the server, simply customize the configuration file to enable live streaming.<br>KPlayer 可以帮助你快速在服务器上进行视频资源的循环直播推流，只需要简单修改配置文件即可开启直播推流。 |
| ![LanCache](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/lancache/icon.png) | [LanCache](./Apps/lancache) | Make the most of your network. Get more play for your gamers. Download your games once and serve them out to many people at your LAN. The principle is to set up the NAS as a DNS server, hijack HTTP traffic to the NAS, cache the downloaded game files, and distribute them at high speed by the NAS when downloading again.<br>充分利用您的网络，为玩家带来更多乐趣。只需下载一次游戏，就可以向局域网中其他设备提供缓存高速下载。其原理是把NAS设为DNS服务器，劫持HTTP流量到NAS，缓存下载过的游戏文件，再次下载时由NAS高速分发。 |
| ![LANraragi](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/lanraragi/icon.png) | [LANraragi](./Apps/lanraragi) | LANraragi is a versatile comic archive management tool that supports various formats such as zip, rar, targz, lzma, 7z, xz, cbz, cbr, and pdf, with basic support for epub. Users can seamlessly read their comic archives directly from a web browser, as the server efficiently accesses compressed files using temporary folders.<br>LANraragi是一款多功能的漫画存档管理工具，支持多种格式，包括zip、rar、targz、lzma、7z、xz、cbz、cbr和pdf，同时对epub提供基本支持。用户可以直接从Web浏览器中无缝阅读其漫画存档，因为服务器通过临时文件夹有效地访问压缩文件。 |
| ![LinkAce](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/LinkAce/icon.png) | [LinkAce](./Apps/LinkAce) | Manage your bookmarks, links, and reading list with ease using LinkAce. Access your links from anywhere with a web browser.<br>使用LinkAce轻松管理书签、链接和阅读列表。通过Web浏览器随时随地访问您的链接。 |
| ![Lucky](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Lucky/icon.png) | [Lucky](./Apps/Lucky) | A powerful tool for port forwarding, reverse proxy, dynamic DNS, wake-on-LAN, IPv4 NAT traversal, task scheduling, and automatic certificate management.<br>一款功能强大的端口转发、反向代理、动态域名、网络唤醒、IPv4内网穿透、计划任务和自动证书管理工具。 |
| ![MariaDB](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/MariaDB/icon.png) | [MariaDB](./Apps/MariaDB) | MariaDB is a community-developed fork of MySQL and aims to be an enhanced, drop-in replacement for it.<br>MariaDB 是 MySQL 的社区开发分支，旨在成为其增强版的兼容替代品。 |
| ![MTG Proxy](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/mtg-proxy/icon.png) | [MTG Proxy](./Apps/mtg-proxy) | MTProto Proxy is a Telegram proxy server with support for all aspects of the protocol and multi-core processors. It provides a high level of privacy and security for your Telegram communication.<br>MTProto代理是一个支持Telegram协议的代理服务器，支持多核处理器。它为您的Telegram通信提供了高水平的隐私和安全性。 |
| ![nginxWebUI](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/nginxWebUI/icon.png) | [nginxWebUI](./Apps/nginxWebUI) | nginxWebUI is a graphical management of nginx configuration tool , you can use the web page to quickly configure the various functions of nginx , including http protocol forwarding , tcp protocol forwarding , reverse proxy , load balancing , static html server , ssl certificate automatically apply for , renew , configure and so on , configure a good can be built to generate the nginx.conf file , and can control nginx using this file startup and reload , to complete the nginx graphical control of the closed loop . At the same time you can control nginx use this file to start and reload, complete the graphical control of nginx closed loop.<br>nginxWebUI是一款图形化管理nginx配置得工具, 可以使用网页来快速配置nginx的各项功能, 包括http协议转发, tcp协议转发, 反向代理, 负载均衡, 静态html服务器, ssl证书自动申请、续签、配置等, 配置好后可一建生成nginx.conf文件, 同时可控制nginx使用此文件进行启动与重载, 完成对nginx的图形化控制闭环. |
| ![PandoraNext](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/pandora-next/icon.png) | [PandoraNext](./Apps/pandora-next) | Pandora Cloud + Pandora Server + Shared Chat + BackendAPI Proxy + Chat2API = PandoraNext. New GPTs(Gizmo) UI, All in one!<br>Pandora Cloud + Pandora Server + Shared Chat + BackendAPI Proxy + Chat2API = PandoraNext. New GPTs(Gizmo) UI, All in one! |
| ![php-nginx](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/php-nginx/icon.png) | [php-nginx](./Apps/php-nginx) | A Docker application that combines PHP-FPM and Nginx to serve PHP websites. It provides a convenient setup for running PHP applications with an Nginx web server.<br>一个将PHP-FPM和Nginx结合起来为PHP网站提供服务的Docker应用。它为使用Nginx作为Web服务器运行PHP应用程序提供了便捷的设置。 |
| ![Portainer](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Portainer/icon.png) | [Portainer](./Apps/Portainer) | Portainer is a lightweight management UI which allows you to easily manage your Docker environments. It is designed to be easy to use and offers full control over your Docker hosts and containers.<br>Portainer 是一个轻量级的管理界面，可让您轻松管理Docker环境。它被设计为易于使用，并提供对Docker主机和容器的完全控制。 |
| ![QingLong](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/qinglong/icon.png) | [QingLong](./Apps/qinglong) | QingLong is a platform for managing and executing scheduled tasks for Python3, JavaScript, Shell, and Typescript scripts.<br>青龙是一个用于管理和执行Python3、JavaScript、Shell和Typescript脚本的定时任务平台。 |
| ![Tailscaled](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/Tailscale/icon.png) | [Tailscaled](./Apps/Tailscale) | Tailscale is a zero config VPN for building secure networks. Install on any device in minutes. Remote access from any network or physical location.<br>Tailscale 是一款用于构建安全网络的零配置 VPN。只需几分钟即可在任何设备上安装，即可从任何网络或物理位置远程访问。 |
| ![tinyMediaManager](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/tinyMediaManager/icon.png) | [tinyMediaManager](./Apps/tinyMediaManager) | tinyMediaManager is a media management tool written in Java/Swing. It is designed to provide a simple and intuitive interface for organizing and managing your media collection.<br>tinyMediaManager 是一个用 Java/Swing 编写的媒体管理工具。它旨在为您的媒体收藏提供简单直观的界面，方便组织和管理。 |
| ![ttnode](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/ttnode/icon.png) | [ttnode](./Apps/ttnode) | TTNODE is a versatile platform that allows you to easily participate in various distributed computing projects. It supports a wide range of tasks and provides a user-friendly web interface for management.<br>甜糖星愿是一个多功能平台，可以轻松参与各种分布式计算项目。它支持广泛的任务，并提供了用户友好的Web界面进行管理。 |
| ![v2rayA](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/v2rayA/icon.png) | [v2rayA](./Apps/v2rayA) | V2RayA is a web-based V2Ray front-end with enhanced functionality. It provides an intuitive and user-friendly interface to configure and manage your V2Ray server. With V2RayA, you can easily set up and customize your own proxy server with various protocols and encryption methods.<br>V2RayA是一个带有增强功能的基于Web的V2Ray前端。它提供了一个直观和用户友好的界面，用于配置和管理V2Ray服务器。使用V2RayA，您可以轻松设置和自定义具有各种协议和加密方法的代理服务器。 |
| ![VerySync](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/verysync/icon.png) | [VerySync](./Apps/verysync) | A user-friendly, cross-platform file synchronization software with remarkable transfer speeds as its most significant advantage. VerySync's intelligent P2P technology accelerates synchronization by splitting files into small, data-only segments, and encrypting the files with AES.<br>简单易用的多平台文件同步软件，惊人的传输速度是不同于其他产品的最大优势， 微力同步 的智能 P2P 技术加速同步，会将文件分割成若干份仅 KB 的数据同步，而文件都会进行 AES 加密处理. |
| ![VS Code](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/vscode/icon.png) | [VS Code](./Apps/vscode) | Code with ease using Visual Studio Code on your server. Access it through your browser anywhere, anytime.<br>在您的服务器上轻松编写代码，使用Visual Studio Code。通过浏览器随时随地访问。 |
| ![XrayR](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/xrayr/icon.png) | [XrayR](./Apps/xrayr) | A Xray backend framework that can easily support many panels.<br>一个基于Xray的后端框架，支持V2ay,Trojan,Shadowsocks协议，极易扩展，支持多面板对接。 |
| ![Thunder](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/xunlei/icon.png) | [Thunder](./Apps/xunlei) | Xunlei remote download is a cross-regional remote control download mode, which can remotely control the remote downloader to download the task, which can really download the task anywhere.<br>迅雷远程下载是一种跨地域远程控制的下载方式，可以远程遥控异地下载器来下载任务，真正做到随地随地下载任务。 |
| ![YesPlayMusic](https://cdn.jsdelivr.net/gh/Cp0204/CasaOS-AppStore-Play@main/Apps/yesplaymusic/icon.png) | [YesPlayMusic](./Apps/yesplaymusic) | ✅ Developed using Vue.js stack, supports Netease Cloud login, MV playback, lyrics display, private FM, and daily recommendations. No social features, direct playback for overseas users, UnblockNeteaseMusic support, automatic check-ins, Light/Dark Mode switching, Touch Bar, PWA installation, Last.fm Scrobble, music cloud storage, custom shortcuts, Mpris, and more features in development. 🛠<br>✅ Vue.js全家桶开发，支持网易云登录、MV播放、歌词显示、私人FM、每日推荐。无社交功能，海外用户直接播放，支持UnblockNeteaseMusic，自动签到，Light/Dark Mode切换，Touch Bar，PWA安装，Last.fm Scrobble，音乐云盘，自定义快捷键，Mpris等。🛠 更多功能开发中。 |
