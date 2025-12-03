# ImmortalWrt编译
## 使用

- Fork 这个仓库
- 本地创建`.config`文件
- 上传`.config` 文件到 GitHub 仓库
- 在Actions页面选择`ImmortalWrt Builder`
- 点击 `Run workflow` 开始编译

## config文件说明
- v23054.config为23.05.4版本，不再使用
- v24104.config为24.10.4版本，不含turboacc插件
- .config为24.10.4版本，加入了turboacc插件，在使用版本

## 当前.config 配置
|插件|功能|
|:-|:-|
|luci-app-adguardhome|去广告和跟踪拦截|
|luci-app-attendedsysupgrade|支持系统在线升级|
|luci-app-autoreboot|自动重启设备|
|luci-app-diskman|磁盘管理工具|
|luci-app-dockerman|Docker容器管理器|
|luci-app-eqos|网速控制|
|luci-app-homeproxy|ImmortalWrt代理平台|
|luci-app-nikki|Mihomo透明代理|
|luci-app-momo|singbox插件|
|luci-app-lucky|端口转发,动态域名服务,http/https反向代理|
|luci-app-mosdns| DNS 转发/分流器|
|luci-app-nlbwmon|网络带宽监控|
|luci-app-onliner|在线用户查看|
|luci-app-partexp|一键分区扩容挂载工具|
|~~luci-app-passwall~~|~~PassWall代理工具~~|
|luci-app-store|store应用商店|
|luci-app-timewol|定时唤醒|
|luci-app-ttyd|Web终端|
|luci-app-upnp|通用即插即用（UPnP）|
|luci-app-wechatpush|推送通知插件|
|~~luci-app-easytier~~|~~EasyTier一个简单、安全、去中心化的内网穿透 VPN 组网方案~~|
|luci-app-vlmcsd|KMS 服务器|
|luci-app-tailscale|Tailscale虚拟局域网|
|luci-app-zerotier|ZeroTier虚拟网络|
|luci-app-turboacc|Turbo ACC 网络加速（no sfe），已在action中加入代码，编译无问题|

## 致谢

- [Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [immortalwrt/immortalwrt](https://github.com/immortalwrt/immortalwrt)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)
- [luci-app-turboacc](https://github.com/chenmozhijin/turboacc)

