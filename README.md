#### 使用

一键命令

```yaml
sed -i '$a src-git kenzo https://github.com/kenzok8/openwrt-packages' feeds.conf.default
sed -i '$a src-git small https://github.com/kenzok8/small' feeds.conf.default
git pull
./scripts/feeds update -a
./scripts/feeds install -a
make menuconfig
```

- OpenWrt 固件编译自定义主题与软件

| 软件名称                    |    菜单名称     |
|:------------------------|:-----------:|
| luci-app-accesscontrol  |    时长控制     |
| luci-app-adbyby-plus    |  广告屏蔽Plus   |
| luci-app-advanced       |    高级设置     |
| luci-app-arpbind        |  IP/MAC绑定   |
| luci-app-autotimeset    |    定时设置     |
| luci-app-ddns           |    动态域名     |
| luci-app-diskman        |    磁盘管理     |
| luci-app-eqos           |   IP地址限速    |
| luci-app-filetransfer   |    文件传输     |
| luci-app-firewall       |    网络防火墙    |
| luci-app-frpc           |   FRP客户端    |
| luci-app-netspeedtest   |    网速测速     |
| luci-app-nlbwmon        |    带宽监控     |
| luci-app-oaf            |    应用过滤     |
| luci-app-onliner        |    在线用户     |
| luci-app-openclash      |  OpenClash  |
| luci-app-openvpn-server |   OpenVPN   |
| luci-app-parentcontrol  |    家长控制     |
| luci-app-partexp        |    分区扩容     |
| luci-app-poweroffdevice |    关机功能     |
| luci-app-samba4         |    网络共享     |
| luci-app-sqm            |    流量QoS    |
| luci-app-store          |    应用商店     |
| luci-app-ttyd           |   TTYD终端    |
| luci-app-turboacc       |    网络加速     |
| luci-app-unblockmusic   |    网易云解锁    |
| luci-app-upnp           |    动态端口     |
| luci-app-vlmcsd         |   KMS服务器    |
| luci-app-wizard         |    设置向导     |
| luci-app-wrtbwmon       |    流量统计     |
| luci-app-zerotier       |  ZeroTier   |
