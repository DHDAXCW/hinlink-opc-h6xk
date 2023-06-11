# 中文简体 | [English](https://github.com/DHDAXCW/NanoPi-R5S-2021/blob/main/EngLish.md)
# hinlink opc h66k h68k h69k
# 机场推荐 [ENET--IEPL内网专线接入](https://www.easy2023.com/#/register?code=Ut7iWMrk)
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## 未经许可不得用于任何商用用途。

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
- 仅支持MT7916 MT7921无线网卡
- 仅支持FM160，其他模块自行解决。或者pr来~
- 机器必须协12V供电，低了会导致无线网卡无法设置或者重启
- 机器开启温控风扇：启动项--rockchip-fam，点击启动即可
![image](https://github.com/DHDAXCW/hinlink-opc-h6xk/assets/74764072/3388c963-5407-455c-be91-d115e11f1552)
### mt7916 WiFi设置
- 第一次刷机上电，网络--里面没有弹出无线的不着急了。网卡第一次上电需要初始化，大概1分钟会在网络里面出现无线，如果供电不够大概5分钟-10分钟。
- 如果MT7916 5G设置好了出现6.xGHx信号，甚至手机搜不到信号表示初始化失败了，原因是供电不足。建议换12v2a以上即可。
- 本次教程只适用mt7916网卡，和mt7921差不多设置。
- 进入网络--无线--选择2.4g,点击修改
![image](https://github.com/DHDAXCW/hinlink-opc-h6xk/assets/74764072/4a8e7767-9c1f-4e00-b428-bb2b51297668)
![image](https://github.com/DHDAXCW/hinlink-opc-h6xk/assets/74764072/02a3e011-d6fb-4e73-bbaa-cb443c3d025e)
- 然后应用保存再应用保存。
- 进入网络--无线--选择5g,点击修改
![image](https://github.com/DHDAXCW/hinlink-opc-h6xk/assets/74764072/879bdd0a-4077-4ba6-9ef0-afebcfcdff52)
![image](https://github.com/DHDAXCW/hinlink-opc-h6xk/assets/74764072/326d4759-1598-4e5f-a462-b3cb6514e428)
- 最后应用保存再应用保存后自动跳回去，然后2.4g和5g全部启用后，信号就出来了~
![image](https://github.com/DHDAXCW/hinlink-opc-h6xk/assets/74764072/ef716071-bf10-4243-8a7c-e903cfdd4811)
### 5G模块启用方法
- 仅支持广和通fm160 ，其他模块自行解决。。。不要插**SIM2**
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
