- 纯净版本
- 默认 IP：192.168.1.99 | 默认密码：password
===cutline===
- 默认 IP：192.168.1.99 | 默认密码：password
- OpenWrt-24.10 及 ImmortalWrt-24.10 固件系统分区由 23.05 固件的 720M 调整为 820M 。
- sing-box 裸核相关脚本文件安装使用方法见 ⌈ [sing-box 安装使用文档](https://github.com/ffuqiangg/build_openwrt/blob/main/doc/sing-box_new.md) ⌋
- packages.zip 压缩包内为 komd ipk 文件，LEDE 及 iStoreOS 固件可通过如下命令部署到本地源：
```bash
sh -c "$(curl -ksS https://testingcf.jsdelivr.net/gh/ffuqiangg/build_openwrt@main/files/local_feeds.sh)"
```