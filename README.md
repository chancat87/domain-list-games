### **Fork from https://github.com/Loyalsoldier/domain-list-custom**
[![Build games.dat](https://github.com/KoinuDayo/domain-list-games/actions/workflows/build.yml/badge.svg)](https://github.com/KoinuDayo/domain-list-games/actions/workflows/build.yml)  
在[release分支](https://github.com/KoinuDayo/domain-list-games/tree/release)查看最新的发布。
# 简介
一个外置的 `games.dat` 文件，包含了一些常见游戏的域名。
# 如何使用
* Windows: 将文件放到v2/xray的执行目录。
* Linux: 将文件放到 `/usr/local/share/$type` 内。
* 路由设置 `ext:game.dat:tag`。
# 贡献
Fork这个仓库，在data文件夹加入你的游戏的域名文件，编辑添加按字典序排序的域名之后提交PR。  
格式： `data/游戏名/按字典序排序的域名` 。  
例：在 `data/rinbow6sidge` 文件内：
```
include:uplay

api-configuration-live01.live01.pc-live.r6.ubi.com
api-discovery.live01.pc-live.r6.ubi.com
d20i5e3rqc90ne.cloudfront.net
ingame-store.cdn.ubisoft.com
mercury.ubi.com
msr-public-ubiservices.ubi.com
msr-public-ubiservices.ubi.com
player.prod.r6.ubi.com
public-ubiservices.ubi.com
public-ws-ubiservices.ubi.com
r6logstorage05.blob.core.windows.net
r6pcaddons.azureedge.net
r6statuspc.azureedge.net
```
其中 `include` 的项可以是这个游戏需要的平台。
# 感谢
[@Loyalsoldier](https://github.com/Loyalsoldier)
# 灵感来源
[Loyalsoldier/v2ray-rules-dat/issues/16](https://github.com/Loyalsoldier/v2ray-rules-dat/issues/16#issuecomment-1642917630)
