# Immortalwrt官方插件库对照表

| 序号 | 插件名                                | 中文名               | 作用说明                                   |
|:-----|:--------------------------------------|:---------------------|:-------------------------------------------|
| 1    | luci-app-3cat                      | 3CAT工具              | 提供3CAT服务集成（具体功能需查证）。           |
| 2    | luci-app-3ginfo-lite               | 3G/4G信息精简版      | 显示移动网络模块状态（信号强度、流量等）。     |
| 3    | luci-app-acl                       | ACL管理               | Luci中设置不同的用户角色，每个角色拥有不同的权限。 |
| 4    | luci-app-acme                      | ACME证书工具          | 自动申请和更新Let's Encrypt SSL证书。      |
| 5    | luci-app-adblock-fast              | 广告屏蔽（快速版）     | 高性能DNS广告过滤，减少延迟。               |
| 6    | luci-app-adblock                   | 广告屏蔽              | 通过DNS拦截广告域名。                     |
| 7    | luci-app-advanced-reboot           | 高级重启              | 支持安全模式、强制重启等选项。               |
| 8    | luci-app-airplay2                  | AirPlay2接收器       | 将路由器变为AirPlay2音频接收设备。         |
| 9    | luci-app-amule                     | aMule电驴下载         | eDonkey/Kad网络P2P下载工具。             |
| 10   | luci-app-antiblock                 | 反网络封锁            | 绕过地域限制（如DNS解锁）。                |
| 11   | luci-app-apinger                   | 网络延迟监控           | 实时监测Ping延迟和丢包率。                 |
| 12   | luci-app-appfilter                 | 应用流量过滤           | 按应用类型（游戏/视频）限制带宽。           |
| 13   | luci-app-argon-config              | Argon主题配置         | 管理OpenWrt的Argon主题界面。             |
| 14   | luci-app-aria2                     | Aria2下载器           | 支持HTTP/BT/Magnet的多线程下载工具。       |
| 15   | luci-app-arpbind                   | ARP绑定               | 防止ARP欺骗攻击（绑定IP与MAC）。           |
| 16   | luci-app-attendedsysupgrade        | 系统自动升级           | 检测并安装OpenWrt固件更新。               |
| 17   | luci-app-autoreboot                | 定时重启              | 设置计划任务定时重启路由器。                 |
| 18   | luci-app-babeld                    | Babel路由协议         | 支持多跳无线Mesh网络。                    |
| 19   | luci-app-banip                     | IP封禁工具            | 动态封禁恶意IP地址。                       |
| 20   | luci-app-bcp38                     | BCP38防IP伪造         | 防止伪造源IP的网络攻击。                   |
| 21   | luci-app-bitsrunlogin-go           | 比特校园网认证         | 用于校园网认证（如Dr.COM）。               |
| 22   | luci-app-bmx7                      | BMX7路由协议          | 无线Mesh网络协议支持。                    |
| 23   | luci-app-cd8021x                   | 802.1X企业认证        | 支持企业级网络认证（如EAP）。               |
| 24   | luci-app-chrony                    | Chrony时间同步        | 高精度NTP时间同步服务。                   |
| 25   | luci-app-cifs-mount                | CIFS共享挂载          | 挂载Windows/Samba网络共享文件夹。         |
| 26   | luci-app-clamav                    | ClamAV杀毒            | 轻量级病毒扫描工具。                       |
| 27   | luci-app-cloudflared               | Cloudflare隧道        | 通过Cloudflare建立安全远程访问。           |
| 28   | luci-app-commands                  | 自定义命令            | 在Web界面直接执行Shell命令。              |
| 29   | luci-app-coovachilli               | CoovaChilli热点认证   | 用于公共WiFi热点认证（如酒店）。           |
| 30   | luci-app-cpufreq                   | CPU频率调节           | 动态调整CPU频率以节能或提频。               |
| 31   | luci-app-cpulimit                  | CPU占用限制           | 限制特定进程的CPU使用率。                  |
| 32   | luci-app-crowdsec-firewall-bouncer | CrowdSec防火墙防护    | 集成CrowdSec的实时威胁防御。               |
| 33   | luci-app-csshnpd                   | CSSH节点管理          | 集群SSH管理工具（具体功能需查证）。         |
| 34   | luci-app-dae                       | DAE代理工具           | 高性能透明代理（类似Clash）。              |
| 35   | luci-app-daed                      | DAED代理工具          | DAE的衍生版本（功能优化）。                 |
| 36   | luci-app-dawn                      | 分布式无线管理         | 优化多AP间的无缝漫游（支持802.11k/v/r）。  |
| 37   | luci-app-dcwapd                    | DCWAPD服务           | 分布式无线控制协议支持（具体功能需查证）。     |
| 38   | luci-app-ddns-go                   | DDNS-Go动态域名       | 轻量级动态域名解析（支持多平台）。           |
| 39   | luci-app-ddns                      | 动态DNS服务           | 集成花生壳、DynDNS等DDNS服务商。           |
| 40   | luci-app-diskman                   | 磁盘管理工具           | 管理硬盘分区、RAID和挂载点。                |
| 41   | luci-app-docker                    | Docker容器支持        | 基础Docker容器管理功能。                   |
| 42   | luci-app-dockerman                 | Docker图形管理        | 增强版Docker Web管理界面。                |
| 43   | luci-app-dufs                      | Dufs文件服务器        | 简易HTTP文件共享服务。                    |
| 44   | luci-app-dump1090                  | Dump1090航空信号接收  | 接收飞机ADS-B信号（需硬件支持）。           |
| 45   | luci-app-email                     | 邮件通知工具           | 发送系统状态邮件报警。                      |
| 46   | luci-app-eoip                      | EOIP隧道工具          | 基于以太网的IP隧道（类似VPN）。             |
| 47   | luci-app-eqos                      | 平等QoS管理           | 按IP/端口分配带宽优先级。                   |
| 48   | luci-app-example                   | 示例插件              | OpenWrt开发模板（无实际功能）。             |
| 49   | luci-app-filebrowser-go            | 文件浏览器（Go版）     | 轻量级Web文件管理器。                      |
| 50   | luci-app-filebrowser               | 文件浏览器            | 旧版文件管理工具。                          |
| 51   | luci-app-filemanager               | 文件管理器            | 支持文件上传、下载、编辑的Web工具。          |
| 52   | luci-app-firewall                  | 防火墙管理            | 配置IPv4/IPv6防火墙规则。                 |
| 53   | luci-app-frpc                      | Frp内网穿透客户端      | 通过Frp实现内网服务外网访问。               |
| 54   | luci-app-frps                      | Frp内网穿透服务端      | 搭建Frp服务器端。                         |
| 55   | luci-app-fwknopd                   | Fwknopd单包授权       | 增强SSH等服务的访问安全。                   |
| 56   | luci-app-gost                      | GOST代理工具          | 多协议代理（支持SOCKS5/HTTP等）。         |
| 57   | luci-app-hd-idle                   | 硬盘休眠工具           | 设置硬盘自动休眠以节能。                     |
| 58   | luci-app-homeproxy                 | imm官方代理工具       | 简化代理服务器配置（如科学上网）。            |
| 59   | luci-app-https-dns-proxy           | HTTPS DNS代理        | 加密DNS查询（如Cloudflare DNS-over-HTTPS）。 |
| 60   | luci-app-ipsec-vpnd                | IPSec VPN服务端       | 搭建IPSec VPN服务器。                    |
| 61   | luci-app-irqbalance                | IRQ中断平衡           | 优化CPU中断分配以提升性能。                 |
| 62   | luci-app-k3screenctrl              | K3屏幕控制            | 管理斐讯K3路由器的OLED屏幕。               |
| 63   | luci-app-keepalived                | Keepalived高可用     | 实现网络服务高可用（VRRP协议）。            |
| 64   | luci-app-ksmbd                     | KSMBD共享服务         | 高性能SMB/CIFS文件共享（Linux内核级）。     |
| 65   | luci-app-ledtrig-rssi              | LED信号强度触发       | 根据WiFi信号强度控制LED灯。                |
| 66   | luci-app-ledtrig-switch            | LED开关触发           | 根据网络开关状态控制LED。                   |
| 67   | luci-app-ledtrig-usbport           | LED USB设备触发      | USB设备插入时触发LED灯。                  |
| 68   | luci-app-libreswan                 | Libreswan VPN        | 基于IPSec的VPN解决方案。                  |
| 69   | luci-app-lldpd                     | LLDP邻居发现          | 检测网络中的相邻设备（类似CDP）。            |
| 70   | luci-app-lorawan-basicstation      | LoRaWAN基站          | 支持LoRaWAN物联网网关。                   |
| 71   | luci-app-lxc                       | LXC容器管理           | 轻量级Linux容器管理工具。                   |
| 72   | luci-app-mentohust                 | MentoHUST认证        | 校园网锐捷认证客户端。                       |
| 73   | luci-app-microsocks                | MicroSocks代理       | 轻量级SOCKS5代理服务器。                   |
| 74   | luci-app-minidlna                  | MiniDLNA媒体服务器    | DLNA协议流媒体共享（视频/音乐）。           |
| 75   | luci-app-mjpg-streamer             | MJPG视频流           | 将USB摄像头转为网络视频流。                 |
| 76   | luci-app-modemband                 | 调制解调器频段控制      | 管理4G/5G模块的频段锁定。                   |
| 77   | luci-app-mosquitto                 | Mosquitto MQTT      | MQTT消息代理服务器（物联网协议）。           |
| 78   | luci-app-msd_lite                  | MSD Lite流媒体       | 高效能的UPnP流媒体服务器。                 |
| 79   | luci-app-music-remote-center       | 音乐远程控制           | 远程控制音乐播放器（如MPD）。                |
| 80   | luci-app-mwan3                     | 多WAN负载均衡         | 多宽带接入的流量分配和故障转移。               |
| 81   | luci-app-n2n                       | N2N VPN工具          | 点对点VPN组网工具。                        |
| 82   | luci-app-natmap                    | NAT端口映射           | 动态NAT端口转发管理。                      |
| 83   | luci-app-netdata                   | Netdata性能监控       | 实时系统性能监控仪表盘。                     |
| 84   | luci-app-nextdns                   | NextDNS配置          | 集成NextDNS加密DNS服务。                 |
| 85   | luci-app-nfs                       | NFS共享服务           | 网络文件系统（NFS）共享管理。                |
| 86   | luci-app-nft-qos                   | NFTables QoS        | 基于nftables的流量控制。                  |
| 87   | luci-app-ngrokc                    | Ngrok内网穿透         | 通过Ngrok实现内网穿透。                    |
| 88   | luci-app-njitclient                | 南京校园网认证         | 南京地区校园网认证客户端。                    |
| 89   | luci-app-nlbwmon                   | 网络带宽监控           | 实时统计设备流量使用情况。                    |
| 90   | luci-app-nps                       | NPS内网穿透           | 轻量级内网穿透工具。                         |
| 91   | luci-app-nut                       | NUT UPS监控          | 不间断电源（UPS）状态监控。                  |
| 92   | luci-app-ocserv                    | OpenConnect VPN     | 搭建Cisco兼容的VPN服务器。                |
| 93   | luci-app-oled                      | OLED屏幕控制          | 管理路由器的OLED显示屏（如R2S）。            |
| 94   | luci-app-olsr-services             | OLSR服务发现          | OLSR Mesh网络的服务公告功能。              |
| 95   | luci-app-olsr-viz                  | OLSR拓扑可视化        | 图形化显示OLSR Mesh网络拓扑。              |
| 96   | luci-app-olsr                      | OLSR路由协议          | 优化链路状态路由（Mesh网络协议）。             |
| 97   | luci-app-omcproxy                  | OMC代理              | 组播代理服务（用于IPTV等）。                 |
| 98   | luci-app-openclash                 | OpenClash代理        | 集成Clash内核的代理工具（科学上网）。         |
| 99   | luci-app-openlist                  | OpenList网盘挂载     | 几乎可以挂载世面上的所有网盘以及本地磁盘         |
| 100  | luci-app-openvpn-server            | OpenVPN服务端        | 搭建OpenVPN服务器。                       |
| 101  | luci-app-openvpn                   | OpenVPN客户端        | 配置OpenVPN客户端连接。                    |
| 102  | luci-app-openwisp                  | OpenWISP管理         | 集中管理多个OpenWrt设备（企业级）。          |
| 103  | luci-app-oscam                     | OSCAM智能卡服务       | 数字电视智能卡共享服务。                      |
| 104  | luci-app-p910nd                    | 网络打印机服务         | 支持远程网络打印（LPR协议）。                 |
| 105  | luci-app-package-manager           | 软件包管理            | 图形化安装/卸载OpenWrt插件。                |
| 106  | luci-app-pagekitec                 | PageKite内网穿透     | 通过PageKite实现内网服务外网访问。           |
| 107  | luci-app-passwall                  | PassWall代理         | 多协议代理工具（支持SS/V2Ray/Trojan）。     |
| 108  | luci-app-pbr                       | 策略路由              | 基于策略的流量路由（如国内外分流）。             |
| 109  | luci-app-pppoe-relay               | PPPoE中继            | 转发PPPoE协议（用于多级路由）。               |
| 110  | luci-app-pppoe-server              | PPPoE服务端          | 搭建PPPoE服务器（如ISP认证）。              |
| 111  | luci-app-privoxy                   | Privoxy代理过滤      | 隐私增强的Web代理（广告过滤/防追踪）。         |
| 112  | luci-app-ps3netsrv                 | PS3网络共享           | 为PS3游戏机提供文件共享服务。                 |
| 113  | luci-app-qbittorrent               | qBittorrent下载      | 集成qBittorrent的BT下载工具。              |
| 114  | luci-app-qos                       | QoS流量控制           | 传统基于IP的带宽限制（旧版）。                 |
| 115  | luci-app-radicale2                 | Radicale日历服务器    | 轻量级CalDAV/CardDAV服务器。              |
| 116  | luci-app-ramfree                   | 内存清理工具           | 手动释放系统内存。                           |
| 117  | luci-app-rclone                    | Rclone云存储         | 挂载Google Drive/OneDrive等云盘。        |
| 118  | luci-app-rp-pppoe-server           | RP-PPPoE服务端       | 另一种PPPoE服务器实现。                      |
| 119  | luci-app-rustdesk-server           | RustDesk服务器       | 自建RustDesk远程桌面服务器。                |
| 120  | luci-app-samba4                    | Samba4文件共享        | 提供Windows兼容的网络文件共享（SMB协议）。     |
| 121  | luci-app-scutclient                | 华南理工校园网认证     | 华南理工大学校园网认证客户端。                  |
| 122  | luci-app-ser2net                   | 串口转网络工具         | 将串口设备（如单片机）转为TCP/IP访问。         |
| 123  | luci-app-smartdns                  | SmartDNS域名解析     | 智能DNS分流（国内外域名优化解析）。            |
| 124  | luci-app-sms-tool-js               | 短信工具（JS版）       | 通过USB调制解调器发送/接收短信。              |
| 125  | luci-app-snmpd                     | SNMP监控服务          | 提供SNMP协议的系统监控数据。                  |
| 126  | luci-app-softether                 | SoftEther VPN       | 多功能VPN服务器（支持L2TP/IPSec/OpenVPN）。 |
| 127  | luci-app-softethervpn              | SoftEther VPN管理   | SoftEther的增强管理界面。                   |
| 128  | luci-app-splash                    | 热点认证页面           | 公共WiFi的认证跳转页面（如酒店）。             |
| 129  | luci-app-spotifyd                  | Spotify音乐播放器    | 轻量级Spotify客户端（命令行版）。             |
| 130  | luci-app-sqm                       | SQM QoS             | 智能队列管理（优化网络延迟）。                  |
| 131  | luci-app-squid                     | Squid代理缓存         | HTTP代理服务器（支持缓存加速）。               |
| 132  | luci-app-sshtunnel                 | SSH隧道工具           | 通过SSH创建加密隧道。                       |
| 133  | luci-app-statistics                | 统计图表              | 收集并显示CPU/内存/流量等数据。               |
| 134  | luci-app-strongswan-swanctl        | StrongSwan VPN      | 基于swanctl配置的IPSec VPN工具。           |
| 135  | luci-app-syncdial                  | 多拨助手              | 单线多拨（宽带叠加）。                        |
| 136  | luci-app-syncthing                 | Syncthing同步工具    | 分布式文件同步（类似Resilio Sync）。         |
| 137  | luci-app-sysuh3c                   | 中山大学校园网认证     | 中山大学H3C认证客户端。                      |
| 138  | luci-app-timewol                   | 定时网络唤醒           | 按计划唤醒局域网设备（WOL）。                  |
| 139  | luci-app-tinyproxy                 | TinyProxy轻量代理    | 小型HTTP代理服务器。                        |
| 140  | luci-app-tor                       | Tor匿名网络           | 配置Tor匿名代理服务。                        |
| 141  | luci-app-transmission              | Transmission下载     | 集成Transmission的BT下载工具。             |
| 142  | luci-app-travelmate                | 旅行WiFi助手          | 自动切换可用的无线热点（如出差使用）。            |
| 143  | luci-app-ttyd                      | TTYD网页终端          | 通过浏览器访问路由器的命令行界面。                |
| 144  | luci-app-ua2f                      | UA2F防火墙工具        | 修改User-Agent以绕过检测（如校园网）。        |
| 145  | luci-app-udpxy                     | UDPxy组播转发        | 将IPTV组播流转为HTTP单播流。                |
| 146  | luci-app-uhttpd                    | uHTTPd Web服务器     | OpenWrt默认的轻量级Web服务器。              |
| 147  | luci-app-unblockneteasemusic       | 解锁网易云音乐         | 绕过网易云音乐地域限制。                       |
| 148  | luci-app-unbound                   | Unbound DNS解析     | 递归DNS服务器（替代Dnsmasq）。               |
| 149  | luci-app-upnp                      | UPnP端口映射          | 自动为游戏/P2P应用配置端口转发。               |
| 150  | luci-app-usb-printer               | USB打印机共享         | 将USB打印机转为网络打印机。                    |
| 151  | luci-app-usteer                    | 无线负载均衡           | 优化多AP间的客户端分配（类似802.11k/v）。      |
| 152  | luci-app-v2raya                    | V2RayA代理管理        | 图形化配置V2Ray代理。                       |
| 153  | luci-app-vlmcsd                    | KMS激活服务器         | 搭建Windows/Office KMS激活服务器。        |
| 154  | luci-app-vnstat2                   | VnStat流量统计        | 监控网络流量使用情况（新版）。                   |
| 155  | luci-app-vsftpd                    | VSFTPD文件服务器      | FTP服务器工具（支持匿名登录）。                 |
| 156  | luci-app-watchcat                  | 看门狗监控             | 检测网络故障并自动重启。                        |
| 157  | luci-app-wechatpush                | 微信推送通知           | 通过Server酱等发送路由器状态到微信。            |
| 158  | luci-app-wifischedule              | WiFi定时开关          | 按计划启用/禁用无线网络。                       |
| 159  | luci-app-wol                       | 网络唤醒工具           | 通过局域网唤醒设备（WOL）。                     |
| 160  | luci-app-xfrpc                     | XFRP内网穿透          | 基于Frp的轻量级内网穿透工具。                   |
| 161  | luci-app-xinetd                    | Xinetd服务管理        | 管理超级守护进程（如TFTP服务）。                |
| 162  | luci-app-xlnetacc                  | 迅雷快鸟加速           | 通过迅雷快鸟提升宽带速度（需会员）。               |
| 163  | luci-app-zerotier                  | ZeroTier组网工具      | 创建虚拟局域网（SD-WAN）。                    |
| 164  | Tailscale                          | Tailscale组网工具    | 与zerotier一样异地组网工具                    |

# Thanks
[immortalwrt官方插件库对照表](https://www.right.com.cn/forum/thread-8441841-1-1.html)
