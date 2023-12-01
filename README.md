## 简介

项目为[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)的修改版，和原项目有以下不同：

- 中国大陆（CN）IPv4、IPv6地址替换为 [苍狼山庄](https://ispip.clang.cn/)、[纯真IP](https://github.com/metowolf/iplist)、[IPIP.NET](https://github.com/17mon/china_ip_list)、[gaoyifan](https://github.com/gaoyifan/china-operator-ip) 的数据源

- 仅生成 MaxMind mmdb 格式的 GeoIP 数据库（适用于各种代理工具，例如 Surge、Clash）

- 项目每天自动化部署更新
  
https://raw.githubusercontent.com/Jard1n/GeoIP/release/GeoIP-CN.mmdb
https://cdn.jsdelivr.net/gh/Jard1n/GeoIP@release/GeoIP-CN.mmdb

## 📥 下载链接
| 📦 项目 | 📃 文件 | 🐙 GitHub RAW | 🚀 CDN 加速 | 🔧 适用范围
|  :--:  |  :--:  |     :--:     |     :--:    | ---- |
| GeoIP2 CN数据库 | GeoIP-CN.mmdb | [点我下载](https://raw.githubusercontent.com/Jard1n/GeoIP/release/GeoIP-CN.mmdb) | [点我起飞](https://cdn.jsdelivr.net/gh/Jard1n/GeoIP@release/GeoIP-CN.mmdb) |  |
| GeoIP2 数据库 | GeoIP.mmdb | [点我下载](https://raw.githubusercontent.com/Jard1n/GeoIP/release/GeoIP.mmdb) | [点我起飞](https://cdn.jsdelivr.net/gh/Jard1n/GeoIP@release/GeoIP.mmdb) | |

对于网络状况良好、无污染的环境下，建议选择 GitHub RAW 的方式下载，因为可以第一获取到最新的资源，因为服务器在境外，可能下载响应时间和速度稍长，但因为文件小，所以通常问题不大。

对于网络状况不好，存在污染的环境下，建议选择 CDN 加速的方式下载，速度非常快。但是可能存在缓存未更新的情况，很可能下载到旧的资源。
