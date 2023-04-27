# 中文简体 | [English](https://github.com/DHDAXCW/NanoPi-R5S-2021/blob/main/EngLish.md)
# hinlink opc h66k h68k h69k
# 机场推荐 [ENET--IEPL内网专线接入](https://www.easy2023.com/#/register?code=Ut7iWMrk)
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## 未经许可不得用于任何商用用途。
# 网卡顺序
- 在我这里固件上是按eth0 eth1 eth2 eth3顺序来的，硬件上走线是没错的.只是因为之前软件导致的丝印才打到外壳eth1和eth0反了
- 如图所示，eth0作为wan，eth1 eth2 eth3都是lan
![image](https://user-images.githubusercontent.com/74764072/234072275-53d393ce-60a8-4a32-b1b5-cb0b6b8bdd97.png)

### 注：不要用恢复备份。。不保证某个插件是否正常运行。。。建议重新设置贼好！

### 源代码地址
- lede https://github.com/DHDAXCW/lede-rockchip
- Luci https://github.com/DHDAXCW/luci
- packages https://github.com/DHDAXCW/packages

### 默认编译

- 用户名：root 密码：password  管理IP：192.168.11.1
- 下载地址： https://github.com/DHDAXCW/hinlink-opc-h6xk/releases
- 关于线刷机方法请参考dn2刷机 https://github.com/DHDAXCW/DoorNet-1-2/blob/mere/emmc.md
- 烧录软件内置提供：rk356x-MiniLoaderAll.bin
- 电报群：https://t.me/DHDAXCW
- X86固件 ：[点击链接下载](https://github.com/DHDAXCW/OpenWRT_x86_x64/releases)
- 仅支持MT7921无线网卡 全新刷机第一次开机网卡需要初始化，等2分钟无线自己会显示在网络里面

### 5G模块启用方法
- 不管是广和通fm160或者移远rm500q都可以用  不要插**SIM2**
- 网络--USB移动网络拨号服务
- APN:移动：cmnet  联通：3gnet 电信：ctnet
![1682406728444](https://user-images.githubusercontent.com/74764072/234201770-3a796152-5873-4152-a34b-705eeb49bfd4.jpg)

- 创建WWA进行拨号：网络--接口--新建接口
![image](https://user-images.githubusercontent.com/74764072/234204127-8c40ef24-2e15-4991-a13b-b133bb97b38c.png)

- WWAN-编辑--绑定防火墙
![image](https://user-images.githubusercontent.com/74764072/234204460-ae98b1d5-85b6-4c28-8b17-1926b5f8f6ce.png)

- 最后成功拨号
![image](https://user-images.githubusercontent.com/74764072/234204830-708bca0e-c135-4d0c-bd10-c8a1fb0ca288.png)

# 插件展示
 
 ![image](https://user-images.githubusercontent.com/74764072/183227361-e8bdb023-5514-437d-97e8-e13ca4285035.png)

# [赏个鸡腿吧](https://afdian.net/@dhdaxcw/plan)
### https://afdian.net/@dhdaxcw/plan

## 鸣谢

特别感谢以下项目：

Openwrt 官方项目：

<https://github.com/openwrt/openwrt>

Lean 大的 Openwrt 项目：

<https://github.com/coolsnowwolf/lede>

immortalwrt 的 OpenWrt 项目：

<https://github.com/immortalwrt/immortalwrt>

P3TERX 大佬的 Actions-OpenWrt 项目：

<https://github.com/P3TERX/Actions-OpenWrt>

SuLingGG 大佬的 Actions 编译框架 项目：

https://github.com/SuLingGG/OpenWrt-Rpi
