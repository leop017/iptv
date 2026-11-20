# iptv

自建直播源名单，由 iptv-api 引擎自动测速筛选后生成，每 12 小时更新一次。

## 订阅地址（主链接，实时最新）

- TVBox 直播源（txt）：https://raw.githubusercontent.com/leop017/iptv/main/iptv.txt
- VLC / Kodi / 通用播放器（m3u）：https://raw.githubusercontent.com/leop017/iptv/main/iptv.m3u

## 国内备用镜像（gh-proxy，内容与主链接同步）

主链接打不开或很慢时用这两个：

- TVBox（txt）：https://gh-proxy.com/https://raw.githubusercontent.com/leop017/iptv/main/iptv.txt
- VLC / Kodi（m3u）：https://gh-proxy.com/https://raw.githubusercontent.com/leop017/iptv/main/iptv.m3u

## Kodi 用法

插件 → 从仓库安装 → PVR 客户端 → PVR IPTV Simple Client，配置里填上面的 m3u 地址，启用后在主界面「电视」栏目观看。本名单未配电子节目单（EPG）。

## 说明

- 仅含 IPv4 源；频道覆盖以当轮公开源实测存活为准，死源会在下一轮被剔除。
- 浙江移动内网源不在此名单内（外网测不到、订不到），请单独使用本地名单文件。
