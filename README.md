## 简介

### 👓 准确度高
项目选取了 **ipip.net**、**gaoyifan**、**苍狼山庄**、**纯真** IP 数据库和 **MaxMind** 中国大陆 IP 地址段信息进行合并、去重、整理操作。

### 🌍 CDN 分发
项目直接托管于 GitHub，并使用 CDN 全球分发，瞬间即可完成数据库的下载和加载，在较差的网络环境下也较容易完成数据库的更新。

### 🤖️ 自动化更新
本项目每天自动生成 GeoIP 文件，时刻保持最佳体验，无需人工干预。

## 📥 下载链接
| 📦 项目 | 📃 文件 | 🐙 GitHub RAW | 🚀 CDN 加速 |
|  :--:  |  :--:  |     :--:     |     :--:    |
| GeoIP2 CN | GeoIP-CN.mmdb | [点我下载](https://raw.githubusercontent.com/Jard1n/GeoIP/release/GeoIP-CN.mmdb) | [点我起飞](https://cdn.jsdelivr.net/gh/Jard1n/GeoIP@release/GeoIP-CN.mmdb) |
| GeoIP2 完整版 | GeoIP.mmdb | [点我下载](https://raw.githubusercontent.com/Jard1n/GeoIP/release/GeoIP.mmdb) | [点我起飞](https://cdn.jsdelivr.net/gh/Jard1n/GeoIP@release/GeoIP.mmdb) |

- 适用范围：Surge, Shadowrocket, QuantumultX, Clash等较新的代理工具

- GeoIP2 完整版新增类别（方便有特殊需求的用户使用）：
  - `cloudflare`（`GEOIP,CLOUDFLARE`）
  - `cloudfront`（`GEOIP,CLOUDFRONT`）
  - `facebook`（`GEOIP,FACEBOOK`）
  - `fastly`（`GEOIP,FASTLY`）
  - `google`（`GEOIP,GOOGLE`）
  - `netflix`（`GEOIP,NETFLIX`）
  - `telegram`（`GEOIP,TELEGRAM`）
  - `twitter`（`GEOIP,TWITTER`）

## 🏅 版权声明

本项目 Fork 自 [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip) 项目，并由 [Jard1n](https://github.com/Jard1n) 加以调整和修改。

项目中所使用的 IP 地址信息来自于 [苍狼山庄](https://ispip.clang.cn/)、[纯真IP](https://github.com/metowolf/iplist)、[IPIP.NET](https://github.com/17mon/china_ip_list)、[gaoyifan](https://github.com/gaoyifan/china-operator-ip)

GeoIP® 商标版权归 [MaxMind](https://www.maxmind.com/) 公司所有

License [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)
